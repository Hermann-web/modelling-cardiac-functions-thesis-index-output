# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-event-jitter-stress-activation1d-e50-n128-ms1/export/jitter_stress_active_mae_by_level_sensor.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-jitter-stress-ms1.yaml --kind line --x observation_event_noise --y active_test_mae --hue model --group-col n_sensors --rank-order lower --select best --aggregate mean --spread std --output-name jitter_stress_active_mae_by_level_sensor.png --intent 'Stress test of active MAE under increasing temporal event jitter for ConvMultiPlus, SNN, and SNNPlus, grouped by sensor count.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-jitter-stress-ms1.yaml`
- output_root_override: `None`
- intent: `Stress test of active MAE under increasing temporal event jitter for ConvMultiPlus, SNN, and SNNPlus, grouped by sensor count.`
