# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-event-h64-retest-activation1d-e100-n128-ms2/export/h64_event_retest_active_mae_by_seed.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-h64-retest-ms2.yaml --kind bar --x n_sensors --y active_test_mae --hue model --group-col seed --rank-order lower --select best --aggregate mean --output-name h64_event_retest_active_mae_by_seed.png --intent 'SNN/Eikonal H64 retest: clean event-trace pairwise comparison across seeds 1235 and 1236.' --dpi 200
```

## Details

- kind: `bar`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-phase3/activation1d-event-h64-retest-ms2.yaml`
- output_root_override: `None`
- intent: `SNN/Eikonal H64 retest: clean event-trace pairwise comparison across seeds 1235 and 1236.`
