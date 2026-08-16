## Veer Arora

Backend and data engineer, Bengaluru. I build systems that can tell you when
they are wrong — evaluation harnesses, reconciliation gates, measured baselines
rather than plausible-looking output.

Portfolio: **[veer0608.github.io](https://veer0608.github.io)** · Résumé: **[PDF](https://veer0608.github.io/Veer_Arora_Resume.pdf)** · veerarora06@gmail.com

Open to backend, data, and AI-engineering roles — Bengaluru or relocating.

### Selected work

| | |
|---|---|
| **[schemablind](https://github.com/veer0608/schemablind)** | A SQL agent given no schema — four verbs, a database it has never seen, and a question. Scored on BIRD execution accuracy: the agent's rows against the reference query's, no judge model. The harness proves itself first (oracle 100%, mute 0%). No complete model run yet. |
| **[citerag](https://github.com/veer0608/citerag)** | Cite-everything RAG over messy 10-K PDFs with a golden-set eval harness. recall@5 0.37 → 0.77 against a measured 0.85 ceiling. The wins came from fixing PDF text extraction, not from clever retrieval. |
| **[moneytrail](https://github.com/veer0608/moneytrail)** | Local-first bank-statement ledger that provably balances. Reconciliation is the first component, not categorisation — if the parse dropped a row, every insight built on it is quietly wrong. |
| **[agencydesk](https://github.com/veer0608/agencydesk)** | Multi-tenant project management where tenant isolation is enforced by PostgreSQL row-level security, not application code. React + FastAPI + Postgres 16. |
| **[agentops](https://github.com/veer0608/agentops)** | Support agent that takes gated actions behind a policy/escalation gate, with a provider-agnostic LLM seam and a built-in eval harness for tool selection, grounding, cost and latency. |

Previously: tested **Nostradamus** at L&T Finance, an MLOps platform running eight
models across EWS, Banking, Self-Cure and Collections — pipeline validation, SQL
verification and UAT on GCP and Kubeflow.

### Working with

Python · FastAPI · PostgreSQL · pandas · LangGraph · pytest · TypeScript · React
