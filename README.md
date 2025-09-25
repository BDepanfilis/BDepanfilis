# Bradley DePanfilis — Data Analytics & Data Science 

### Gen-Z CPI (2020–2025): Fixed vs. Chained Index vs BLS CPI-U
- Developed a reproducible ETL pipeline using **BigQuery SQL** to compute two consumer price indices (fixed-weight Laspeyres and chained Laspeyres) tailored to Gen-Z spending, validated against **BLS CPI-U**.  
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
- Developed a production-ready **Bayesian team rating system** in for Valorant teams displayed on **vlr.gg**, aggregating player stats into team skills with hierarchical priors for uncertainty, incorporating margin-of-win scaling, map adjustments, meta updates, roster resets, time decay, and regional biases to enable accurate 1:1 cross-regional predictions for Tier 1 & 2 teams across global regions. . 
- Deployed for 2024–2025 VCT/VCL matches with >28M total visitors; supports dynamic leaderboards and real-time updates.  
- **Highlights:** Modular design with **FastAPI**, **SQLAlchemy**, and **PostgreSQL**; deployed via **Docker** on **AWS**; integrates **Chart.js** for visualizations.  
- **Skills:** Data engineering, Docker, AWS, Python (pandas, NumPy, FastAPI, SQLAlchemy, Pydantic), PostgreSQL, API development, Bayesian modeling, data visualization.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Valorant-Bayesian-Elo-System)

### Cake Chooser (Elo micro-app)
- Built a lightweight **GitHub Pages** app using **JavaScript** and a simple Elo system to rank cake preferences, demonstrating decision-making tools with a playful dataset.  
- **Highlights:** Clean UI, reproducible logic, and rapid deployment for stakeholder interaction.  
- **Skills:** Data analytics, JavaScript, data visualization, decision support systems.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Elo-Cake-Birthday) • Live: [LIVE_URL](https://bdepanfilis.github.io/Elo-Cake-Birthday/)

## Contact

- **LinkedIn:** https://www.linkedin.com/in/bradley-depanfilis/  
- **GitHub:** https://github.com/BDepanfilis  
- **Email:** bradleydepanfilis@gmail.com

---

### Notes for Reviewers
Repos are structured for quick digestion. If you’d like a private walkthrough of any project or a short Loom overview, I’m happy to share.
