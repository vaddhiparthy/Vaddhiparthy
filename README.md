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

An end-to-end banking-stress intelligence platform that turns free FDIC, FFIEC, and FRED public data into a calibrated early-warning read on U.S. bank distress. A governed DuckDB/dbt lakehouse (Great Expectations quality gates) feeds an out-of-time-validated, monotone, SHAP-explained LightGBM hazard model that scores each bank four-quarter distress probability, served via FastAPI, Streamlit surfaces, and a cited assistant.

**Signals:** Airflow, dbt, Great Expectations, Snowflake/DuckDB patterns, FastAPI, Streamlit, data platform documentation.

### Privacy-Preserving Authentication Audit Data Platform

[Presentation](https://surya.vaddhiparthy.com/privacy-preserving-authentication-audit-data-platform/) | [Repository](https://github.com/vaddhiparthy/Privacy-Preserving-Authentication-Audit-Data-Platform)

Authentication telemetry pipeline that ingests login events, pseudonymizes sensitive fields, persists structured audit data, and supports privacy-aware operational analysis.

**Signals:** Python ETL, queue-style intake, PostgreSQL, Docker, privacy engineering, audit evidence, data contracts.

### Privacy-Aware Corpus Intelligence Pipeline

[Presentation](https://surya.vaddhiparthy.com/Privacy-Aware-Corpus-Intelligence-Pipeline) | [Repository](https://github.com/vaddhiparthy/Privacy-Aware-Corpus-Intelligence-Pipeline)

Data engineering and AI pipeline for corpus processing, governed text handling, and retrieval-oriented analytics. This project connects data platform discipline with modern AI/search workflows.

**Signals:** Python, corpus processing, governed data flow, retrieval-aware architecture, AI-ready data preparation.

### Failure-Aware Metric Realignment for Post-Hoc Dense Retrieval

[Presentation](https://surya.vaddhiparthy.com/Failure-Aware-Metric-Realignment-for-Post-Hoc-Dense-Retrieval)

Research-oriented retrieval evaluation project for legal QA and dense retrieval diagnostics. It explores failure-aware post-hoc transformation methods, grid-search evaluation, result persistence, and scientific reporting.

**Signals:** Python, DuckDB, retrieval evaluation, legal RAG benchmarks, embeddings, experiment tracking, reproducible research artifacts.

### Synthetic Credit Score Modeling

[Repository](https://github.com/vaddhiparthy/Synthetic-Credit-Score-Modeling)

Machine-learning project around synthetic credit data generation and credit scoring for thin-file borrowers.

**Signals:** ML modeling, synthetic data, credit-risk framing, responsible data-product thinking.

### Semantic Expert Routing Architecture

[Repository](https://github.com/vaddhiparthy/Semantic-Expert-Routing-Architecture)

Research-grade PyTorch scaffold for semantic expert routing in a compact mixture-of-experts model on small-compute environments, with teacher/student routers, centroid routing, load balancing, and observability helpers.

**Signals:** LLM systems, mixture-of-experts, routing, model specialization, AI infrastructure experimentation.

### Agentic Planning and Execution Intelligence Platform

[Presentation](https://surya.vaddhiparthy.com/overthinker/) | [Repository](https://github.com/vaddhiparthy/Agentic-Planning-and-Execution-Intelligence-Platform)

A FastAPI service that iteratively refines Markdown-based goals with an LLM and a rich persona file, maintaining per-goal files, appending timestamped progress, tracking iterations, and building an auditable plan-and-execute trail.

**Signals:** FastAPI, LLM workflows, scheduling, PostgreSQL, agentic planning, progress tracking.

### Iterative Research Intelligence Workbench

[Repository](https://github.com/vaddhiparthy/Iterative-Research-Intelligence-Workbench)

A local-first iterative deep-research tool built on Ollama, with an interactive web UI and human-in-the-loop feedback that nudges research directions across rounds.

**Signals:** Python, Ollama/local LLMs, Docker, SQLite, interactive UI, human-in-the-loop research.

## Operating Strengths

- Designed data systems with stronger ingestion, modeling, validation, and serving contracts
- Built reliability practices around structured logs, runbooks, failure isolation, and repeatable deployment
- Cut cloud platform and compute costs 20 to 25 percent through warehouse right-sizing, partitioning, and query profiling
- Connect data engineering fundamentals with AI/RAG systems without losing traceability or measurement

## Direction

I am focused on data engineering and data platform roles where pipeline reliability, data quality, cloud data architecture, and regulatory-grade governance matter. My best work sits at the intersection of production batch pipelines, governed analytics layers, and retrieval-aware systems.
