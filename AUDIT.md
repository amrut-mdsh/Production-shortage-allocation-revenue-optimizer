# Local audit — Production-Shortage-Allocation---Revenue-at-Risk-Optimizer-main

## Changes

Made notebook setup portable, pinned compatible PuLP, documented Jinja2, removed unused dataclass imports and resume/interview promotion, cleared stale outputs and cleaned notebook UI metadata. Added optimizer input/status guards and fixed customer-risk aggregation with numeric tolerance. All 35 analytical code cells and four regression checks passed.

## Validation performed

- **PASS** — Production-Shortage-Allocation---Revenue-at-Risk-Optimizer-main/notebook/shortage_allocation_revenue_risk_optimizer.ipynb: Notebook schema and every code-cell syntax
- **PASS** — All 35 code cells executed sequentially in a temporary Python 3.12 audit environment; Plotly `show()` was intercepted to validate figure JSON without opening browsers. Display tables were computed but not visually rendered.
- **PASS** — missing SKU, duplicate order, customer aggregate and solver tolerance, genuine customer shortfall.
- Exact environment used: Python 3.12; NumPy 2.5.5; pandas 3.1.1; Plotly 7.1.0; PuLP 3.3.0; Jinja2 3.1.6. CBC was available and the solver smoke test passed.
- Synthetic base-case balanced protected margin: $2,456,516.92; fill rate: 84.214811%. These are simulation outputs, not achieved business results.
- Archive members and XML were parsed where present; images decoded and screenshots reviewed. Notebook/JSON syntax and local paths were checked.
- No plaintext secret candidates, personal contact emails, promotional GitHub/LinkedIn profile links or machine-home paths were detected in the final scanned text/package content. This is a bounded local pattern scan, not proof that opaque native models contain no sensitive data.

## Remaining limitations

Models use synthetic inputs and a mixture of integer and continuous allocation policies. Continuous results are not directly dispatchable discrete-unit plans. OTIF/perfect-order metrics are modeled fill-rate proxies; Monte Carlo uses interpolated responses. Browser rendering of every generated Plotly chart was not tested; original screenshots remain historical examples. Native business integration and commercial impact are not claimed.

## Provenance and execution scope

Original source datasets and SQL are retained. No Git history was present in the five extracted folders. Original Downloads folders match their pre-copy SHA-256 hashes. No GitHub command, authentication, repository creation, commit, push or upload was performed.

Original authorship and legally required notices remain in [ATTRIBUTION.md](ATTRIBUTION.md). Personal UI redactions do not replace author attribution.
