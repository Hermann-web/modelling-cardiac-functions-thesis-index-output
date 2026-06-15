# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a2-perturbation-specificity-activation1d-e50-n128-ms1/export/paper-a2-specificity-control.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a2-perturbation-specificity.yaml --kind line --x observation_event_noise --y active_test_mae --hue model --group-row observation_event_noise_mode --group-col n_sensors --rank-order lower --select best --aggregate mean --spread std --output-name paper-a2-specificity-control.png --intent 'Paper figure: specificity control. SNNPlus does not generalize across jitter, dropout, and false-event perturbations.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a2-perturbation-specificity.yaml`
- output_root_override: `None`
- intent: `Paper figure: specificity control. SNNPlus does not generalize across jitter, dropout, and false-event perturbations.`
