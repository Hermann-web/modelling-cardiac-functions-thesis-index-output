# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-phase3-activation1d-e100-n128-ms3/export/active_mae_by_sensor_mode_noise.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-axis-ms3.yaml --kind line --x n_sensors --y active_test_mae --hue model --group-row observation_mode --group-col observation_noise --rank-order lower --select best --aggregate mean --spread std --output-name active_mae_by_sensor_mode_noise.png --intent 'Activation1D event-axis SNN comparison: active MAE versus number of observation sensors, faceted by observation mode and observation noise.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-axis-ms3.yaml`
- output_root_override: `None`
- intent: `Activation1D event-axis SNN comparison: active MAE versus number of observation sensors, faceted by observation mode and observation noise.`
