# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-phase3-activation1d-e100-n128-ms3/export/observation_activity_by_sensor_noise.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-axis-ms3.yaml --kind line --x n_sensors --y test_observation_active_fraction --hue observation_noise --group-row observation_mode --rank-order lower --select best --aggregate mean --output-name observation_activity_by_sensor_noise.png --intent 'Activation1D observation activity: event-trace sparsity is preserved only before additive observation noise; noisy event traces become numerically dense under nonzero-threshold activity counting.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-axis-ms3.yaml`
- output_root_override: `None`
- intent: `Activation1D observation activity: event-trace sparsity is preserved only before additive observation noise; noisy event traces become numerically dense under nonzero-threshold activity counting.`
