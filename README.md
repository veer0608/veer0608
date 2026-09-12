## Veer Arora

Backend and data engineer, Bengaluru. I build systems that can tell you when
they are wrong: evaluation harnesses, reconciliation gates, measured baselines
instead of plausible-looking output.

Portfolio: **[veer0608.github.io](https://veer0608.github.io)** · Résumé: **[PDF](https://veer0608.github.io/Veer_Arora_Resume.pdf)** · veerarora06@gmail.com

Open to backend, data, and AI-engineering roles. Bengaluru or relocating.

### Selected work

| | |
|---|---|
| **[agentops](https://github.com/veer0608/agentops)** | Support agent that takes gated actions behind a policy and escalation gate, with a provider-agnostic LLM seam and a built-in eval harness for tool selection, grounding, cost and latency. |
| **[citerag](https://github.com/veer0608/citerag)** | Cite-everything RAG over messy 10-K PDFs with a golden-set eval harness. recall@5 0.37 to 0.767 against a measured 0.85 ceiling. The wins came from fixing PDF text extraction, not clever retrieval. |
| **[vidsmith](https://github.com/veer0608/vidsmith)** | Turns a script into a narrated, captioned video. Uses edge-tts word-boundary timing for exact captions instead of running Whisper after the fact. Deployed and running at vidsmith.duckdns.org. |
| **[moneytrail](https://github.com/veer0608/moneytrail)** | Local-first bank-statement ledger that provably balances. Reconciliation is the first component, not categorisation. If the parse dropped a row, every insight built on it is quietly wrong. |
| **[reruns](https://github.com/veer0608/reruns)** | Benchmark for multi-turn support agents, scored on pass^k rather than a single pass or fail. 110 tests. The first measurement run was thrown out on purpose for being unreliable; daily runs since. |
| **[schemablind](https://github.com/veer0608/schemablind)** | A SQL agent given no schema: four verbs, a database it has never seen, a question. Scored on BIRD execution accuracy, the agent's rows against the reference query's, no judge model. Harness proven (oracle 100%, mute 0%), full model run pending. |

Previously: tested **Nostradamus** at L&T Finance, an MLOps platform running eight
models across EWS, Banking, Self-Cure and Collections. Pipeline validation, SQL
verification and UAT on GCP and Kubeflow.

### Working with

Python · FastAPI · PostgreSQL · pandas · LangGraph · pytest · TypeScript · React
