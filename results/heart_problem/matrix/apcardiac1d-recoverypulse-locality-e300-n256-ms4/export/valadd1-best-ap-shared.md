# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac1d-recoverypulse-locality-e300-n256-ms4/export/valadd1-best-ap-shared.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-best-prediction-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-recoverypulse-active-a-d-mu1.yaml --metric active_test_mae --filter model=convmulti --filter formulation=reference_delta --filter radius_pct=1 --filter n_refs=1 --rank-order lower --select best --output-name valadd1-best-ap-shared.png --intent 'Shared cardiac value-add 1: best AP RecoveryPulse row showcase' --dpi 220
```

## Details

- metric: `active_test_mae`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-recoverypulse-active-a-d-mu1.yaml`
- output_root_override: `None`
- rank_reduce_by: `None`
- rank_reduce_agg: `mean`
- rank_order: `lower`
- select: `best`
- intent: `Shared cardiac value-add 1: best AP RecoveryPulse row showcase`
