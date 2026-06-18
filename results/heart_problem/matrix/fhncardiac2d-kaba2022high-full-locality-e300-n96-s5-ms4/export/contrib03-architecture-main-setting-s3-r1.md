# Export Record

- png: `/home/ahlk/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac2d-kaba2022high-full-locality-e300-n96-s5-ms4/export/contrib03-architecture-main-setting-s3-r1.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml --kind bar --x model --y active_test_mae --hue formulation --rank-order lower --select best --filter n_sensors=3 --filter radius_pct=1 --filter noise=0 --aggregate mean --spread std --output-name contrib03-architecture-main-setting-s3-r1.png --intent 'Contribution 03: architecture matters less than formulation, but convmulti is the best reference-delta choice at the main setting. At sensors=3 and radius=1, compare active-only a,d,gamma MAE across models and formulations.' --dpi 220
```

## Details

- kind: `bar`
- spec: `docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml`
- output_root_override: `None`
- intent: `Contribution 03: architecture matters less than formulation, but convmulti is the best reference-delta choice at the main setting. At sensors=3 and radius=1, compare active-only a,d,gamma MAE across models and formulations.`
