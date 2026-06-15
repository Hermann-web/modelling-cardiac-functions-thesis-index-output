# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac1d-shortpulse-locality-e300-n256-ms4/export/valadd3-reference-benefit-grid-ap-shortpulse.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml --kind best_prediction_grid --metrics active_test_mae,test_mae --select-group-by formulation --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --filter radius_pct=1 --aggregate mean --output-name valadd3-reference-benefit-grid-ap-shortpulse.png --intent 'Shared cardiac value-add 3: best-prediction grid grouped by formulation on AP ShortPulse at radius 1' --dpi 220
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/apcardiac1d-shortpulse-active-a-d-mu1.yaml`
- output_root_override: `None`
- intent: `Shared cardiac value-add 3: best-prediction grid grouped by formulation on AP ShortPulse at radius 1`
