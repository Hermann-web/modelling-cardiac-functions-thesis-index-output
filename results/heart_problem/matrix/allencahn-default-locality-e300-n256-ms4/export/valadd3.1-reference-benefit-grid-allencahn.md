# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/allencahn-default-locality-e300-n256-ms4/export/valadd3.1-reference-benefit-grid-allencahn.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/allencahn-default-active-D-r.yaml --kind best_prediction_grid --metrics active_test_mae,test_mae --select-group-by radius_pct --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --filter formulation=reference_delta --aggregate mean --output-name valadd3.1-reference-benefit-grid-allencahn.png --intent 'Shared cardiac value-add 3: best-prediction grid grouped by radius on Allen-Cahn for reference-delta formulation' --dpi 220
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/allencahn-default-active-D-r.yaml`
- output_root_override: `None`
- intent: `Shared cardiac value-add 3: best-prediction grid grouped by radius on Allen-Cahn for reference-delta formulation`
