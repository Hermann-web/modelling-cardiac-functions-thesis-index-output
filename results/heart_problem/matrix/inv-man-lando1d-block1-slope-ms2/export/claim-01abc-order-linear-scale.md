# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-slope-ms2/export/claim-01abc-order-linear-scale.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml --kind line --x radius_pct --y test_forward_linear_error_median,test_forward_quadratic_error_median,active_test_mae --rank-order lower --select best --aggregate median --output-name claim-01abc-order-linear-scale.png --intent 'Claim 1: linear/Born forward error, quadratic MAN forward error, and inverse active-parameter error on one linear-scale plot.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 1: linear/Born forward error, quadratic MAN forward error, and inverse active-parameter error on one linear-scale plot.`
