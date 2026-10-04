## Veer Arora

Data and backend engineer, Bengaluru. I build systems that can tell you when
they are wrong: evaluation harnesses, reconciliation gates, measured baselines
instead of plausible-looking output.

Portfolio: **[veer0608.github.io](https://veer0608.github.io)** · Résumé: **[PDF](https://veer0608.github.io/Veer_Arora_Resume.pdf)** · veerarora06@gmail.com

Open to data, backend, and AI-engineering roles. Bengaluru or relocating.

### Selected work

| | |
|---|---|
| **[bhavcopy-pipeline](https://github.com/veer0608/bhavcopy-pipeline)** | Daily NSE and BSE end-of-day price pipeline with no LLM in it: Python ingestion, DuckDB, dbt models and tests, GitHub Actions, and a static dashboard live on [GitHub Pages](https://veer0608.github.io/bhavcopy-pipeline/). |
| **[syncline](https://github.com/veer0608/syncline)** | Incremental GitHub API connector into DuckDB, scheduled with Dagster. Each page commits with its checkpoint, so a crash loses nothing. The first live run said "ok" and had skipped 7,553 rows, because GitHub's updated_at does not always follow its own sort order; after the fix a full sync matches GitHub's own count exactly (22,425 rows). |
| **[agentops](https://github.com/veer0608/agentops)** | Support agent that takes gated actions behind a policy and escalation gate, with a provider-agnostic LLM seam and a built-in eval harness for tool selection, grounding, cost and latency. |
| **[citerag](https://github.com/veer0608/citerag)** | Cite-everything RAG over messy 10-K PDFs with a golden-set eval harness. recall@5 0.37 to 0.767 against a measured 0.85 ceiling. The wins came from fixing PDF text extraction, not clever retrieval. |
| **[vidsmith](https://github.com/veer0608/vidsmith)** | Turns a script into a narrated, captioned video. Uses edge-tts word-boundary timing for exact captions instead of running Whisper after the fact. Deployed and running at vidsmith.duckdns.org. |
| **[moneytrail](https://github.com/veer0608/moneytrail)** | Local-first bank-statement ledger that provably balances. Reconciliation is the first component, not categorisation. If the parse dropped a row, every insight built on it is quietly wrong. |
| **[reruns](https://github.com/veer0608/reruns)** | Benchmark for multi-turn support agents, scored on pass^k rather than a single pass or fail: pass@1 0.78, pass^5 0.70. 192 tests. The first measurement run was thrown out on purpose for being unreliable; daily runs since. |
| **[schemablind](https://github.com/veer0608/schemablind)** | A SQL agent given no schema: four verbs, a database it has never seen, a question. Scored on BIRD execution accuracy, the agent's rows against the reference query's, no judge model. Harness proven (oracle 100%, mute 0%). Dev half measured at 64.7% on 266 questions; not a held-out score. |

Previously: tested **Nostradamus** at L&T Finance, an MLOps platform running eight
models across EWS, Banking, Self-Cure and Collections. Pipeline validation, SQL
verification and UAT on GCP and Kubeflow.

### Working with

Python · SQL · DuckDB · dbt · Dagster · FastAPI · PostgreSQL · pandas · LangGraph · pytest · TypeScript · React
