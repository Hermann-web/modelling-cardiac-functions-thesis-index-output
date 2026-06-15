# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-diagnostics-activation1d-e100-n128-ms1/export/diagnostic_active_mae_by_obs_mode_sensor_hidden.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-diagnostics-ms1.yaml --kind bar --x observation_mode --y active_test_mae --hue model --group-row n_sensors --group-col hidden_dim --rank-order lower --select best --aggregate mean --output-name diagnostic_active_mae_by_obs_mode_sensor_hidden.png --intent 'SNN/Eikonal diagnostic: compare ConvMultiPlus and SNNPlus across activation samples, threshold times, and event traces at hidden widths 20 and 64.' --dpi 200
```

## Details

- kind: `bar`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-diagnostics-ms1.yaml`
- output_root_override: `None`
- intent: `SNN/Eikonal diagnostic: compare ConvMultiPlus and SNNPlus across activation samples, threshold times, and event traces at hidden widths 20 and 64.`
