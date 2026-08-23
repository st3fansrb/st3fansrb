<div align="center">

# Stefan Sîrbu

**I build autonomous systems and then try to make them inspectable.**

![Location](https://img.shields.io/badge/Timișoara-Romania-C1272D?style=for-the-badge)
![University](https://img.shields.io/badge/Politehnica%20Timișoara-CS%20'28-004A8F?style=for-the-badge)
![Role](https://img.shields.io/badge/System%20Test%20Engineer%20Intern-Aumovio-1B1F23?style=for-the-badge)

</div>

---

Computer Science student at **Politehnica University of Timișoara** (graduating 2028), currently
**System Test Engineer Intern** at Aumovio Technologies Romania on an NFC digital car key platform —
and building AI agents for the test-architecture team outside my assigned scope.

What I care about: making autonomous systems **inspectable**. An agent that claims it followed the
rules is not evidence. A run ledger, a regression benchmark and a fail-closed approval gate are.

---

## What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🥷 [Kage](https://github.com/st3fansrb/kage.ai)

A self-hosted Python platform that orchestrates, governs and evaluates AI workflows.

- FastAPI over **PostgreSQL 16** for shared state and telemetry, migrated off lock files and SQLite
  with an idempotent cutover that verifies row counts in-transaction and rolls back on mismatch
- **raw → staging → mart** ETL in SQL, with point-in-time lineage and a snapshot ID per run
- **Airflow** DAGs for batch work — while fail-closed near-real-time jobs deliberately stay in-process
- **Risk gates**: policy-based approvals, workspace confinement, budget caps
- **KageBench**: a fixed-task regression gate, so capability changes get measured rather than asserted

`576 tests` · `CI on every push` · [OWASP LLM Top 10 mapping](https://github.com/st3fansrb/kage.ai/blob/dev/docs/SECURITY-LLM-TOP10.md) · [Sentinel detection lab](https://github.com/st3fansrb/kage.ai/tree/dev/docs/lab-azure-sentinel)

</td>
<td width="50%" valign="top">

### 💻 [iTECify](https://github.com/st3fansrb/iTECify)

Collaborative web IDE with an integrated AI coding agent. **Tech lead; 7th of 30 teams at iTEC 2026.**

Real-time editing over Supabase Realtime, PostgreSQL data model, Docker-isolated execution
of user code, and a static security scanner that grades submitted code before it ever reaches
the sandbox.

### 📈 [forex-research](https://github.com/st3fansrb/forex-research)

Quantitative trading research — paper-only, no real capital.

Event-driven backtesting with no look-ahead, walk-forward and out-of-sample validation, and a
bias toward reporting negative results as negative. The code is public; the trader's logs it was
calibrated against, and the reports derived from them, are not.

### 🧊 [Frigo](https://github.com/st3fansrb/HackTM)

Flutter pantry-tracking app built for HackTM 2026 — barcode and OCR product resolution,
locally computed Nutri-Score, LLM meal planning from what you already have.

</td>
</tr>
</table>

---

## Working with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-1A1A1A?style=for-the-badge)

**Backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

**AI & agents**

![Anthropic](https://img.shields.io/badge/Claude%20Agent%20SDK-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge)
![LiteLLM](https://img.shields.io/badge/LiteLLM-6E56CF?style=for-the-badge)

**Security & cloud**

![Azure](https://img.shields.io/badge/Azure%20Monitor-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE%20ATT%26CK-C41E3A?style=for-the-badge)
![OWASP](https://img.shields.io/badge/OWASP%20LLM%20Top%2010-8A2BE2?style=for-the-badge&logo=owasp&logoColor=white)

**Currently learning:** Kafka · Kubernetes · GCP

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/stefan-andrei-sirbu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stefan.andrei.sirbu@gmail.com)

</div>
