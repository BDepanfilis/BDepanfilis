# Bradley DePanfilis — Data Analytics & Analytics Engineering

I build end-to-end data products: ingest → model → validate → ship (dashboards, docs, and apps). Strengths in **SQL**, **Python/R**, **dbt**, **DuckDB/BigQuery**, and **Power BI**, with a focus on **reproducibility, statistical rigor, and clear decision-making**.

**Core strengths (ATS):** SQL (CTEs, window fx, optimization) • Python (pandas, NumPy, statsmodels, scikit-learn, matplotlib/Plotly) • R (tidyverse, ggplot2, broom, sandwich/lmtest) • dbt Core • DuckDB, BigQuery, PostgreSQL • Streamlit, Altair • Power BI & Tableau • ELT/ETL • Dimensional modeling & star schema • Data quality testing • CI/CD (GitHub Actions) • A/B testing, causal inference, time-series, cohorts/LTV • REST APIs (FastAPI, SQLAlchemy, Pydantic) • Documentation & lineage

## Selected Projects

### Gen-Z CPI (2020–2025): Fixed vs. Chained Index vs BLS CPI-U
- Developed a reproducible ETL pipeline using **BigQuery SQL** and a **bash runner** to compute two consumer price indices (fixed-weight Laspeyres and chained Laspeyres) tailored to Gen-Z spending, validated against **BLS CPI-U**.  
- Deliverables: versioned CSVs, **GitHub Pages** site with **Plotly** visualizations, and a **Power BI** dashboard.  
- **Highlights:** Transparent methodology, normalized base (2020=1.00), cost-aware query design, and automated data processing for easy re-runs.  
- **Skills:** SQL (BigQuery), data pipeline development, data visualization, time-series analysis, index construction.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Gen-Z-CPI) • Live: [LIVE_URL](https://bdepanfilis.github.io/Gen-Z-CPI/) • Power BI: [LIVE_URL](https://app.powerbi.com/view?r=eyJrIjoiMDU5OWFhNDAtYWI2OC00MDQ5LTk1ZDMtYzU5ZGYyNmI3ZmNmIiwidCI6ImE4MjE2YzFlLTRkNjMtNDM1Mi04YzNiLTUwZmExZjE0NzViMSIsImMiOjZ9)

### Gender Wage Gap (2019–2024): Sequential Specs & Robust Inference
- Analyzed **CPS March ASEC** microdata to estimate the U.S. career gender wage gap using sequential regression models (baseline, education, personal/geo, household, singles).  
- Implemented **HC1 robust standard errors**, year-by-year trends, and publication-quality visualizations with **R/ggplot2**.  
- Deliverables: Modular **R scripts** (wrangle/analysis), CSV outputs, **GitHub Pages** site, and **Power BI** dashboard.  
- **Highlights:** Reproducible data wrangling, robust statistical modeling, and clear visualizations showing a persistent 21–24% gap (14% for singles).  
- **Skills:** Statistical modeling, R (tidyverse, broom, sandwich/lmtest), data visualization, data wrangling, regression analysis.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Gender-Wage-Gap-2019-2024) • Live: [LIVE_URL](https://bdepanfilis.github.io/Gender-Wage-Gap-2019-2024/) • Power BI: [LIVE_URL](https://app.powerbi.com/view?r=eyJrIjoiYWIyZGVmMjUtYzc3My00OTAzLTgzODQtZWMyMzFjZjYyMDEzIiwidCI6ImE4MjE2YzFlLTRkNjMtNDM1Mi04YzNiLTUwZmExZjE0NzViMSIsImMiOjZ9)

### Olist Analytics — Streamlit Dashboard
- Built an interactive e-commerce analytics dashboard using **Streamlit**, **DuckDB**, **Altair**, and **Pandas** on the Olist dataset, delivering metrics on revenue, AOV, customer cohorts, LTV, retention heatmaps, returns, and marketing ROI (ROAS).  
- Designed a two-repo architecture, fetching **DuckDB** artifacts from private GitHub Releases at runtime for secure, scalable data delivery.  
- **Highlights:** Optimized query caching, defensive data handling, and production-ready secrets management; serves ~180 days of data with snappy performance.  
- **Skills:** Analytics engineering, Python (Pandas, Altair), Streamlit, DuckDB, data visualization, ETL pipelines, cohort analysis, LTV modeling.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/olist-analytics-public) • Live: [LIVE_URL](https://olist-analytics-public.streamlit.app/)

### ecom-analytics-olist (dbt Project)
- Engineered a curated analytics warehouse using **dbt Core** to transform raw Olist e-commerce data into a star schema with staging, core dimensions/facts, and marts for sales, marketing ROI, cohorts, and returns quality.  
- Implemented data quality tests (**dbt_utils**, **dbt_expectations**), seeds for enrichment, and automated **dbt Docs** publishing to **GitHub Pages** for lineage and observability.  
- **Highlights:** Warehouse-agnostic workflow with **DuckDB** for local/CI and optional **BigQuery** execution with cost guards; demonstrates robust ELT and CI/CD integration.  
- **Skills:** Data engineering, dbt Core, SQL, DuckDB, BigQuery, data modeling, ELT pipelines, data quality testing, CI/CD.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/ecom-analytics-olist) • Live Docs: [LIVE_URL](https://bdepanfilis.github.io/ecom-analytics-olist)

### AB Uplift Analysis (Python)
- Created an end-to-end A/B testing pipeline for uplift modeling using the Criteo Uplift dataset, featuring power checks, causal effect estimates (diff-in-proportions, CUPAC, IPW/AIPW), and targeting via Qini/AUUC with a Top-K policy.  
- Engineered as a reproducible Python package with CLI entry point, deterministic seeds, and auto-generated reports/figures; includes covariate balance (SMDs) and propensity diagnostics.  
- **Highlights:** Narrative Jupyter Notebook with ROI appendix; supports data-driven marketing and product decisions.  
- **Skills:** Data analytics, Python (pandas, NumPy, statsmodels, scikit-learn, matplotlib), causal inference, A/B testing, statistical modeling, data visualization.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/ab-uplift-analysis)

