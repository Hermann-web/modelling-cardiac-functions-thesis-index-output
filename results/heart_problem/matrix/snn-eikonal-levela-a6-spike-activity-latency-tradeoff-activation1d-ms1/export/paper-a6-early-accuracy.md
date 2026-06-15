# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a6-spike-activity-latency-tradeoff-activation1d-ms1/export/paper-a6-early-accuracy.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a6-spike-activity-latency-tradeoff.yaml --kind line --x epochs --y early_active_test_mae_25 --hue model --group-row n_sensors --group-col observation_event_noise --rank-order lower --select best --filter n_samples=32 --aggregate mean --spread std --output-name paper-a6-early-accuracy.png --intent 'Paper figure: early-window accuracy proxy. SNNPlus keeps the lowest mean MAE pattern when evaluation is restricted to the early time window.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a6-spike-activity-latency-tradeoff.yaml`
- output_root_override: `None`
- intent: `Paper figure: early-window accuracy proxy. SNNPlus keeps the lowest mean MAE pattern when evaluation is restricted to the early time window.`
