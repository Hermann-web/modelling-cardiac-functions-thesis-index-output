# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-slope-ms2/export/claim-01a-linear-forward-order.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml --kind line --x radius_pct --y test_forward_linear_error_median --rank-order lower --select best --aggregate median --x-scale log --y-scale log --output-name claim-01a-linear-forward-order.png --intent 'Claim 1a: linear/Born forward approximation error scales near O(epsilon^2).' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 1a: linear/Born forward approximation error scales near O(epsilon^2).`
