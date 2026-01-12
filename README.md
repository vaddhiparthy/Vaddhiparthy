# Sri Surya S. Vaddhiparthy
Senior Data Engineer (Data Platform Architecture, FinOps, Reliability)

Website: https://surya.vaddhiparthy.com  
LinkedIn: https://linkedin.com/in/vaddhiparthy  
Email: surya@vaddhiparthy.com  

---

## Professional Summary
Senior Data Engineer (7+ years) building production-grade data platforms and ELT/ETL frameworks across batch and streaming workloads. I turn fragmented sources into governed, analytics-ready datasets with strong reliability (SLAs, monitoring, runbooks), cost discipline (warehouse + cloud FinOps), and clean delivery standards (IaC, CI/CD, reproducibility).  

Core stack: Snowflake, AWS, Airflow, dbt, Spark/PySpark, Python, SQL.

### Highlights
- Delivered Snowflake subject areas with dimensional modeling and dbt (models/tests/macros/docs), driving ~3× query performance and ~42% faster time-to-insight
- Orchestrated Python/SQL/dbt pipelines in Airflow (incrementals, backfills, reusable connectors), cutting batch latency ~45% while keeping runs auditable and maintainable
- Implemented data reliability and observability practices (automated validation + monitoring + runbooks), sustaining ~99.9% availability, reducing incident MTTR by ~35%, and lowering compute costs by ~20% via warehouse + SQL tuning

---

## What I Build
- Data platform architecture: Snowflake + dbt + Airflow ecosystems, curated marts/metrics, warehouse/query tuning, repeatable delivery patterns
- Reliability and governance: tests, SLAs, monitoring/lineage, incident runbooks, auditability/backfills, privacy-first ingestion and PII-safe transformations
- Engineering standards: CI/CD + IaC (Terraform), containerized jobs/services, reproducible environments, versioned datasets and definitions

---

## Technical Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| Data Platforms | Snowflake, AWS (S3, Glue, Lambda, ECS/Fargate), BigQuery |
| Orchestration & Transform | Airflow, dbt (Models/Macros/Tests/Docs) |
| Distributed Compute & Streaming | Spark, PySpark, Kafka |
| Engineering | Python, SQL, Docker, Git, CI/CD, Terraform |
| Quality & Observability | Great Expectations, data observability tooling, CloudWatch, SLAs, runbooks |

---

## Featured Engineering Systems (Selected)

### 1) Secure PII Event Ingestion Framework (SQS → Postgres)
Repo: https://github.com/vaddhiparthy/Login-Events-ETL  
Event-driven ingestion pipeline consuming authentication/login events via AWS SQS (LocalStack for reproducible local runs). Applies SHA-256 pseudonymization mid-flight and lands normalized records into Postgres for downstream analytics.  
Stack: AWS SQS, Python, PostgreSQL, LocalStack, Docker

### 2) Portfolio Assistant Backend — Guardrailed LLM Gateway
Repo: https://github.com/vaddhiparthy/Pepper_portfolio  
Containerized FastAPI service powering a scoped portfolio assistant. Implements strict context boundaries, schema validation, and security controls for public-facing LLM interactions. Repository is private/access-restricted; demo available on the website.  
Stack: FastAPI, OpenAI SDK, Pydantic, Docker, CORS/security controls

### 3) ASTRA-X Overthinker — Stateful Workflow Orchestrator
Repo: https://github.com/vaddhiparthy/ASTRA-X-Overthinker-v2  
Stateful orchestration system that schedules iterative runs, persists goal state/history, and produces timestamped progress logs/changelogs for reproducible long-horizon workflows.  
Stack: Python, Flask, APScheduler, YAML/Markdown state, Docker

### 4) Privacy-Preserving Synthetic Data Engine (GAN → Downstream Scoring)
Repo: https://github.com/vaddhiparthy/SynthScoreNet  
Synthetic data generation pipeline using a GAN to create credit-feature rows for experimentation and model development under constrained real-data access, followed by downstream scoring/regression training.  
Stack: Python, TensorFlow/Keras, Pandas/NumPy, synthetic data, model training

### 5) VideoSemanticAlignment — Multimodal Research Data Pipeline
Manuscript in peer review. Built the data pipeline to clean event-level text and align it with temporal video segments, producing high-fidelity supervised pairs to enable VLM fine-tuning. Artifacts available on request.  
Stack: Python, PyTorch, temporal alignment, dataset construction, VLM fine-tuning

### 6) Multi-API Metrics Pipeline — Structured Financial Data Outputs
Repo: https://github.com/vaddhiparthy/stock-data-analysis-tool  
Data ingestion and transformation toolkit that pulls from multiple APIs, standardizes metrics, and exports structured tables for downstream screening/analysis.  
Stack: Python, API ingestion, Pandas, structured exports, repeatable pipelines

---
© 2026 Sri Surya S. Vaddhiparthy. All rights reserved.
