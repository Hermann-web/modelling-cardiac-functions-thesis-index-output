# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2/export/claim-06-noisy-regularization-by-model-lambda-line.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml --kind line --x observation_noise --y test_clean_forward_residual_median --hue inverse_regularization_lambda --group-row radius_pct --group-col model --rank-order lower --select best --filter 'observation_noise>0' --filter 'model!=born' --filter 'model!=explicit_quadratic' --filter 'model!=full_nls' --aggregate median --x-scale log --y-scale log --output-name claim-06-noisy-regularization-by-model-lambda-line.png --intent 'Claim 6 diagnostic: clean-forward residual versus observation noise, split by model and regularization lambda for regularized inverse families.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 6 diagnostic: clean-forward residual versus observation noise, split by model and regularization lambda for regularized inverse families.`
