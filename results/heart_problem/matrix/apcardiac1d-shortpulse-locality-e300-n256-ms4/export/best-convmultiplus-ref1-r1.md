# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac1d-shortpulse-locality-e300-n256-ms4/export/best-convmultiplus-ref1-r1.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-best-prediction-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml --metric active_test_mae --filter model=convmultiplus --filter formulation=reference_delta --filter radius_pct=1 --rank-order lower --select best --output-name best-convmultiplus-ref1-r1.png --dpi 220
```

## Details

- metric: `active_test_mae`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml`
- output_root_override: `None`
- rank_reduce_by: `None`
- rank_reduce_agg: `mean`
- rank_order: `lower`
- select: `best`
