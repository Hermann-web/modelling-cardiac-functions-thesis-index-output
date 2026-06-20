# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac1d-belhamadia2009-locality-e300-n256-ms4/export/valadd1-solution-fhn-belhamadia-shared.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-visu /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-belhamadia2009-active-d-a-gamma.yaml --kind component_quantile_stack --rank-by active_test_mae --filter model=convmultiplus --filter formulation=reference_delta --filter radius_pct=1 --filter n_refs=1 --rank-order lower --select best --component-name u --param-name a --quantiles 0.05,0.5,0.95 --output-name valadd1-solution-fhn-belhamadia-shared.png --intent 'Shared cardiac value-add 1: FHN Belhamadia2009 solution-side quantile stack for the best reference-delta row' --dpi 220
```

## Details

- kind: `component_quantile_stack`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-belhamadia2009-active-d-a-gamma.yaml`
- output_root_override: `None`
- rank_by: `active_test_mae`
- select_group_by: `None`
- rank_reduce_by: `None`
- rank_reduce_agg: `mean`
- rank_order: `lower`
- select: `best`
- component_name: `u`
- param_name: `a`
- quantiles: `(0.05, 0.5, 0.95)`
- intent: `Shared cardiac value-add 1: FHN Belhamadia2009 solution-side quantile stack for the best reference-delta row`
