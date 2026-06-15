# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a4-training-budget-efficiency-activation1d-ms1/export/paper-a4-low-budget-regime.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a4-training-budget-efficiency.yaml --kind line --x epochs --y active_test_mae --hue model --group-row n_sensors --group-col observation_event_noise --rank-order lower --select best --aggregate mean --spread std --output-name paper-a4-low-budget-regime.png --intent 'Paper figure: low-budget regime. SNNPlus has the lowest mean MAE under timestamp jitter when the epoch budget is limited.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a4-training-budget-efficiency.yaml`
- output_root_override: `None`
- intent: `Paper figure: low-budget regime. SNNPlus has the lowest mean MAE under timestamp jitter when the epoch budget is limited.`
