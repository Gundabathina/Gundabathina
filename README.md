<!-- ====================== HERO ====================== -->
<div align="center">

<img src="assets/hero.svg" alt="Prem Teja Gundabathina — Data Engineer · Healthcare Data Platforms · Cloud Pipelines · AI-ready Data Systems" width="100%" />

<br/>

### I build the data platforms that turn raw, messy source systems into trustworthy, analytics-ready products.

<br/>

<a href="https://prem-portfolio-nu.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0B1226?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
&nbsp;
<a href="https://github.com/Gundabathina/claimslake"><img src="https://img.shields.io/badge/ClaimsLake-3b82f6?style=for-the-badge&logo=github&logoColor=white" alt="ClaimsLake" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/prem-teja-21856a28b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
&nbsp;
<a href="https://prem-portfolio-nu.vercel.app/resume.pdf"><img src="https://img.shields.io/badge/Résumé-8b5cf6?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Résumé" /></a>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== FEATURED PROJECT ====================== -->
<div align="center">

<kbd>&nbsp;FEATURED PROJECT&nbsp;</kbd>

# ClaimsLake

**Healthcare Claims Data Engineering Platform**

An end-to-end, production-style pipeline that carries synthetic healthcare claims through a
**Bronze → Silver → Gold** medallion architecture — ingested with Python, transformed in PySpark,
modeled in dbt, orchestrated with Airflow, and reproducible locally with Docker Compose.

<br/>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
<img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

<br/><br/>

<img src="assets/architecture.svg" alt="ClaimsLake medallion architecture: Bronze, Silver, Gold, Analytics, Cloud" width="100%" />

</div>

<br/>

> **Engineering highlights** &nbsp;·&nbsp; Config-driven ingestion &nbsp;·&nbsp; PySpark cleaning with an explicit **quarantine path** (never silent drops) &nbsp;·&nbsp; **SCD Type 2** provider history &nbsp;·&nbsp; dbt-duckdb star schema &nbsp;·&nbsp; a curated analytical SQL layer &nbsp;·&nbsp; a path-filtered Terraform validation workflow.

<div align="center">

|  |  |  |  |
|:--|:--|:--|:--|
| **17** PySpark tests passed | **dbt PASS = 14** | **35** analytical SQL queries | **5** SQL domains |
| Docker Compose verified locally | MinIO + PostgreSQL healthy | Airflow webserver + scheduler running | Four-job GitHub Actions CI |

_Terraform AWS reference architecture — CI-validated, never deployed. Synthetic data only; no real patient, member, or provider records._

<br/>

### [&nbsp;Explore ClaimsLake&nbsp; →](https://github.com/Gundabathina/claimslake)

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== ARCHITECTURE (native) ====================== -->
<div align="center">

<kbd>&nbsp;ARCHITECTURE&nbsp;</kbd>

### How the data moves

</div>

```mermaid
flowchart LR
    A[Raw claims files] --> B[Python ingestion<br/>config-driven]
    B --> C[Bronze<br/>raw landed]
    C --> D[Silver<br/>PySpark · clean · validate · dedup]
    D --> E[Gold<br/>dbt-duckdb star schema · SCD2]
    E --> F[Analytics<br/>35 SQL queries · 5 domains]
    E --> G[AWS reference<br/>S3 · Glue · Athena]
    B -.orchestrated by.- H((Apache Airflow))
    D -.orchestrated by.- H
    E -.orchestrated by.- H
```

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== ENGINEERING PHILOSOPHY ====================== -->
<div align="center">

<kbd>&nbsp;ENGINEERING PHILOSOPHY&nbsp;</kbd>

### Principles the work is built on

<table>
<tr>
<td align="center" width="20%"><br/><b>Reliable Systems</b><br/><sub>Retries, alerting,<br/>reproducible runs</sub><br/><br/></td>
<td align="center" width="20%"><br/><b>Automation First</b><br/><sub>Orchestrated pipelines,<br/>not manual steps</sub><br/><br/></td>
<td align="center" width="20%"><br/><b>Data Quality</b><br/><sub>Validate &amp; quarantine,<br/>never silently drop</sub><br/><br/></td>
<td align="center" width="20%"><br/><b>Infrastructure as Code</b><br/><sub>Versioned, reviewed,<br/>CI-validated</sub><br/><br/></td>
<td align="center" width="20%"><br/><b>Scalable Design</b><br/><sub>Batch &amp; streaming,<br/>cloud-native</sub><br/><br/></td>
</tr>
</table>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== CURRENT FOCUS ====================== -->
<div align="center">

