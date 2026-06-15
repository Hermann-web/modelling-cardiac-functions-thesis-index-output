# Export Record

- png: `/home/ubuntu/Github/thesis/modelling-cardiac-functions-thesis-index/output/results/heart_problem/matrix/snn-eikonal-levela-a6-spike-activity-latency-tradeoff-activation1d-ms1/export/paper-a6-spike-cost.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a6-spike-activity-latency-tradeoff.yaml --kind bar --x model --y test_model_spike_count_per_sample --group-row n_sensors --group-col observation_event_noise --rank-order lower --select best --filter n_samples=32 --filter epochs=50 --aggregate mean --spread std --output-name paper-a6-spike-cost.png --intent 'Paper figure: spike-cost tradeoff. SNNPlus improves accuracy but does not reduce internal spike count relative to plain SNN.' --dpi 200
```

## Details

- kind: `bar`
- spec: `docs/views/2026-journal/matrixes/snn-eikonal-levelA-paper/a6-spike-activity-latency-tradeoff.yaml`
- output_root_override: `None`
- intent: `Paper figure: spike-cost tradeoff. SNNPlus improves accuracy but does not reduce internal spike count relative to plain SNN.`
