## Stefan Sîrbu

Computer Science student at **Politehnica University of Timișoara** (graduating 2028), currently
**System Test Engineer Intern** at Aumovio Technologies Romania on an NFC digital car key platform —
and building AI agents for the test-architecture team outside my assigned scope.

What I care about: making autonomous systems **inspectable**. An agent that claims it followed the
rules is not evidence. A run ledger, a regression benchmark and a fail-closed approval gate are.

### What I'm building

**[Kage](https://github.com/st3fansrb/kage.ai)** — a self-hosted Python platform that orchestrates,
governs and evaluates AI workflows.

- FastAPI over **PostgreSQL 16** for shared state and telemetry, migrated off lock files and SQLite
  with an idempotent cutover that verifies row counts in-transaction and rolls back on mismatch
- **raw → staging → mart** ETL pipeline in SQL, with point-in-time lineage and a snapshot ID per run
- **Airflow** DAGs for batch work — while fail-closed near-real-time jobs deliberately stay in-process
- **Risk gates**: policy-based approvals, workspace confinement with path canonicalisation, budget caps
- **KageBench**: a fixed-task regression gate, so capability changes get measured rather than asserted
- 576 tests, CI on every push

**[iTECify](https://github.com/st3fansrb/iTECify)** — collaborative web IDE with an integrated AI
coding agent. Tech lead; 7th of 30 teams at iTEC 2026. PostgreSQL data model, real-time sync layer,
Docker-isolated user code execution.

**[forex-research](https://github.com/st3fansrb/forex-research)** — quantitative trading research
(paper-only, no real capital): event-driven backtesting with no look-ahead, walk-forward and
out-of-sample validation, and a bias toward reporting negative results as negative. The code is
public; the trader's logs it was calibrated against, and the reports derived from them, are not.

### Working with

`Python` · `SQL` · `PostgreSQL` · `FastAPI` · `Airflow` · `Docker` · `ChromaDB` · `pandas` · `C` · `TypeScript`

Currently learning: Kafka, Kubernetes, GCP.

### Elsewhere

[LinkedIn](https://linkedin.com/in/stefan-andrei-sirbu) · `stefan.andrei.sirbu@gmail.com`
