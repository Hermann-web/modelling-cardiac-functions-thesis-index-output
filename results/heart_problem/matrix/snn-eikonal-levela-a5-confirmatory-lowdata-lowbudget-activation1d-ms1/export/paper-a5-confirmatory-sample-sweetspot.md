# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a5-confirmatory-lowdata-lowbudget-activation1d-ms1/export/paper-a5-confirmatory-sample-sweetspot.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a5-confirmatory-lowdata-lowbudget.yaml --kind line --x n_samples --y active_test_mae --hue model --group-row n_sensors --group-col observation_event_noise --rank-order lower --select best --filter epochs=50 --filter 'observation_event_noise>0' --aggregate mean --spread std --output-name paper-a5-confirmatory-sample-sweetspot.png --intent 'Paper figure: confirmatory sample sweep under nonzero jitter. SNNPlus has the lowest mean MAE in the moderate low-data region, especially 32 samples.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a5-confirmatory-lowdata-lowbudget.yaml`
- output_root_override: `None`
- intent: `Paper figure: confirmatory sample sweep under nonzero jitter. SNNPlus has the lowest mean MAE in the moderate low-data region, especially 32 samples.`
