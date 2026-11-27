# Dautmer Contreras

**Data Engineer** based in Bogotá, Colombia. I build data pipelines and dimensional models on Databricks, and I treat them like software: infrastructure as code, automated tests, and CI/CD.

[Leer en español](README.es.md)

I have 3 years of experience in data across fintech and Business Intelligence consulting, working with SQL, Python, Snowflake, SQL Server, and Power BI. I'm also studying Data Science at Universidad de La Salle.

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
| BI | Power BI, Tableau |

## Certifications

- Databricks Certified Data Engineer Associate
- Microsoft Certified: Fabric Data Engineer Associate (DP-700)
- Microsoft Certified: Fabric Analytics Engineer Associate (DP-600)
- Microsoft Certified: SQL AI Developer Associate (DP-800)
- Microsoft Certified: Power BI Data Analyst Associate (PL-300)

## Contact

[LinkedIn](https://www.linkedin.com/in/dautmer-contreras)