### Bayesian Elo (Valorant)
- Developed a production-ready **Bayesian Elo system** in **Python** for Valorant teams, integrating player performance weighting (R².0 stats), Bayesian priors, time decay, regional bias, and API-driven match data ingestion.  
- Deployed for 2024–2025 VCT/VCL matches with 2M/monthly organic visitors; supports dynamic leaderboards and real-time updates.  
- **Highlights:** Modular design with **FastAPI**, **SQLAlchemy**, and **PostgreSQL**; integrates **Chart.js** and **Tailwind CSS** for visualizations.  
- **Skills:** Data engineering, Python (pandas, NumPy, FastAPI, SQLAlchemy, Pydantic), PostgreSQL, API development, Bayesian modeling, data visualization.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Valorant-Bayesian-Elo-System)

### Cake Chooser (Elo micro-app)
- Built a lightweight **GitHub Pages** app using **JavaScript** and a simple Elo system to rank cake preferences, demonstrating decision-making tools with a playful dataset.  
- **Highlights:** Clean UI, reproducible logic, and rapid deployment for stakeholder interaction.  
- **Skills:** Data analytics, JavaScript, data visualization, decision support systems.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Elo-Cake-Birthday) • Live: [LIVE_URL](https://bdepanfilis.github.io/Elo-Cake-Birthday/)

## Experience

**Analytics Projects for Local Businesses** — Conducted financial statement analysis, identified margin drivers, and performed forecasting to optimize supplier terms and support growth planning.  
**Intern, U.S. Green Chamber of Commerce** — Built a B2B sustainability supplier database; authored research briefs and presented data-driven findings to guide partner selection.

## Skills

**Data & Analytics**  
- **SQL (BigQuery)**: Window functions, CTEs, robust aggregation, cost-aware query optimization.  
- **Python**: pandas, NumPy, matplotlib/Plotly, statsmodels, scikit-learn for data processing, statistical modeling, and causal inference.  
- **R**: tidyverse, ggplot2, broom, sandwich/lmtest for regression analysis, robust standard errors, and visualization.  
- Statistical modeling: Linear/log models, robust SEs, time-series analysis, index construction, Bayesian modeling, A/B testing, cohort analysis, LTV modeling.  
- Reproducible workflows: Bash runners, structured repos, versioned outputs, data validation.

**Analytics Engineering & Data Engineering**  
- **dbt Core**: ELT pipeline development, data modeling (star schema), data quality testing (dbt_utils, dbt_expectations).  
- **DuckDB** and **BigQuery**: Warehouse-agnostic workflows, cost optimization, and scalable data processing.  
- **API Development**: FastAPI, SQLAlchemy, Pydantic for RESTful APIs and data integration.  
- **CI/CD**: GitHub Actions for automated testing, docs publishing, and deployment.  
- Data pipeline development, ETL/ELT processes, data warehousing, schema design.

**BI & Visualization**  
- **Power BI**, **Tableau**, **Altair**, **Plotly**, **ggplot2**: Story-driven visual design, interactive dashboards, audience-appropriate axes/scales, tooltips/annotations.  
- Web-friendly delivery: **GitHub Pages**, responsive iframes, Streamlit applications.

**Tooling & Practices**  
- **Git/GitHub**, **Markdown**, **CI/CD** pipelines, lightweight data validation (schema/na checks).  
- Cloud platforms: **GCP BigQuery**, secure asset publishing (no secrets in repo).  
- Project management: Modular codebases, clear READMEs, auditable outputs.

## Contact

- **LinkedIn:** https://www.linkedin.com/in/bradley-depanfilis/  
- **GitHub:** https://github.com/BDepanfilis  
- **Email:** bradleydepanfilis@gmail.com

---

### Notes for Reviewers
Repos are structured for quick digestion. If you’d like a private walkthrough of any project or a short Loom overview, I’m happy to share.
