# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2/export/claim-06-regularized-quadratic-clean-not-winner.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml --kind bar --x model --y active_test_mae --hue radius_pct --rank-by active_test_mae --rank-reduce-by inverse_regularization_lambda --rank-reduce-agg median --rank-order lower --select best --filter observation_noise=0 --filter 'model!=born' --filter 'model!=full_nls' --filter 'model!=regularized_full_nls' --filter 'model!=man_initialized_full_nls' --aggregate median --y-scale log --output-name claim-06-regularized-quadratic-clean-not-winner.png --intent 'Claim 6: on clean data, the best regularized quadratic inverse remains worse than explicit quadratic at both tested radii.' --dpi 200
```

## Details

- kind: `bar`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 6: on clean data, the best regularized quadratic inverse remains worse than explicit quadratic at both tested radii.`
