# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a3-sample-efficiency-activation1d-e50-ms1/export/paper-a3-low-data-regime.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a3-sample-efficiency.yaml --kind line --x n_samples --y active_test_mae --hue model --group-row n_sensors --group-col observation_event_noise --rank-order lower --select best --aggregate mean --spread std --output-name paper-a3-low-data-regime.png --intent 'Paper figure: low-data regime. SNNPlus has the lowest mean MAE at low sample counts and ConvMultiPlus becomes lowest at high sample counts.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a3-sample-efficiency.yaml`
- output_root_override: `None`
- intent: `Paper figure: low-data regime. SNNPlus has the lowest mean MAE at low sample counts and ConvMultiPlus becomes lowest at high sample counts.`
