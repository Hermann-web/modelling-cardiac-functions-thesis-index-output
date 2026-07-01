# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2/export/claim-04-clean-method-accuracy-lambda0.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml --kind bar --x model --y active_test_mae --hue radius_pct --rank-order lower --select best --filter observation_noise=0 --filter inverse_regularization_lambda=0 --filter 'model!=born' --filter 'model!=regularized_quadratic' --filter 'model!=regularized_full_nls' --aggregate median --y-scale log --output-name claim-04-clean-method-accuracy-lambda0.png --intent 'Claim 4: full NLS is not the enemy; MAN-initialized full NLS is the strongest clean-data reconstruction method.' --dpi 200
```

## Details

- kind: `bar`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 4: full NLS is not the enemy; MAN-initialized full NLS is the strongest clean-data reconstruction method.`
