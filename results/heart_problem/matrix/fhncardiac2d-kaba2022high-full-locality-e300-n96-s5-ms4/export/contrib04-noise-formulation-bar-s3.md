# Export Record

- png: `/home/ahlk/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac2d-kaba2022high-full-locality-e300-n96-s5-ms4/export/contrib04-noise-formulation-bar-s3.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml --kind bar --x noise --y active_test_mae --hue formulation --group-col model --rank-order lower --select best --filter n_sensors=3 --aggregate mean --spread std --output-name contrib04-noise-formulation-bar-s3.png --intent 'Contribution 04: mild observation noise does not reverse the formulation effect. At sensors=3, aggregate over radii and seeds and compare clean versus noise=0.01 active-only a,d,gamma MAE for absolute and reference-delta formulations in each model.' --dpi 220
```

## Details

- kind: `bar`
- spec: `docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml`
- output_root_override: `None`
- intent: `Contribution 04: mild observation noise does not reverse the formulation effect. At sensors=3, aggregate over radii and seeds and compare clean versus noise=0.01 active-only a,d,gamma MAE for absolute and reference-delta formulations in each model.`
