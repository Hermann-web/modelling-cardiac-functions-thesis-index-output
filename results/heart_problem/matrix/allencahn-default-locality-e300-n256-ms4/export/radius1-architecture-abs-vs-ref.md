# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/allencahn-default-locality-e300-n256-ms4/export/radius1-architecture-abs-vs-ref.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/allencahn-default-active-D-r.yaml --kind bar --x model --y active_test_mae --hue formulation --rank-order lower --select best --filter radius_pct=1 --aggregate mean --output-name radius1-architecture-abs-vs-ref.png --dpi 200
```

## Details

- kind: `bar`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/allencahn-default-active-D-r.yaml`
- output_root_override: `None`
