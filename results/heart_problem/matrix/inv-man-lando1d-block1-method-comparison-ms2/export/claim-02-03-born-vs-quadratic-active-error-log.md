# Export Record

- png: `output/results/heart_problem/matrix/inv-man-lando1d-block1-method-comparison-ms2/export/claim-02-03-born-vs-quadratic-active-error-log.png`

## Equivalent CLI

```bash
uv run heartproblem matrix-plot docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml --kind line --x radius_pct --y active_test_mae --hue model --rank-order lower --select best --filter observation_noise=0 --filter inverse_regularization_lambda=0 --filter 'model!=full_nls' --filter 'model!=regularized_full_nls' --filter 'model!=regularized_quadratic' --filter 'model!=man_initialized_full_nls' --aggregate median --x-scale log --y-scale log --output-name claim-02-03-born-vs-quadratic-active-error-log.png --intent 'Claims 2 and 3: Born is too weak beyond small perturbations and explicit quadratic MAN captures nonlinear curvature missed by Born.' --dpi 200
```

## Details

- kind: `line`
- spec: `docs/views/2026-inv-man/codework/2026-06-30-lando1d-block1-method-comparison-ms2.yaml`
- output_root_override: `None`
- intent: `Claims 2 and 3: Born is too weak beyond small perturbations and explicit quadratic MAN captures nonlinear curvature missed by Born.`
