# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac1d-recoverypulse-locality-e300-n256-ms4/export/valadd3-reference-benefit-grid-fhn.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml --kind best_prediction_grid --metrics active_test_mae,test_mae --select-group-by formulation --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --filter radius_pct=1 --aggregate mean --output-name valadd3-reference-benefit-grid-fhn.png --intent 'Shared cardiac value-add 3: best-prediction grid grouped by formulation on FHN RecoveryPulse at radius 1' --dpi 220
```

## Details

- kind: `best_prediction_grid`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml`
- output_root_override: `None`
- intent: `Shared cardiac value-add 3: best-prediction grid grouped by formulation on FHN RecoveryPulse at radius 1`
