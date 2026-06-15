# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a5-confirmatory-lowdata-lowbudget-activation1d-ms1/export/paper-a5-jitter-flip-sensors-8-12.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a5-confirmatory-lowdata-lowbudget.yaml --kind line --x observation_event_noise --y active_test_mae --hue model --group-row n_sensors --rank-order lower --select best --filter 'n_sensors>4' --filter n_samples=32 --filter epochs=50 --aggregate mean --spread std --output-name paper-a5-jitter-flip-sensors-8-12.png --intent 'Paper figure: A5 jitter sensitivity at 32 samples and 50 epochs for sensors 8 and 12. ConvMultiPlus has the lowest mean MAE at zero jitter, while SNNPlus has the lowest mean MAE after timestamp jitter is introduced.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a5-confirmatory-lowdata-lowbudget.yaml`
- output_root_override: `None`
- intent: `Paper figure: A5 jitter sensitivity at 32 samples and 50 epochs for sensors 8 and 12. ConvMultiPlus has the lowest mean MAE at zero jitter, while SNNPlus has the lowest mean MAE after timestamp jitter is introduced.`
