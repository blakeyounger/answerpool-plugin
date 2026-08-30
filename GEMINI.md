# CortexAssay tools

Computed intelligence from rights-reviewed open data (SEC EDGAR, Federal Register, USAspending,
NIH RePORTER, OpenAlex). Outputs are analytical signals with provenance — not investment or
legal advice.

- `technology_lookup` is free (no key). Use it first to screen a research field.
- `sec_events`, `sec_company`, `reg_rules`, `funding_signals`, `technology_emerging`,
  `technology_momentum` are paid per call ($0.005–$0.05) and need a credit key in
  `CORTEXASSAY_API_KEY`. Without one they return a 401 with purchase instructions
  (credits from $1 at https://cortexassay.com/v1/credits/checkout).
- Failed calls are never charged. Docs: https://cortexassay.com/llms.txt
