# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fisherkpp-locality-default-e100-n128-strong-ms2/export/valadd1-best-grid-fisherkpp.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/fisherkpp-default-active-d-r.yaml --kind best_prediction_grid --metrics active_test_mae --select-group-by formulation --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --aggregate mean --output-name valadd1-best-grid-fisherkpp.png --intent 'fisherkpp: grouped best prediction grid by formulation' --dpi 200
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/fisherkpp-default-active-d-r.yaml`
- output_root_override: `None`
- intent: `fisherkpp: grouped best prediction grid by formulation`
