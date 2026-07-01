# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2/export/claim-05-time-accuracy-ladder-log.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml --kind scatter --x training_time_seconds --y active_test_mae --hue model --group-col radius_pct --rank-order lower --select best --filter observation_noise=0 --filter inverse_regularization_lambda=0 --filter 'model!=regularized_quadratic' --filter 'model!=regularized_full_nls' --aggregate median --x-scale log --y-scale log --output-name claim-05-time-accuracy-ladder-log.png --intent 'Claim 5: on clean data, Born, explicit quadratic MAN, MAN-initialized full NLS, and full NLS form a speed-accuracy ladder.' --dpi 200
```

## Details

- kind: `scatter`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- output_root_override: `None`
- intent: `Claim 5: on clean data, Born, explicit quadratic MAN, MAN-initialized full NLS, and full NLS form a speed-accuracy ladder.`
