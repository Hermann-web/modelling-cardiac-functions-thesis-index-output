# Export Record

- png: `/home/ahlk/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/apcardiac2d-kaba2025numerical-full-locality-e300-n96-s5-ms4/export/contrib02-paper-best-recovery-convmulti-s3-r1.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-best-prediction-plot docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/apcardiac2d-kaba2025numerical-active-a-d-mu1.yaml --metric active_test_mae --filter model=convmulti --filter formulation=reference_delta --filter n_refs=1 --filter n_sensors=3 --filter radius_pct=1 --filter noise=0 --rank-order lower --select best --output-name contrib02-paper-best-recovery-convmulti-s3-r1.png --intent 'Contribution 02: paper-level 2D cardiac FHN recovery. Best convmulti reference-delta run at sensors=3 and radius=1, ranked by active-only a,d,gamma MAE; the figure should show diagonal agreement for all active parameters and expose d as the hardest parameter.' --dpi 220
```

## Details

- metric: `active_test_mae`
- spec: `docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/apcardiac2d-kaba2025numerical-active-a-d-mu1.yaml`
- output_root_override: `None`
- rank_reduce_by: `None`
- rank_reduce_agg: `mean`
- rank_order: `lower`
- select: `best`
- intent: `Contribution 02: paper-level 2D cardiac FHN recovery. Best convmulti reference-delta run at sensors=3 and radius=1, ranked by active-only a,d,gamma MAE; the figure should show diagonal agreement for all active parameters and expose d as the hardest parameter.`
