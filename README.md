# Bradley DePanfilis — Data Analyst

I’m a recent graduate focused on **analytical rigor, reproducibility, and clear storytelling**. I build end-to-end data projects: gather/clean, analyze/model, and ship **trustworthy, documented outputs** (dashboards, reports, Pages sites). Comfortable across **SQL (BigQuery)**, **Python/R**, and **BI tools**.

## Selected Projects

### Gen-Z CPI (2020–2025): Fixed vs. Chained Index vs BLS CPI-U
- Built a reproducible pipeline in **BigQuery SQL** with a guarded **bash runner** to create two indices (fixed-weight Laspeyres and annually reweighted chained) and validate them against **BLS CPI-U**.  
- Deliverables: versioned CSVs, a clean **GitHub Pages** site with Plotly charts, and an optional **Power BI** embed.
- **Highlights:** clear methodology; normalized base (2020=1.00); transparent comparison; easy re-runs.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Gen-Z-CPI) • Live: [LIVE_URL](https://bdepanfilis.github.io/Gen-Z-CPI/) • Power BI: [LIVE_URL
](https://app.powerbi.com/view?r=eyJrIjoiMDU5OWFhNDAtYWI2OC00MDQ5LTk1ZDMtYzU5ZGYyNmI3ZmNmIiwidCI6ImE4MjE2YzFlLTRkNjMtNDM1Mi04YzNiLTUwZmExZjE0NzViMSIsImMiOjZ9)

### Gender Wage Gap (2019–2024): Sequential Specs & Robust Inference
- Reproduced March CPS (ASEC) extracts, built an analysis sample, and estimated the adjusted female wage gap across **sequential model specs** (baseline → education → personal/geo → household; singles).  
- Implemented **HC1 robust standard errors**, year-by-year effects, and publication-quality figures (R/ggplot2).  
- Deliverables: **README**, **R scripts** split by wrangle/analysis, and **dashboard PNGs** embedded in the repo site/Power BI.
- Repo: [REPO_URL](https://github.com/BDepanfilis/Gender-Wage-Gap-2019-2024) • Live: [LIVE_URL](https://bdepanfilis.github.io/Gender-Wage-Gap-2019-2024/) Power BI: [LIVE_URL](https://app.powerbi.com/view?r=eyJrIjoiYWIyZGVmMjUtYzc3My00OTAzLTgzODQtZWMyMzFjZjYyMDEzIiwidCI6ImE4MjE2YzFlLTRkNjMtNDM1Mi04YzNiLTUwZmExZjE0NzViMSIsImMiOjZ9)

### Bayesian Elo (Valorant)
- **Python** project that ingests match data via API and produces **dynamic player/team ratings**.  
- Designed for stability vs. volatility trade-offs; outputs updated leaderboards.
- User traffic is ~500K / Month, 20+ Million total
- Repo: [REPO_URL](https://github.com/BDepanfilis/Valorant-Bayesian-Elo-System)

### Cake Chooser (Elo micro-app)
- Lightweight **GitHub Pages** app using an Elo system to rank alternatives—playful demo of turning a small dataset into a decision tool.  
- Repo: [REPO_URL](https://github.com/BDepanfilis/Elo-Cake-Birthday) • Live: [LIVE_URL](https://bdepanfilis.github.io/Elo-Cake-Birthday/)

## Experience

**Analytics Projects for Local Businesses** — financial statement review, margin drivers, and basic forecasting to inform supplier terms and growth planning.  
**Intern, U.S. Green Chamber of Commerce** — contributed to a B2B sustainability supplier database; wrote short research briefs and presented findings to support partner selection.

## Skills

**Data & Analytics**  
- **SQL (BigQuery)**, window functions, CTEs, robust aggregation; cost-aware query design  
- **Python** (pandas, NumPy, matplotlib/Plotly, statsmodels), **R** (tidyverse, ggplot2, broom, sandwich/lmtest)  
- Statistical modeling (linear/log models, robust SEs), time-series basics, index construction  
- Reproducible workflows: **bash** runners, structured repos, versioned outputs

**BI & Visualization**  
- **Power BI**, Tableau; Story-first visual design, audience-appropriate axes/scales, tooltips/annotations  
- Web-friendly delivery (GitHub Pages, responsive iframes)

**Tooling & Practices**  
- Git/GitHub, Markdown; basic CI concepts and lightweight data validation (schema/na checks)  
- Cloud familiarity: **GCP BigQuery**; publish/read public assets safely (no secrets in repo)

## How I Work

- **Reproducible by default:** clear READMEs, runnable scripts, and environment-free visualizations.  
- **Explain the “so what”:** every chart accompanies the decision context or implication.  
- **Iterate with feedback:** keep code modular (wrangle vs. analysis), and keep outputs auditable.

## What I’m Building Next

- A **product analytics** case study (funnels, cohorts, retention, segmentation) with production-quality SQL.  
- A **clean A/B analysis** in Python (design, power, randomization checks, CUPED/stratification, decision memo).

## Contact

- **LinkedIn:** https://www.linkedin.com/in/bradley-depanfilis/  
- **GitHub:** https://github.com/BDepanfilis  
- **Email:** bradleydepanfilis@gmail.com

---

### Notes for Reviewers
Repos are structured for quick digestion (top-level README, `/sql`, `/scripts`, `/data/external`, `/outputs`, `/docs`). If you’d like a private walkthrough of any project or a short Loom overview, I’m happy to share.
