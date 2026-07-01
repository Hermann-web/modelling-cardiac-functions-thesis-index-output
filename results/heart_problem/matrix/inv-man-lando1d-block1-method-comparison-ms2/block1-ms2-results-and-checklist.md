# Block 1 `ms2` Results And Checklist

## Scope

- Project: `lando1d`
- Preset: `default`
- Grid profile: `full`
- Active parameters: `alpha,gamma`
- Observation: identity/full-state through `n_sensors=0`, `observation_mode=default`
- Formulation: absolute through `n_refs=0`
- Noise: clean data, `noise_level=0`, `observation_noise_level=0`
- Seeds: `1234`, `2025`, `4096`

## Code Correction Before Final Rerun

- The matrix expander now sweeps `inverse_regularization_lambdas` only for:
  - `regularized_quadratic`
  - `regularized_full_nls`
  - `man_initialized_full_nls`
- Non-regularized methods collapse to `lambda=0`.
- Progress labels now include `lambda=...`.
- Stale/corrupted pre-fix run directories were deleted through `matrix-sync --delete-stale-runs`.
- The lambda rule now lives in `python/src/heart_problem/matrix/fields_resolution.py`.
- After that field-resolution patch, `matrix-sync --only-collect --delete-stale-runs` removed `22` stale duplicate `full_nls` directories and then confirmed `0` stale runs.

## Slope Gate

- Source spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml`
- Output folder: `output/results/heart_problem/matrix/inv-man-lando1d-block1-slope-ms2`
- Runs: `18/18 complete`
- Radii: `0.25,0.5,1,2,5,10`
- Lambda: `0`
- Median-across-seeds log-log slopes:
  - `test_forward_linear_error_median`: `1.99012`
  - `test_forward_quadratic_error_median`: `2.98749`
  - `test_true_forward_residual_median`: `2.97934`
  - `active_test_mae`: `3.01433`

## Method And Lambda Comparison

- Source spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- Output folder: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2`
- Runs: `108/108 complete`
- Lambda grid for regularized methods: `0`, `1e-10`, `1e-8`, `1e-6`, `1e-4`
- Non-regularized models evaluated only at `lambda=0`.

| radius | method | lambda | median active error | median true forward residual |
|---:|---|---:|---:|---:|
| 2 | `man_initialized_full_nls` | `1e-10` | `2.47735e-10` | `2.03583e-11` |
| 2 | `man_initialized_full_nls` | `0` | `2.50866e-10` | `2.62994e-11` |
| 2 | `explicit_quadratic` | `0` | `1.88851e-07` | `3.20770e-08` |
| 2 | `regularized_quadratic` | `1e-6` | `4.67696e-07` | `5.91950e-07` |
| 2 | `full_nls` | `0` | `8.35256e-07` | `1.29719e-07` |
| 2 | `born` | `0` | `6.01653e-05` | `7.87033e-05` |
| 10 | `man_initialized_full_nls` | `0` | `7.22933e-09` | `2.87478e-12` |
| 10 | `man_initialized_full_nls` | `1e-10` | `7.23341e-09` | `2.74813e-11` |
| 10 | `full_nls` | `0` | `5.53744e-08` | `1.69249e-08` |
| 10 | `explicit_quadratic` | `0` | `2.47650e-05` | `3.75035e-06` |
| 10 | `regularized_quadratic` | `1e-4` | `4.65075e-05` | `5.02253e-05` |
| 10 | `born` | `0` | `1.52200e-03` | `1.83310e-03` |

## Runtime Export

- `results.csv` now exposes `training_time_seconds` and `evaluation_time_seconds`.
- The curated claim figures include a time-accuracy ladder plot in the same matrix `export` folder.
- Median `training_time_seconds` across completed runs:

| method | completed runs | median training seconds | max training seconds |
|---|---:|---:|---:|
| `born` | 6 | `0.201547` | `0.216994` |
| `explicit_quadratic` | 6 | `0.209501` | `0.217929` |
| `regularized_quadratic` | 30 | `0.214903` | `0.267097` |
| `man_initialized_full_nls` | 30 | `1.61133` | `1.86371` |
| `full_nls` | 6 | `4.61622` | `4.89920` |
| `regularized_full_nls` | 30 | `4.63601` | `5.12164` |

Evaluation time is negligible here, with median values near `6e-06` seconds across methods.

## Checklist

- [x] Removed fake lambda sweep for non-regularized models.
- [x] Deleted stale pre-fix matrix run directories through `matrix-sync`.
- [x] Clean slope sweep rerun after solver reset and matrix-axis fix.
- [x] Linear forward approximation error shows slope near `2`.
- [x] Quadratic forward approximation error shows slope near `3`.
- [x] True nonlinear forward residual is populated.
- [x] Born baseline included.
- [x] Explicit quadratic inverse included.
- [x] Regularized quadratic inverse included with lambda sweep.
- [x] Full PDE-constrained NLS included.
- [x] Regularized full NLS included with lambda sweep.
- [x] MAN-initialized full NLS included with lambda sweep.
- [x] Curated claim figures exported and indexed.
- [x] Training and evaluation time columns exported to `results.csv`.
- [x] Runtime evidence exported through the time-accuracy claim figure.
- [ ] Add noisy-data sweep.
- [ ] Block 2 alpha-basis rerun after Block 1 is accepted.

## Interpretation

- Explicit quadratic inversion strongly improves over Born on the clean Block 1 surface.
- MAN-initialized full NLS is the strongest clean-data method on this run.
- MAN-initialized full NLS is also a real runtime compromise: it is about `7.7x` slower than explicit quadratic by median training time, but about `2.9x` faster than full NLS.
- Regularization does not help the clean-data quadratic inverse here; the best regularized-quadratic result is still worse than explicit quadratic.
- The lambda sweep is now meaningful because it is limited to regularized model families.
- These results support clean-data Block 1 validation. They do not yet support noise robustness, functional coefficient recovery, or IBS comparison claims.
