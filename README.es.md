# Dautmer Contreras

**Data Analyst · Power BI Architect · Data Engineer**, en Bogotá, Colombia.

[Read in English](README.md)

Trabajo en todo el recorrido de los datos: construyo los pipelines, modelo los datos y diseño los reportes y análisis con los que los equipos toman decisiones. Tengo 3 años de experiencia en fintech y consultoría de Business Intelligence.

## Qué hago

- **Análisis:** análisis con SQL y Python para equipos de riesgo, crecimiento y operaciones: cohortes, embudos de adquisición y segmentación.
- **Arquitectura BI:** modelos semánticos en Power BI, modelos estrella y tableros para equipos de negocio y clientes de consultoría.
- **Ingeniería de datos:** pipelines en Databricks con dbt, Terraform y CI/CD, como los proyectos de abajo.
- **Lo siguiente, ciencia de datos:** estudio Ciencia de Datos en la Universidad de La Salle, y hacia el machine learning van mis próximos proyectos.

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
| BI | Power BI (modelos semánticos, DAX, Power Query), Tableau, MicroStrategy |

## Certificaciones

- Databricks Certified Data Engineer Associate
- Microsoft Certified: Fabric Data Engineer Associate (DP-700)
- Microsoft Certified: Fabric Analytics Engineer Associate (DP-600)
- Microsoft Certified: SQL AI Developer Associate (DP-800)
- Microsoft Certified: Power BI Data Analyst Associate (PL-300)

## Contacto

[LinkedIn](https://www.linkedin.com/in/dautmer-contreras)
