# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-event-jitter-confirm-activation1d-e20-n64-ms1/export/jitter_confirm_active_mae_by_level_sensor.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-jitter-confirm-ms1.yaml --kind line --x observation_event_noise --y active_test_mae --hue model --group-col n_sensors --rank-order lower --select best --aggregate mean --spread std --output-name jitter_confirm_active_mae_by_level_sensor.png --intent 'Mean active MAE under event-time jitter for ConvMultiPlus and SNNPlus, grouped by sensor count; confirms SNNPlus has a small, seed-dependent jitter robustness niche rather than a broad dominance claim.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-jitter-confirm-ms1.yaml`
- output_root_override: `None`
- intent: `Mean active MAE under event-time jitter for ConvMultiPlus and SNNPlus, grouped by sensor count; confirms SNNPlus has a small, seed-dependent jitter robustness niche rather than a broad dominance claim.`
