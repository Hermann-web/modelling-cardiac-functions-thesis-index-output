# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac1d-recoverypulse-locality-e300-n256-ms4/export/inut.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml --kind best_prediction_grid --select-group-by radius_pct --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --filter formulation=reference_delta --aggregate mean --output-name inut.png --dpi 200
```

## Details

- kind: `best_prediction_grid`
- spec: `docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml`
- output_root_override: `None`
