# Sri Surya S. Vaddhiparthy
## Senior Data Engineer & Architect
[![Website](https://img.shields.io/badge/Website-surya.vaddhiparthy.com-blue)](https://surya.vaddhiparthy.com) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vaddhiparthy-blue?logo=linkedin)](https://linkedin.com/in/vaddhiparthy)
[![Email](https://img.shields.io/badge/Email-surya%40vaddhiparthy.com-red)](mailto:surya@vaddhiparthy.com)

---

## Professional Summary
Senior Data Engineer & Architect focused on building production-grade data platforms and ELT/ETL frameworks. I turn fragmented sources into governed, analytics-ready datasets with strong reliability (SLAs, monitoring, runbooks), cost discipline (Snowflake/AWS FinOps), and clean delivery standards (IaC, CI/CD, reproducibility). Core stack: Snowflake, AWS, Airflow, dbt, Spark/PySpark, Python, SQL—plus production LLM systems where they materially improve workflows.

- **Data Platform Architecture:** Snowflake + dbt + Airflow ecosystems, dimensional marts/metrics, warehouse/query tuning, and repeatable delivery patterns.
- **Reliability & Governance:** Data quality/observability (tests, lineage/monitoring, incident runbooks), auditability/backfills, and privacy-first ingestion (PII-safe transformations).
- **Production AI Systems (when relevant):** Retrieval pipelines and guardrailed LLM interfaces (scoped context, evaluation/controls) built as real services—not notebooks.

---

## Technical Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Data Platforms** | **Snowflake**, AWS (S3, Glue, Redshift, ECS), BigQuery, Databricks |
| **Orchestration** | **Airflow**, dbt (Models/Macros/Tests), Prefect, Terraform (IaC) |
| **AI / Vector Ops** | **LangGraph**, LangChain, Milvus, pgvector, RAGAS, VLM Fine-tuning |
| **Engineering** | Python, SQL, PySpark, Docker, CI/CD (GitHub Actions) |
| **Observability** | **Monte Carlo**, Great Expectations, Langfuse, CloudWatch |

---

## Featured Engineering Systems

### **[Secure PII Event Ingestion Framework (SQS → Postgres)](https://github.com/vaddhiparthy/Login-Events-ETL)**
Event-driven ingestion pipeline consuming authentication/login events via AWS SQS (LocalStack for reproducible local runs). Applies SHA-256 pseudonymization mid-flight and lands normalized records into Postgres for downstream analytics.  
`AWS SQS` `Python` `PostgreSQL` `LocalStack` `Docker`

### **[Portfolio Assistant Backend — Guardrailed LLM Gateway](https://github.com/vaddhiparthy/Pepper_portfolio)**
Containerized FastAPI service powering a scoped portfolio assistant. Implements strict context boundaries, schema validation, and security controls for public-facing LLM interactions. *(Repo is private / access-restricted.)*  
`FastAPI` `OpenAI SDK` `Pydantic` `Docker` `CORS/Security Controls`

### **[ASTRA-X Overthinker — Stateful Workflow Orchestrator](https://github.com/vaddhiparthy/ASTRA-X-Overthinker-v2)**
A stateful orchestration system that schedules iterative runs, persists goal state/history, and produces timestamped progress logs/changelogs for reproducible long-horizon workflows.  
`Python` `Flask` `APScheduler` `YAML/Markdown State` `Docker`

### **[Privacy-Preserving Synthetic Data Engine (GAN → Downstream Scoring)](https://github.com/vaddhiparthy/SynthScoreNet)**
Synthetic data generation pipeline using a GAN to create credit-feature rows for experimentation and model development under constrained real-data access, followed by downstream scoring/regression training.  
`Python` `TensorFlow/Keras` `Pandas/NumPy` `Synthetic Data` `Model Training`

### **VideoSemanticAlignment — Multimodal Research Data Pipeline**
*Manuscript in peer review (targeting CVPR/ICCV 2026).* Built the data pipeline to clean event-level text and align it with temporal video segments, producing high-fidelity supervised pairs to enable VLM fine-tuning.  
`Python` `PyTorch` `Temporal Alignment` `Dataset Construction` `VLM Fine-Tuning`

### **[Multi-API Metrics Pipeline — Structured Financial Data Outputs](https://github.com/vaddhiparthy/stock-data-analysis-tool)**
Data ingestion + transformation toolkit that pulls from multiple APIs, standardizes metrics, and exports structured tables for downstream screening/analysis.  
`Python` `API Ingestion` `Pandas` `Structured Exports` `Repeatable Pipelines`

---
*© 2026 Sri Surya S. Vaddhiparthy. Senior Data Engineer & Architect.*
