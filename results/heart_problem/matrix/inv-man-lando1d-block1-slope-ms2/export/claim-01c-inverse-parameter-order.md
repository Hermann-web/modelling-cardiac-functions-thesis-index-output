# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-slope-ms2/export/claim-01c-inverse-parameter-order.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml --kind line --x radius_pct --y active_test_mae --rank-order lower --select best --aggregate median --x-scale log --y-scale log --output-name claim-01c-inverse-parameter-order.png --intent 'Claim 1c: inverse active-parameter error scales near third order on clean scalar Lando1D.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-slope-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 1c: inverse active-parameter error scales near third order on clean scalar Lando1D.`
