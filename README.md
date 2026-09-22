<h1 align="center">Jordan Roesch</h1>

<p align="center">
  <b>Statistician &amp; Data Analyst</b> · M.S. Statistics (Biostatistics) @ San Diego State University<br>
  Public health research · Statistical modeling · End-to-end data workflows
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/SAS-0766D1?style=flat-square&logo=sas&logoColor=white" alt="SAS">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" alt="XGBoost">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX">
</p>

---

## About

I'm a statistician and data analyst in San Diego working at the intersection of **public health research** and **applied machine learning**. My day job is epidemiological data: cleaning, validating, modeling, and making the results legible to people who don't write code. My repos show the engineering side of that skill set: leak-safe ML pipelines, schema-validated ETL, and self-updating dashboards.

- 🔬 **Data Analyst**, SDSU Research Foundation — large-scale epidemiological datasets, recruitment &amp; enrollment tracking databases, EDC validation and QA, regression modeling with multidisciplinary research teams
- 🤖 **AI Training Specialist (Data Science &amp; Mathematics)**, Handshake AI — evaluating and ranking model responses, annotating technical prompts
- 🎓 **M.S. Statistics, Biostatistics concentration**, SDSU (expected May 2028) · **B.A. Mathematics &amp; Statistics**, Vassar College
- 📄 Co-author on peer-reviewed research from the **LUNA-E randomized clinical trial**, presented at the American Diabetes Association
- 🧠 Currently deepening: causal inference, Bayesian workflow, and production ML tooling

---

## Toolbox

**Languages**
`Python` `R` `SQL` `SAS` `Java` `C` `OCaml`

**Statistical methods**
Linear &amp; logistic regression · Generalized Estimating Equations (GEE) · Propensity score matching · Bayesian modeling (JAGS) · Random forests · MLE / method-of-moments / MVUE estimation · Cross-validation &amp; probability calibration

**Machine learning**
scikit-learn · XGBoost · Optuna · MLflow · SHAP · Leak-safe feature engineering · Computer vision (YOLOv8, BoT-SORT)

**Data engineering &amp; workflow**
Prefect · Pydantic · DuckDB · Parquet / JSONL · GitHub Actions · ETL pipeline design · EDC data validation

**Visualization &amp; tooling**
Plotly Dash · Chart.js · R Markdown · RStudio · Git · Excel · LaTeX

---

## Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[Expected-Metrics-ML](https://github.com/jroesch-droid/Expected-Metrics-ML)** | Production-style expected-goals (xG) system. Rolling averages and encodings are rebuilt **inside each CV fold** so nothing leaks; tuned and tracked end to end with an emphasis on calibration and reproducible lineage. | `scikit-learn` `XGBoost` `Optuna` `MLflow` |
| **[Sports-ETL-Engine](https://github.com/jroesch-droid/Sports-ETL-Engine)** | Retry-safe ingestion pipeline with strict schema validation, quarantine of bad records, idempotent upserts, and OLAP marts (standings, scoring leaders). | `Prefect 3` `Pydantic v2` `DuckDB` |
| **[Binge-Drinking-Health](https://github.com/jroesch-droid/Binge-Drinking-Health)** | Logistic regression study of factors associated with binge drinking using 2022 BRFSS data (n ≈ 102,635) — mental health, physical health, income, emotional support, life satisfaction. | `R` `logistic regression` |
| **[2024-Lion-Football-Stats](https://github.com/jroesch-droid/2024-Lion-Football-Stats)** | Predicts NFL game outcomes from early-season data, comparing Bayesian multiple linear regression, logistic regression, and a fully Bayesian model on a deliberately data-limited problem. | `R` `JAGS` `Bayesian inference` |

---

## More Repositories

<details>
<summary><b>Machine learning &amp; data engineering</b></summary>

<br>

- **[Expected-Metrics-ML](https://github.com/jroesch-droid/Expected-Metrics-ML)** — leak-safe xG modeling with Optuna tuning, MLflow tracking, and calibration analysis.
- **[Sports-ETL-Engine](https://github.com/jroesch-droid/Sports-ETL-Engine)** — Prefect 3 orchestration, Pydantic v2 contracts, DuckDB marts, quarantine for malformed records.
- **[Computer-Vision-Tracking](https://github.com/jroesch-droid/Computer-Vision-Tracking)** — player and ball tracking in sports video with YOLOv8 + BoT-SORT; frame-by-frame streaming for memory efficiency; derives velocities, trajectories, and zone-based event flags; exports JSONL/Parquet.

</details>

<details>
<summary><b>Statistical modeling &amp; inference</b></summary>

<br>

- **[Binge-Drinking-Health](https://github.com/jroesch-droid/Binge-Drinking-Health)** — public health regression modeling on 2022 BRFSS data.
- **[2024-Lion-Football-Stats](https://github.com/jroesch-droid/2024-Lion-Football-Stats)** — Bayesian vs. frequentist comparison on limited in-season data.
- **[NYC-Market-Value](https://github.com/jroesch-droid/NYC-Market-Value)** — multiple linear regression on NYC Dept. of Finance condo data (2012–2018); gross square footage and gross income per square foot emerge as strong predictors, with full assumption checking.
- **[German-Tank-Problem](https://github.com/jroesch-droid/German-Tank-Problem)** — recreation of the WWII estimation problem, comparing MLE, method of moments, and the MVUE that the Allies actually used.

</details>

<details>
<summary><b>Dashboards &amp; automation</b></summary>

<br>

- **[mlb_dashboard](https://github.com/jroesch-droid/mlb_dashboard)** — interactive MLB analytics dashboard in Plotly Dash; XGBoost game-outcome classifier trained on 13,000+ games (2019–2026) with 16 engineered features (rolling win %, run differential, head-to-head), explained with SHAP.
- **[Baseball-Interactive-Dashboard](https://github.com/jroesch-droid/Baseball-Interactive-Dashboard)** — self-updating Padres analytics site. A nightly GitHub Actions job pulls from Baseball-Reference, FanGraphs, and Baseball Savant into a JSON file that a static Chart.js front end reads — no server required.

</details>

---

## Publications &amp; Presentations

- **"Team-Based and Virtual Diabetes Care for Latino Adults: The LUNA-E Randomized Clinical Trial"** — co-authored, peer-reviewed.
- **"Integrating Behavioral, Medical, and E-health Care to Improve Glycemic Management among Latino Adults: Results from the LUNA-E Randomized Clinical Trial"** — conference presentation, American Diabetes Association.
- **"Effects of an Integrated Behavioral, Medical, and E-Health Care Intervention on Psychological and Diabetes Distress among Latino Patients with Type 2 Diabetes: The LUNA-E Randomized Controlled Trial"** — in preparation.

---


## Get in Touch

<p align="center">
  <a href="mailto:jorroe10@gmail.com"><img src="https://img.shields.io/badge/Email-jorroe10%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/jordan-roesch-77169528a"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center"><sub>Open to conversations about biostatistics, causal inference, and sports analytics.</sub></p>
