# Export Record

- png: `/home/ahlk/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac2d-kaba2025numerical-full-locality-e300-n96-s5-ms4/export/contrib01-reference-mechanism-grid-s3-r1.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/apcardiac2d-kaba2025numerical-active-a-d-mu1.yaml --kind best_prediction_grid --select-group-by n_refs --rank-by active_test_mae --rank-reduce-by seed --rank-reduce-agg mean --rank-order lower --select best --filter n_sensors=3 --filter radius_pct=1 --filter noise=0 --aggregate mean --output-name contrib01-reference-mechanism-grid-s3-r1.png --intent 'Contribution 01: the reference library is the decisive mechanism. At sensors=3 and radius=1, compare the best n_refs=0 absolute row against the best n_refs=1 reference-delta row; the intended read is failure/scatter without references and near-diagonal recovery with one reference.' --dpi 220
```

## Details

- kind: `best_prediction_grid`
- spec: `docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/apcardiac2d-kaba2025numerical-active-a-d-mu1.yaml`
- output_root_override: `None`
- intent: `Contribution 01: the reference library is the decisive mechanism. At sensors=3 and radius=1, compare the best n_refs=0 absolute row against the best n_refs=1 reference-delta row; the intended read is failure/scatter without references and near-diagonal recovery with one reference.`
