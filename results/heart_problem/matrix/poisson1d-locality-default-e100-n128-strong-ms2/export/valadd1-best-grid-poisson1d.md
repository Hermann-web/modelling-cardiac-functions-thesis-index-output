# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/poisson1d-locality-default-e100-n128-strong-ms2/export/valadd1-best-grid-poisson1d.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/poisson1d-default-active-p.yaml --kind best_prediction_grid --metrics active_test_mae --select-group-by formulation --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --aggregate mean --output-name valadd1-best-grid-poisson1d.png --intent 'poisson1d: grouped best prediction grid by formulation' --dpi 200
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/poisson1d-default-active-p.yaml`
- output_root_override: `None`
- intent: `poisson1d: grouped best prediction grid by formulation`
