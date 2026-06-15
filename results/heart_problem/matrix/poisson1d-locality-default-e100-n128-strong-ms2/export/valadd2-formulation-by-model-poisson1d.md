# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/poisson1d-locality-default-e100-n128-strong-ms2/export/valadd2-formulation-by-model-poisson1d.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/poisson1d-default-active-p.yaml --kind bar --x model --y active_test_mae --hue formulation --group-col residual_form --rank-order lower --select best --aggregate mean --spread iqr --output-name valadd2-formulation-by-model-poisson1d.png --intent 'poisson1d: mean active test MAE by model and formulation, faceted by residual form' --dpi 200
```

## Details

- kind: `bar`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/beamer-shared-default-strong-ms2/poisson1d-default-active-p.yaml`
- output_root_override: `None`
- intent: `poisson1d: mean active test MAE by model and formulation, faceted by residual form`
