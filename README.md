# Surya Vaddhiparthy

Data Engineer with extensive experience across data engineering, analytics, and software engineering, building banking data platforms under SOX and PII controls.

## Focus

- Batch and streaming pipelines: Airflow, Dagster, dbt, and change data capture on Kafka, Debezium, and Flink
- Warehouse and lakehouse modeling: star schema, SCD Type 2, and dbt models on Snowflake; Databricks with Delta Lake and Iceberg
- Data quality, lineage, and governance for SOX-audited financial reporting
- Cost and performance: warehouse rightsizing, table clustering, and query tuning

## Stack

| Area | Tools |
| --- | --- |
| Languages | Python, SQL, PL/SQL |
| Processing | Apache Spark (PySpark, Spark Streaming), Apache Kafka, Apache Flink |
| Orchestration | Apache Airflow, Dagster, dbt, Fivetran |
| Cloud | AWS (S3, Lambda, Glue), Google Cloud (BigQuery, Dataproc), Microsoft Azure |
| Storage | Snowflake, Databricks (Delta Lake), Apache Iceberg, Amazon Redshift, PostgreSQL |
| Quality | Great Expectations, data observability, data lineage, data contracts, PII masking |
| DevOps | Git, GitHub Actions, Docker, Kubernetes, Terraform, Linux |

## Projects

**[FinLens: Banking Stress Data Platform](https://vaddhiparthy.com/FinLens-Banking-Stress-Intelligence-Platform/)** ![CI](https://github.com/Vaddhiparthy/FinLens-Banking-Stress-Intelligence-Platform/actions/workflows/main.yml/badge.svg?branch=main)
Ingests FDIC, FFIEC, and FRED public data (448K bank-quarter records) through 7 Airflow DAGs into a DuckDB/dbt medallion model with a Kimball star schema and SCD Type 2 snapshots. Quality gates at load and serve; a LightGBM bank-failure model served through FastAPI and Streamlit. Docker, GitHub Actions CI, pytest.

**[Authentication Audit Data Platform](https://vaddhiparthy.com/privacy-preserving-authentication-audit-data-platform/)** ![CI](https://github.com/Vaddhiparthy/Privacy-Preserving-Authentication-Audit-Data-Platform/actions/workflows/ci.yml/badge.svg?branch=main)
SQS-to-PostgreSQL event pipeline enforced by a versioned JSON Schema contract: HMAC tokenization of identifiers, idempotent loads, quarantine table, batch audit trail. 84 tests in GitHub Actions CI; runs locally with LocalStack and Docker Compose.

**[Privacy-Aware Corpus Pipeline](https://vaddhiparthy.com/Privacy-Aware-Corpus-Intelligence-Pipeline)** ![CI](https://github.com/Vaddhiparthy/Privacy-Aware-Corpus-Intelligence-Pipeline/actions/workflows/ci.yml/badge.svg?branch=main)
Streams large JSON archives and routes text to public, private, or low-signal outputs with deterministic PII detection and a reconciliation check that outputs sum to input. 11K units processed; pytest and CI.