<kbd>&nbsp;CURRENT FOCUS&nbsp;</kbd>

### What I'm building right now

</div>

<table>
<tr>
<td width="33%" align="center"><br/><b>Healthcare Data Platforms</b><br/><sub>HIPAA-aware claims &amp; member pipelines</sub><br/><br/></td>
<td width="33%" align="center"><br/><b>Cloud Data Engineering</b><br/><sub>Snowflake · Redshift · AWS · Airflow · dbt</sub><br/><br/></td>
<td width="33%" align="center"><br/><b>Production ETL</b><br/><sub>Batch &amp; streaming, built to run unattended</sub><br/><br/></td>
</tr>
<tr>
<td width="33%" align="center"><br/><b>Data Quality</b><br/><sub>Validation, quarantine, testable transforms</sub><br/><br/></td>
<td width="33%" align="center"><br/><b>GenAI-ready Data Pipelines</b><br/><sub>LangChain · OpenAI · embeddings · RAG</sub><br/><br/></td>
<td width="33%" align="center"><br/><b>Infrastructure as Code</b><br/><sub>Terraform reference architectures</sub><br/><br/></td>
</tr>
</table>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== SELECTED PROJECTS ====================== -->
<div align="center">

<kbd>&nbsp;SELECTED PROJECTS&nbsp;</kbd>

### Selected work

</div>

<table>
<tr>
<td width="50%" valign="top">

#### [ClaimsLake →](https://github.com/Gundabathina/claimslake)
End-to-end healthcare claims platform on a Bronze → Gold medallion architecture. Python · PySpark · dbt · Airflow · Docker.

</td>
<td width="50%" valign="top">

#### [Portfolio →](https://github.com/Gundabathina/prem-portfolio)
Data engineering portfolio site — React · TypeScript · Vite · Tailwind. Live at prem-portfolio-nu.vercel.app.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Healthcare Analytics →](https://github.com/Gundabathina/Healthcare-Data-Analysis-Using-Python)
Exploratory analysis of patient appointment no-show data. Python · Pandas · Matplotlib · Seaborn.

</td>
<td width="50%" valign="top">

#### [Medical Cost Forecasting →](https://github.com/Gundabathina/Medical-Cost-Analysis-and-Forecasting)
Forecasting medical insurance costs with EDA, linear &amp; polynomial regression. Python · scikit-learn.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Tesla Stock Analysis →](https://github.com/Gundabathina/Tesla-Stock-Price-Analysis-and-Prediction-Using-Python)
Stock price analysis &amp; prediction with technical indicators and ARIMA. Python · statsmodels.

</td>
<td width="50%" valign="top">

#### [More on GitHub →](https://github.com/Gundabathina?tab=repositories)
Additional analytics and data projects across healthcare, finance, and public datasets.

</td>
</tr>
</table>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== TECH STACK ====================== -->
<div align="center">

<kbd>&nbsp;TECHNOLOGY STACK&nbsp;</kbd>

### The tools I work with

<br/>

**Languages**

<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white" />
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />

**Cloud**

<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white" />

**Data Engineering**

<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />

**Databases &amp; Warehousing**

<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white" />
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />

**Analytics &amp; BI**

<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />

**DevOps**

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<!-- ====================== CONTACT ====================== -->
<div align="center">

<kbd>&nbsp;CONTACT&nbsp;</kbd>

### Let's build reliable data systems.

Open to Data Engineer and AI/ML platform roles &nbsp;·&nbsp; Dallas–Fort Worth, Texas

<br/>

<a href="https://prem-portfolio-nu.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0B1226?style=for-the-badge&logo=vercel&logoColor=white" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/prem-teja-21856a28b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
&nbsp;
<a href="mailto:premteja.data@gmail.com"><img src="https://img.shields.io/badge/Email-06b6d4?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>
