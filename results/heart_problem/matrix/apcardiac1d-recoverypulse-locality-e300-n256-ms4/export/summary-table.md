# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac1d-recoverypulse-locality-e300-n256-ms4/export/summary-table.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-recoverypulse-active-a-d-mu1.yaml --kind table --columns model,n_refs,radius_pct,active_test_mae,test_mae,data_loss,physics_loss,total_loss --rank-order lower --select best --aggregate none --output-name summary-table.png --dpi 200
```

## Details

- kind: `table`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-recoverypulse-active-a-d-mu1.yaml`
- output_root_override: `None`
