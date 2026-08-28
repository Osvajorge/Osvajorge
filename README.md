# Jorge Guardado

**Data Engineer** · Barcelona, Spain

I build production data pipelines for enterprise supply chain planning. I work at
[Quantiqus](https://www.linkedin.com/company/quantiqus/) on an
[o9 Solutions](https://o9solutions.com) implementation for
[Mango](https://www.mango.com/), covering Merchandise Financial Planning (MFP) and
Assortment Planning (AP).

Before this, I spent five years as a Data Engineer at Oracle and TCS. That background
still shapes how I read query plans and debug execution behavior.

---

## What I work on

**Integration pipelines.** Medallion architecture (raw, normalized, planning layer)
built in PySpark. Data moves from Snowflake and Databricks into the o9 data lake through
Delta Sharing and staged file loads.

**Data modeling.** Delta Lake tables, incremental merges, slowly changing dimensions,
and dimensional models that feed OLAP cubes and live planning workspaces.

**Data quality.** Reconciliation and validation frameworks that catch drift between
source systems and the planning platform before the business does.

**Automation.** Scheduled jobs, CI pipelines, and AI assisted tooling that remove
repeated manual work from the delivery loop.

---

## Tech stack

| Area | Tools |
|---|---|
| **Processing** | PySpark, Python, pandas, NumPy |
| **Query** | SQL, Snowflake SQL, Spark SQL, T-SQL, Oracle PL/SQL |
| **Storage and formats** | Delta Lake, Delta Sharing, Parquet, AWS S3 |
| **Platforms** | o9 Solutions, Databricks, Snowflake, Cloudflare, Oracle Cloud Infrastructure |
| **Modeling and orchestration** | dbt, Delta Live Tables, Autoloader, Airflow, GitHub Actions |
| **Machine learning** | scikit-learn, XGBoost, probabilistic and time-series modeling, ensembling, backtesting and calibration |
| **AI assisted engineering** | Claude Code, Model Context Protocol (MCP) servers, custom agent skills, Hugging Face, local model deployment |
| **Testing** | pytest, Playwright, Vitest |
| **Workflow** | Git, GitHub, Linux, VS Code |

**Languages:** Spanish (native) · English (professional) · German (conversational) ·
French (learning)

---

## Selected projects

### [dbt Databricks Retail Data Warehouse](https://github.com/Osvajorge/dbt-databricks-retail-data-warehouse)

Multi-layered warehouse (bronze, silver, gold) built with dbt on Databricks. Covers data
modeling, transformation, testing, and generated documentation.

### [Databricks Flights Data Warehouse](https://github.com/Osvajorge/databricks-flights-project)

End to end pipeline with incremental ingestion through Autoloader, transformations in
Delta Live Tables, and a gold layer with dynamic dimension and fact builders that produce
a star schema.

### [E-commerce Product Analytics](https://github.com/Osvajorge/ecommerce-product-analytics)

Analytics platform for product metrics and customer insights on a modern data stack:
dbt, Databricks, and Airflow.

### [World Cup Draw Simulator](https://world-cup-draw-app.pages.dev)

Interactive group draw simulator built with React, Vite, and Tailwind CSS. Supports two
distribution modes, animated transitions, and shareable results. Deployed on Cloudflare
Pages. [Source](https://github.com/Osvajorge/world-cup-draw-app).

### [LeetCode Interview Mastery](https://github.com/Osvajorge/LeetCode-Interview-Mastery)

Structured practice repository for SQL, Python, and algorithms.

---

## GitHub activity

<div align="center">
  <img alt="Profile details" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=osvajorge&theme=github_dark"/>
</div>

<div align="center">
  <img alt="Repositories per language" height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=osvajorge&theme=github_dark"/>
  <img alt="Most committed language" height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=osvajorge&theme=github_dark"/>
</div>

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/osvajorge)

Open to conversations about data platform work, pipeline architecture, and supply chain
analytics.
