# Dautmer Contreras

**Data Engineer** en Bogotá, Colombia. Construyo pipelines de datos y modelos dimensionales en Databricks, y los trabajo como software: infraestructura como código, pruebas automáticas y CI/CD.

[Read in English](README.md)

Tengo 3 años de experiencia en datos en fintech y consultoría de Business Intelligence, con SQL, Python, Snowflake, SQL Server y Power BI. También estudio Ciencia de Datos en la Universidad de La Salle.

## Proyectos

### [Lakehouse de contratación pública (SECOP II) con CI/CD](https://github.com/DautmerCo/lakehouse-secop-cicd)

Pipeline diario sobre los datos abiertos de contratación pública de Colombia, desde la API pública hasta un tablero. Terraform declara la infraestructura, dbt corre en una imagen Docker y cada pull request se prueba en esquemas efímeros antes de llegar a `main`.

**Hallazgo:** el 71,8 % de ≈198.000 contratos se adjudicó por contratación directa, sin un proceso competitivo, pero esos contratos suman solo el 31,8 % del valor.

`Databricks` `dbt` `Terraform` `Docker` `GitHub Actions` `Unity Catalog`

### [Lakehouse de riesgo de crédito en Databricks](https://github.com/DautmerCo/lakehouse-riesgo-credito)

Pipeline medallion de punta a punta para una cartera de préstamos de consumo con datos sintéticos: ingesta incremental con Auto Loader, reglas de calidad con tablas de cuarentena, dimensión histórica de clientes (SCD tipo 2) y un reporte de Power BI sobre cohortes y mora.

**Hallazgo:** tras relajar la política de crédito para crecer, los préstamos desembolsados entre julio y noviembre de 2025 llegan a 7,4 %–9,7 % de saldo en mora 30+ a los 6 meses, frente a 2,7 %–6,4 % de las cohortes anteriores.

`Databricks` `PySpark` `Delta Lake` `Asset Bundles` `Power BI`

## Stack

| Área | Herramientas |
|---|---|
| Lenguajes | SQL, Python (PySpark, pandas), DAX |
| Plataformas de datos | Databricks, Snowflake, Microsoft Fabric, SQL Server |
| Transformación y orquestación | dbt, Lakeflow Jobs, Azure Data Factory, GitHub Actions |
| Prácticas de ingeniería | Terraform, Docker, Git, CI/CD, pruebas de calidad de datos |
| BI | Power BI, Tableau |

## Certificaciones

- Databricks Certified Data Engineer Associate
- Microsoft Certified: Fabric Data Engineer Associate (DP-700)
- Microsoft Certified: Fabric Analytics Engineer Associate (DP-600)
- Microsoft Certified: SQL AI Developer Associate (DP-800)
- Microsoft Certified: Power BI Data Analyst Associate (PL-300)

## Contacto

[LinkedIn](https://www.linkedin.com/in/dautmer-contreras)
