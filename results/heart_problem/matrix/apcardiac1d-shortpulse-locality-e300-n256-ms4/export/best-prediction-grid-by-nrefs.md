# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac1d-shortpulse-locality-e300-n256-ms4/export/best-prediction-grid-by-nrefs.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml --kind best_prediction_grid --select-group-by n_refs --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --aggregate mean --output-name best-prediction-grid-by-nrefs.png --dpi 200
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml`
- output_root_override: `None`
