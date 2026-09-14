# Sri Surya S. Vaddhiparthy

Data Engineer with 8+ years building batch ETL/ELT pipelines, cloud data platforms, and regulatory reporting systems across banking, healthcare, insurance, and retail.

[Portfolio](https://surya.vaddhiparthy.com) | [Projects](https://surya.vaddhiparthy.com/portfolio) | [Research](https://surya.vaddhiparthy.com/case-studies) | [LinkedIn](https://www.linkedin.com/in/vaddhiparthy) | [Email](mailto:surya@vaddhiparthy.com)

## Focus

I build production-minded data systems that move from ingestion to trusted decision support: clear contracts, observable execution, quality checks, cost-aware modeling, and practical operating discipline.

Current focus areas:

- Batch pipeline orchestration with Airflow, Informatica IICS, and AWS Step Functions, with SLA-backed scheduling and failure recovery
- Data platform architecture across ingestion, transformation, validation, orchestration, and serving layers
- Warehouse modeling and ELT with dbt on Snowflake and Redshift, with data quality gates and reconciliation controls
- Regulatory reporting platform engineering on NASDAQ AxiomSL ControllerView with SOX and HIPAA controls
- Privacy-aware audit pipelines, governed event processing, and traceable operational data products
- Retrieval, RAG, and LLM evaluation systems where data quality and measurement matter
- Cloud and containerized delivery with Docker, CI/CD, Terraform, and Linux operations

## Core Stack

| Area | Technologies |
| --- | --- |
| Languages | Python, SQL, PySpark |
| ETL / ELT | Informatica IICS/IDMC and PowerCenter, dbt, incremental loads, backfills |
| Orchestration | Airflow, IICS taskflows, AWS Step Functions, Azure Data Factory, GitHub Actions |
| Cloud | AWS (S3, Glue, Lambda, Step Functions, EMR, Athena), Azure, Databricks, Delta Lake |
| Warehouses and Databases | Snowflake, Redshift, Teradata, Oracle, SQL Server, PostgreSQL, DuckDB |
| Quality and Governance | Great Expectations, dbt tests, reconciliation, data lineage, data contracts, schema validation |
| Regulatory | NASDAQ AxiomSL ControllerView, FR Y-9C, FFIEC, SOX, HIPAA |
| Services | FastAPI, Streamlit, Docker, Terraform, Linux |
| AI and Retrieval | LangChain, LangGraph, RAG pipelines, pgvector, Milvus, LLM evaluation |
| Operations | Structured logging, runbooks, incident review, performance and cost monitoring |

## Selected Work

### FinLens: Banking Stress Intelligence Platform

[Presentation](https://surya.vaddhiparthy.com/FinLens-Banking-Stress-Intelligence-Platform/) | [Repository](https://github.com/vaddhiparthy/FinLens-Banking-Stress-Intelligence-Platform)

End-to-end banking-stress intelligence platform that turns free FDIC, FFIEC, and FRED public data into a calibrated early-warning read on U.S. bank distress. A governed DuckDB/dbt lakehouse with Great Expectations quality gates feeds an out-of-time-validated LightGBM hazard model, served through FastAPI and Streamlit.

**Signals:** Airflow, dbt, Great Expectations, Snowflake/DuckDB patterns, medallion layering, FastAPI, Docker, Terraform, GitHub Actions.

### Privacy-Preserving Authentication Audit Data Platform

[Presentation](https://surya.vaddhiparthy.com/privacy-preserving-authentication-audit-data-platform/) | [Repository](https://github.com/vaddhiparthy/Privacy-Preserving-Authentication-Audit-Data-Platform)

Authentication telemetry pipeline with SQS-compatible queue intake, versioned event contracts, HMAC tokenization of sensitive identifiers, PostgreSQL curated and quarantine tables, and batch-level audit evidence, reproducible locally through LocalStack and Docker Compose.

**Signals:** Python ETL, data contracts, PostgreSQL, Docker, privacy engineering, audit evidence, structured logging.

### Privacy-Aware Corpus Intelligence Pipeline

[Presentation](https://surya.vaddhiparthy.com/Privacy-Aware-Corpus-Intelligence-Pipeline) | [Repository](https://github.com/vaddhiparthy/Privacy-Aware-Corpus-Intelligence-Pipeline)

Local-first pipeline separating public-safe text from sensitive content in large conversation archives, with deterministic PII detection, sensitive-domain routing, and auditable review artifacts.

**Signals:** Python, streaming JSON processing, PII detection, Presidio, governed data flow.

## Operating Strengths

- Designed data systems with stronger ingestion, modeling, validation, and serving contracts
- Built reliability practices around structured logs, runbooks, failure isolation, and repeatable deployment
- Cut cloud platform and compute costs 20 to 25 percent through warehouse right-sizing, partitioning, and query profiling
- Connect data engineering fundamentals with AI/RAG systems without losing traceability or measurement

## Direction

I am focused on data engineering and data platform roles where pipeline reliability, data quality, cloud data architecture, and regulatory-grade governance matter. My best work sits at the intersection of production batch pipelines, governed analytics layers, and retrieval-aware systems.
