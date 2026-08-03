<div align="center">

<img src="https://raw.githubusercontent.com/Gundabathina/Gundabathina/main/assets/hero-name.svg" alt="Prem Teja Gundabathina — Data Engineer" width="640" />

I build the data platforms that turn raw, messy source systems into trustworthy, analytics-ready products.

<a href="https://prem-portfolio-nu.vercel.app"><img src="https://img.shields.io/badge/Portfolio-3B82F6?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>&nbsp;<a href="https://github.com/Gundabathina/claimslake"><img src="https://img.shields.io/badge/ClaimsLake-06B6D4?style=for-the-badge&logo=github&logoColor=white" alt="ClaimsLake" /></a>&nbsp;<a href="https://www.linkedin.com/in/prem-teja-21856a28b/"><img src="https://img.shields.io/badge/LinkedIn-8B5CF6?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;<a href="https://prem-portfolio-nu.vercel.app/resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-1F2937?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume" /></a>

<img src="https://raw.githubusercontent.com/Gundabathina/Gundabathina/main/assets/divider.svg" alt="" width="100%" />

</div>

&nbsp;

## &nbsp; Featured Work &nbsp; · &nbsp; ClaimsLake

> A healthcare claims data platform that carries synthetic claims through a **Bronze → Silver → Gold** medallion architecture — ingested in Python, cleaned and validated in PySpark, modeled in dbt, orchestrated with Airflow, and fully reproducible with Docker Compose.

| | |
|:--|:--|
| **Problem** | Raw healthcare claims are messy, inconsistent, and hard to trust for analytics. |
| **Architecture** | Medallion layers — Bronze (raw) → Silver (clean · validate · quarantine) → Gold (dbt star schema, SCD2) → Analytics → AWS reference. |
| **Engineering** | Tested PySpark transformations, automated data-quality gates, orchestrated DAGs, reproducible local infra. |
| **Technology** | `Python` `PySpark` `dbt` `Airflow` `DuckDB` `Docker` `Terraform` `GitHub Actions` |
| **Verified** | 17 PySpark tests passing · dbt PASS = 14 · 35 SQL queries across 5 domains · four-job CI · Docker Compose verified locally · Terraform AWS reference (CI-validated, never deployed) · synthetic data only. |
| **Next** | Streaming ingestion, expanded dbt test coverage, and a deployed cloud reference environment. |

### &nbsp; → &nbsp; [Explore ClaimsLake](https://github.com/Gundabathina/claimslake)

&nbsp;

## &nbsp; Architecture

```mermaid
flowchart LR
  S([Sources]):::src --> B[Bronze]:::bronze --> Si[Silver]:::silver --> G[Gold]:::gold --> A[Analytics]:::an --> C[(AWS Cloud)]:::cloud
  classDef src fill:#1F2937,stroke:#8B949E,color:#C9D1D9;
  classDef bronze fill:#3B82F6,stroke:#3B82F6,color:#fff;
  classDef silver fill:#06B6D4,stroke:#06B6D4,color:#0b1220;
  classDef gold fill:#F59E0B,stroke:#F59E0B,color:#0b1220;
  classDef an fill:#8B5CF6,stroke:#8B5CF6,color:#fff;
  classDef cloud fill:#1F2937,stroke:#3B82F6,color:#C9D1D9;
```

&nbsp;

## &nbsp; Current Engineering Focus

<img src="https://img.shields.io/badge/Cloud_Data_Engineering-3B82F6?style=flat-square" /> <img src="https://img.shields.io/badge/Healthcare_Data-06B6D4?style=flat-square" /> <img src="https://img.shields.io/badge/Snowflake-3B82F6?style=flat-square&logo=snowflake&logoColor=white" /> <img src="https://img.shields.io/badge/AWS-8B5CF6?style=flat-square&logo=amazonaws&logoColor=white" /> <img src="https://img.shields.io/badge/PySpark-06B6D4?style=flat-square&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Airflow-3B82F6?style=flat-square&logo=apacheairflow&logoColor=white" /> <img src="https://img.shields.io/badge/dbt-8B5CF6?style=flat-square&logo=dbt&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-06B6D4?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Terraform-8B5CF6?style=flat-square&logo=terraform&logoColor=white" />

&nbsp;

## &nbsp; Featured Projects

| Project | Summary | Tech | Links |
|:--|:--|:--|:--|
| **ClaimsLake** | Healthcare claims platform on a Bronze → Gold medallion architecture. | `PySpark` `dbt` `Airflow` | [Repo](https://github.com/Gundabathina/claimslake) |
| **Portfolio** | Data engineering portfolio site. | `React` `TypeScript` | [Repo](https://github.com/Gundabathina/prem-portfolio) · [Live](https://prem-portfolio-nu.vercel.app) |
| **Healthcare Analytics** | Exploratory analysis of patient appointment no-show data. | `Python` `Pandas` | [Repo](https://github.com/Gundabathina/Healthcare-Data-Analysis-Using-Python) |
| **Medical Cost Forecasting** | Forecasting insurance costs with EDA and regression. | `scikit-learn` | [Repo](https://github.com/Gundabathina/Medical-Cost-Analysis-and-Forecasting) |

&nbsp;

## &nbsp; Engineering Philosophy

**Reliable Systems**&nbsp;&nbsp;·&nbsp;&nbsp;**Automation First**&nbsp;&nbsp;·&nbsp;&nbsp;**Data Quality**&nbsp;&nbsp;·&nbsp;&nbsp;**Infrastructure as Code**&nbsp;&nbsp;·&nbsp;&nbsp;**Scalable Design**

&nbsp;

<div align="center">

<img src="https://raw.githubusercontent.com/Gundabathina/Gundabathina/main/assets/divider.svg" alt="" width="100%" />

## Contact

[Portfolio](https://prem-portfolio-nu.vercel.app)&nbsp;&nbsp;·&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/prem-teja-21856a28b/)&nbsp;&nbsp;·&nbsp;&nbsp;[GitHub](https://github.com/Gundabathina)&nbsp;&nbsp;·&nbsp;&nbsp;[Email](mailto:premteja.data@gmail.com)

Dallas–Fort Worth, Texas

</div>
