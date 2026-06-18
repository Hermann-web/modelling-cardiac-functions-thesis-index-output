# Export Record

- png: `/home/ahlk/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac2d-kaba2022high-full-locality-e300-n96-s5-ms4/export/annex05-sensors-not-main-story-convmulti.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml --kind line --x n_refs --y active_test_mae --hue n_sensors --style noise --group-col radius_pct --rank-order lower --select best --filter model=convmulti --aggregate mean --spread std --output-name annex05-sensors-not-main-story-convmulti.png --intent 'Annex observation 01: sensor count is a secondary effect, not a failure case. For convmulti, compare sensors=3 and sensors=5 across n_refs, clean/noisy observations, and both radii; the intended read is that five sensors are not harmful and help modestly under noise, while formulation remains the larger effect.' --dpi 220
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/cardiac2d-shared-locality-ms4/fhncardiac2d-kaba2022high-active-a-d-gamma.yaml`
- output_root_override: `None`
- intent: `Annex observation 01: sensor count is a secondary effect, not a failure case. For convmulti, compare sensors=3 and sensors=5 across n_refs, clean/noisy observations, and both radii; the intended read is that five sensors are not harmful and help modestly under noise, while formulation remains the larger effect.`
