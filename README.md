# AnswerPool plugin (Claude Code / Cowork) and Gemini CLI extension

Adds the AnswerPool remote MCP server (https://answerpool.io/mcp) as native tools:
flagged SEC EDGAR events, one-call SEC company snapshots, Federal Register rule tracking with
deadline flags, US federal funding trajectories, and OpenAlex research-momentum scores.

- **Free tool:** `technology_lookup` (no key needed).
- **Paid tools:** $0.005–$0.05 per call, debited from a prepaid credit key; failed calls are
  never charged. Buy credits (from $1) at https://answerpool.io/v1/credits/checkout
  and paste the key when the plugin asks (Claude Code) or set `ANSWERPOOL_API_KEY` (Gemini CLI).

Data: SEC EDGAR, Federal Register, USAspending, NIH RePORTER (US federal public domain) and
OpenAlex (CC0). Outputs are analytical signals with provenance, not investment or legal advice.
Docs: https://answerpool.io/llms.txt · Terms: /terms · Privacy: /privacy

## Install

Claude Code: `/plugin install answerpool` (after directory approval) or add the marketplace
from this repo. Gemini CLI: `gemini extensions install https://github.com/blakeyounger/answerpool-plugin`.
