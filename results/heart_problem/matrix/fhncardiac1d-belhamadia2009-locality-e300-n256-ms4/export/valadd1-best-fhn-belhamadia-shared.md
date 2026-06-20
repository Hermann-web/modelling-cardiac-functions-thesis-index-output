# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac1d-belhamadia2009-locality-e300-n256-ms4/export/valadd1-best-fhn-belhamadia-shared.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-best-prediction-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-belhamadia2009-active-d-a-gamma.yaml --metric active_test_mae --filter model=convmultiplus --filter formulation=reference_delta --filter radius_pct=1 --filter n_refs=1 --rank-order lower --select best --output-name valadd1-best-fhn-belhamadia-shared.png --intent 'Shared cardiac value-add 1: best FHN Belhamadia2009 row showcase' --dpi 220
```

## Details

- metric: `active_test_mae`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-belhamadia2009-active-d-a-gamma.yaml`
- output_root_override: `None`
- rank_reduce_by: `None`
- rank_reduce_agg: `mean`
- rank_order: `lower`
- select: `best`
- intent: `Shared cardiac value-add 1: best FHN Belhamadia2009 row showcase`
