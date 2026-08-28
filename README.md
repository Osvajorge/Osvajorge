# Jorge Guardado

**Data Engineer** · Barcelona, Spain

Building production data pipelines for enterprise supply-chain planning. Currently at
[Quantiqus](https://quantiqus.com), working on-site with Mango on a large-scale
[o9 Solutions](https://o9solutions.com) implementation for Merchandise Financial Planning
and Assortment Planning.

---

## What I work on

- **Integration pipelines** — medallion architecture (raw → normalized → planning layer) built in PySpark, moving data from Snowflake and Databricks into the o9 data lake.
- **Data modeling** — Delta Lake tables, incremental merges, SCD handling, and dimensional models that feed OLAP cubes and live planning workspaces.
- **Data quality** — reconciliation and validation frameworks that catch drift between source systems and the planning platform before the business does.
- **Documentation** — pipeline specs, runbooks, and architecture notes that let the next engineer pick up the work without a handover call.

Before moving into data engineering, I spent roughly five years in SQL support
engineering at Oracle and TCS — a background that still shapes how I debug query
plans and read execution behavior.

---

## Tech stack

| Area | Tools |
|---|---|
| **Processing** | PySpark, Python, pandas |
| **Query** | SQL, Snowflake SQL, Spark SQL, T-SQL, Oracle PL/SQL |
| **Storage & formats** | Delta Lake, Delta Sharing, Parquet, AWS S3 |
| **Platforms** | o9 Solutions, Databricks, Snowflake, Oracle Cloud Infrastructure |
| **Modeling & orchestration** | dbt, Delta Live Tables, Autoloader, Airflow |
| **Workflow** | Git, GitHub, Linux, VS Code |

**Languages:** Spanish (native) · English (professional) · German (conversational) · French (learning)

---

## Selected projects

**[dbt Databricks Retail Data Warehouse](https://github.com/Osvajorge/dbt-databricks-retail-data-warehouse)**
Multi-layered warehouse (bronze → silver → gold) built with dbt on Databricks, covering
data modeling, transformation, testing, and generated documentation.

**[Databricks Flights Data Warehouse](https://github.com/Osvajorge/databricks-flights-project)**
End-to-end pipeline with incremental ingestion via Autoloader, transformations in Delta
Live Tables, and a gold layer with dynamic dimension and fact builders producing a star schema.

**[E-commerce Product Analytics](https://github.com/Osvajorge/ecommerce-product-analytics)**
Analytics platform for product metrics and customer insights on a modern data stack —
dbt, Databricks, and Airflow.

**[World Cup Draw Simulator](https://github.com/Osvajorge/world-cup-draw-app)**
Interactive group-draw simulator implementing real tournament seeding and confederation
constraints.

**[LeetCode Interview Mastery](https://github.com/Osvajorge/LeetCode-Interview-Mastery)**
Structured practice repository for SQL, Python, and algorithms.

---

## GitHub activity

<div align="center">
  <img height="165em" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=osvajorge&theme=prussian&show_icons=true&hide_border=true&count_private=true&include_all_commits=true"/>
  <img height="165em" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=osvajorge&theme=prussian&show_icons=true&hide_border=true&layout=compact&hide=html,css,scss&langs_count=8"/>
</div>

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/osvajorge)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@osvajorge)

Open to conversations about data platform work, pipeline architecture, and
supply-chain analytics.
