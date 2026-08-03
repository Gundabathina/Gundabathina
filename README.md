<h1 align="center">Prem Teja Gundabathina</h1>

<p align="center">
  <b>Data Engineer</b> · Dallas–Fort Worth, Texas
</p>

<p align="center">
  Building reliable healthcare and cloud data pipelines — batch and streaming — that turn raw source data into analytics-ready tables.
</p>

<p align="center">
  <a href="https://prem-portfolio-nu.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/prem-teja-21856a28b/">LinkedIn</a> ·
  <a href="https://github.com/Gundabathina/claimslake">ClaimsLake</a> ·
  <a href="mailto:premteja.data@gmail.com">Email</a>
</p>

<img src="assets/divider.svg" alt="" width="100%" />

## About

I design and operate the pipelines that move data from raw source systems to analytics-ready tables. Day to day that means **Spark / PySpark** for high-volume processing, **Kafka and Spark Streaming** for real-time ingestion, and **Airflow + dbt** for orchestration and transformation on **Snowflake, Redshift, and AWS**.

- **3+ years** designing, building, and optimizing large-scale data pipelines and cloud-native architectures.
- **Healthcare and banking** domains — HIPAA-aware claims and member data; earlier, banking datasets for fraud analytics and regulatory reporting.
- **Batch and streaming** — Spark and PySpark for high-volume processing; Kafka and Spark Streaming for real-time ingestion.
- **Growing AI/ML exposure** — LangChain, OpenAI APIs, Hugging Face models, embeddings, and RAG pipelines.

<img src="assets/divider.svg" alt="" width="100%" />

## Experience

- **Data Engineer** — HighViz IT Solutions Inc · _Jul 2024 – Present_
- **Data Engineer (Contract)** — Ven Solutions LLC · _Jan 2024 – Jun 2024_
- **Associate Data Engineer (Intern)** — Accenture · _Jun 2022 – Jun 2023_

## Education

- **M.S. in System Science Engineering** — Binghamton University, NY · _Aug 2023 – Dec 2024_
- **B.Tech in Information Technology** — VIT

<img src="assets/divider.svg" alt="" width="100%" />

## Featured project — ClaimsLake

An end-to-end, production-style healthcare **claims data engineering platform** built on a medallion (**Bronze → Silver → Gold**) architecture. Raw synthetic claims files are ingested with config-driven Python, cleaned and validated in **PySpark** (with an explicit quarantine path rather than silent drops), and modeled into a **dbt-duckdb** star schema, all orchestrated with **Airflow** and reproducible locally via **Docker Compose**.

Verified facts from the repository:

- **17 PySpark tests passed**
- **dbt PASS = 14**
- **35 analytical SQL queries** across **five domains** (Claims, Finance, Members, Providers, Data Quality)
- **Docker Compose verified locally** — MinIO and PostgreSQL healthy; Airflow webserver and scheduler running
- **Four-job GitHub Actions CI**
- **Terraform AWS reference architecture** — CI-validated, **never deployed** (creates no resources or cost)
- **Synthetic data only** — no real patient, member, or provider records are used anywhere

→ **[Read the ClaimsLake case study](https://github.com/Gundabathina/claimslake)**

<img src="assets/divider.svg" alt="" width="100%" />

## Tech

**Languages:** SQL · Python · PySpark · Scala · Java · JavaScript
**Big Data & ETL:** Spark · dbt · AWS Glue · Informatica · SSIS
**Streaming:** Kafka · Spark Streaming
**Orchestration:** Apache Airflow
**Warehousing & DBs:** Snowflake · Redshift · DuckDB · PostgreSQL · SQL Server · Oracle
**Cloud:** AWS · Azure
**DevOps:** Docker · Terraform · GitHub Actions
**BI:** Power BI · Tableau
**AI/ML:** LangChain · OpenAI APIs · Hugging Face · embeddings · RAG

<img src="assets/divider.svg" alt="" width="100%" />

<p align="center">
  Open to Data Engineer and AI/ML platform roles.<br/>
  <a href="https://prem-portfolio-nu.vercel.app">prem-portfolio-nu.vercel.app</a>
</p>
