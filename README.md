# Dautmer Contreras

**Data Analyst · Power BI Architect · Data Engineer**, based in Bogotá, Colombia.

[Leer en español](README.es.md)

I work across the whole path of data: I build the pipelines, model the data, and design the reports and analyses that teams use to make decisions. I have 3 years of experience in fintech and Business Intelligence consulting.

## What I do

- **Analytics:** SQL and Python analyses for risk, growth, and operations teams: cohorts, acquisition funnels, and segmentation.
- **BI architecture:** Power BI semantic models, star schemas, and dashboards for business teams and consulting clients.
- **Data engineering:** pipelines on Databricks with dbt, Terraform, and CI/CD, like the projects below.
- **Next, data science:** I'm studying for a B.S. in Data Science at Universidad de La Salle, and machine learning is where my next projects are heading.

## Projects

### [Public procurement lakehouse (SECOP II) with CI/CD](https://github.com/DautmerCo/lakehouse-secop-cicd)

A daily pipeline on Colombia's public procurement open data, from the public API to a dashboard. Terraform declares the infrastructure, dbt runs in a Docker image, and every pull request is tested in ephemeral schemas before it reaches `main`.

**Finding:** 71.8% of ~198,000 contracts were awarded directly, without a competitive process, yet they add up to only 31.8% of the total value.

`Databricks` `dbt` `Terraform` `Docker` `GitHub Actions` `Unity Catalog`

### [Credit risk lakehouse on Databricks](https://github.com/DautmerCo/lakehouse-riesgo-credito)

An end-to-end medallion pipeline for a consumer loan portfolio built on synthetic data: incremental ingestion with Auto Loader, data quality rules with quarantine tables, a customer history dimension (SCD Type 2), and a Power BI report on cohorts and delinquency.

**Finding:** after the credit policy was loosened to grow, loans disbursed from July to November 2025 reached 7.4–9.7% of their balance 30+ days past due at 6 months, versus 2.7–6.4% for earlier cohorts.

`Databricks` `PySpark` `Delta Lake` `Asset Bundles` `Power BI`

## Stack

| Area | Tools |
|---|---|
| Languages | SQL, Python (PySpark, pandas), DAX |
| Data platforms | Databricks, Snowflake, Microsoft Fabric, SQL Server |
| Transformation and orchestration | dbt, Lakeflow Jobs, Azure Data Factory, GitHub Actions |
| Engineering practices | Terraform, Docker, Git, CI/CD, data quality testing |
| BI | Power BI (semantic models, DAX, Power Query), Tableau, MicroStrategy |

## Certifications

- Databricks Certified Data Engineer Associate
- Microsoft Certified: Fabric Data Engineer Associate (DP-700)
- Microsoft Certified: Fabric Analytics Engineer Associate (DP-600)
- Microsoft Certified: SQL AI Developer Associate (DP-800)
- Microsoft Certified: Power BI Data Analyst Associate (PL-300)

## Contact

[LinkedIn](https://www.linkedin.com/in/dautmer-contreras)
