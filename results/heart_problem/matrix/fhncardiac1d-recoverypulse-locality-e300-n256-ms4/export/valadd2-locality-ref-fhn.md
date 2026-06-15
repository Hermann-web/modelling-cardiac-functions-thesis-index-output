# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/fhncardiac1d-recoverypulse-locality-e300-n256-ms4/export/valadd2-locality-ref-fhn.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot /home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml --kind line --x radius_pct --y active_test_mae --rank-order lower --select best --filter formulation=absolute --aggregate mean --spread q10q90 --output-name valadd2-locality-ref-fhn.png --intent 'Shared cardiac value-add 2: locality trend under absolute on FHN RecoveryPulse' --dpi 220
```

## Details

- kind: `line`
- spec: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/docs/views/2026-journal/matrixes/cardiac-shared-locality-ms4/fhncardiac1d-recoverypulse-active-d-a-gamma.yaml`
- output_root_override: `None`
- intent: `Shared cardiac value-add 2: locality trend under absolute on FHN RecoveryPulse`
