# Sri Surya S. Vaddhiparthy  
Senior Data Engineer (Data Platforms, FinOps, Reliability)  


Website: https://surya.vaddhiparthy.com  
LinkedIn: https://linkedin.com/in/vaddhiparthy  
Email: surya@vaddhiparthy.com  

## Professional Summary
Senior Data Engineer (8 years) focused on building reliable, cost-aware data systems—from ingestion and orchestration to modeling, validation, and operational support. My GitHub highlights the engineering side of my work: event-driven pipelines, workflow orchestration, API-based ingestion, privacy-safe transformations, and dataset construction pipelines used for analytics and ML.

**Core stack:** Snowflake, AWS, Airflow, dbt, Spark/PySpark, Python, SQL.

## Highlights
- Built repeatable ingestion + transformation pipelines with strong failure handling (retries, idempotency, schema checks)
- Shipped dimensional modeling and analytics-ready datasets with automated validation and clear ownership boundaries
- Emphasized operational rigor: monitoring, runbooks, cost controls, and reproducible environments for faster debugging and safer releases

## What I Build
- Data ingestion and integration: APIs/events → normalized storage, with schema enforcement and backfill-safe designs
- Orchestration and reliability: scheduled/stateful workflows, durable retries, and observable execution paths
- Privacy-safe data handling: pseudonymization, least-privilege boundaries, and PII-aware transformations

## Technical Stack
| Domain | Tools & Technologies |
|---|---|
| Data Platforms | Snowflake, AWS (S3, Glue, Lambda, ECS/Fargate), BigQuery |
| Orchestration & Transform | Airflow, dbt (Models/Macros/Tests/Docs) |
| Distributed Compute & Streaming | Spark, PySpark, Kafka |
| Engineering | Python, SQL, Docker, Git, CI/CD, Terraform |
| Quality & Observability | Great Expectations, CloudWatch, SLAs, runbooks, data observability tooling |

## Featured Engineering Systems (Selected)

### 1) Secure PII Event Ingestion Framework (SQS → Postgres)
Repo: https://github.com/vaddhiparthy/Login-Events-ETL  
Event-driven pipeline that consumes authentication events, applies deterministic pseudonymization, and lands normalized records in Postgres for downstream analytics. Designed for reproducible local execution and safe iteration.  
**Stack:** AWS SQS, Python, PostgreSQL, LocalStack, Docker

### 2) Portfolio Assistant Backend — Guardrailed LLM Gateway
Repo: https://github.com/vaddhiparthy/Pepper_portfolio  
Backend service that enforces strict request/response schemas, scoped context access, and controlled inputs/outputs. Built as an API-first system with clear boundaries and deployment-friendly packaging. Repository is private; demo available on the website.  
**Stack:** FastAPI, OpenAI SDK, Pydantic, Docker, CORS/security controls

### 3) ASTRA-X Overthinker — Stateful Workflow Orchestrator
Repo: https://github.com/vaddhiparthy/ASTRA-X-Overthinker-v2  
Stateful orchestration service that schedules jobs, persists run history, and produces audit-friendly logs/changelogs. Demonstrates workflow patterns that translate directly to production orchestration (state, retries, traceability).  
**Stack:** Python, Flask, APScheduler, YAML/Markdown state, Docker

### 4) Privacy-Preserving Synthetic Data Engine (GAN → Downstream Scoring)
Repo: https://github.com/vaddhiparthy/SynthScoreNet  
Pipeline that generates privacy-preserving synthetic datasets for experimentation when real data access is constrained, then runs downstream training/scoring workflows on the synthetic outputs. Emphasis is on dataset lifecycle, repeatability, and controlled outputs.  
**Stack:** Python, TensorFlow/Keras, Pandas/NumPy, synthetic data, model training

### 5) VideoSemanticAlignment — Multimodal Research Data Pipeline
Manuscript in peer review. Built a pipeline that cleans event text, aligns it to temporal video segments, and produces supervised training pairs with consistent formatting and QA steps. Artifacts available on request.  
**Stack:** Python, PyTorch, temporal alignment, dataset construction, VLM fine-tuning

### 6) Multi-API Metrics Pipeline — Structured Financial Data Outputs
Repo: https://github.com/vaddhiparthy/stock-data-analysis-tool  
API ingestion + normalization toolkit that standardizes fields across sources and exports clean, analysis-ready tables. Designed around repeatable runs and consistent outputs.  
**Stack:** Python, API ingestion, Pandas, structured exports, repeatable pipelines
