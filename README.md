<!--
  GitHub Profile README — English is the source of truth.
  Korean interpretation lives in README.ko.md and must mirror this file's facts, numbers, and order.
-->

<div align="center">

[English](README.md) | [한국어](README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:203a43,100:2c5364&height=200&section=header&text=Jinho%20Kang&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Data%20Scientist%20%C2%B7%20ML%20Researcher&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3500&pause=800&color=4FC3F7&center=true&vCenter=true&width=680&lines=Framing+business+problems+as+ML+problems;Explainable%2C+testable%2C+decision-ready+models;From+problem+framing+to+something+you+can+ship" alt="Typing SVG"/>

**Data Scientist — I turn business problems into structured, explainable, and testable machine-learning solutions.**

</div>

<br/>

## About

I work on structured-data machine learning with a focus on prediction, credit scoring, demand forecasting, and anomaly detection. I care less about a single high metric and more about whether a model is framed around the right problem, whether its decisions can be explained, and whether the result changes a real decision.

- Frame business questions as data and ML problems before modeling
- Own the full cycle — problem framing → data and feature design → modeling → validation → use
- Weigh cost, usability, and decision impact alongside model accuracy
- Value explainability, experiment design, causal validation, and reproducible work
- Comfortable with financial and industrial data, and with making complex problems explainable and actionable

<br/>

## Selected Impact

- First-author, peer-reviewed publication in APJIS on AI-era electricity demand
- Grand Prize, Financial Services Commission D-Testbed — explainable credit scoring (2025)
- 4× Grand Prize in national data and AI competitions, plus a society-level Grand Prize
- Top 5% (33rd of 698 teams), LG Aimers 5th — industrial process anomaly detection
- Archived research results: F1 0.979 on explainable adversarial-prompt detection; 5.93% MAE reduction on weather-aware sales forecasting

<br/>

## Selected Projects and Research

### Graph-based Explainable Credit Scoring

- **Problem** — Credit decisions must be accurate and justifiable to applicants and regulators; opaque scores are hard to contest or act on.
- **Contribution** — Built a graph-based credit-scoring approach that treats explanation as a first-class output rather than a post-hoc add-on.
- **Methodology** — Used a graph representation to capture relational structure that flat tabular models miss, paired with per-decision explanations.
- **Validation** — Selected for and demonstrated at the Financial Services Commission D-Testbed (regulatory sandbox pilot).
- **Outcome** — Grand Prize, Korea Fintech Center Director's Award (2025).
- **Relevance** — Applies directly to credit risk, fraud, and any decision that must be both predictive and explainable.

### AI-Era Electricity Demand Forecasting

- **Problem** — Long-horizon electricity demand is increasingly shaped by AI and cloud adoption, drivers that traditional demand models do not capture.
- **Contribution** — Framed AI and cloud growth as candidate demand drivers and tested whether they carry usable signal before adding them to a forecast.
- **Methodology** — Applied Double Machine Learning (DML) to validate the effect of GPT search volume and cloud-market size while controlling for confounders, then integrated the validated drivers and simulated the SSP585 scenario to 2045.
- **Validation** — Causal validation via DML, followed by scenario simulation.
- **Outcome** — First-author paper published in APJIS (Vol. 35 No. 4, 2025, pp. 933–954).
- **Relevance** — Demonstrates a causal-to-forecast workflow that separates correlation from usable signal before it drives a decision.

### GEO Auditor Agent

Parses web-page code to diagnose how citable a page is to AI search, and points to specific fixes. Grand Prize, Korea Society for e-Business.

### FINZ: Context-Aware Financial Agent

A context-aware financial assistant designed for younger (MZ) users. Encouragement Award, Korea Knowledge Management Society.

<br/>

## How I Work

1. **Define the problem first.** Agree on what we are improving before building.
2. **Design with reasons.** Be able to explain why the structure is what it is.
3. **Evaluate what is built.** Check contribution per design element, not one aggregate score.
4. **Build with AI, verify before use.** Run experiments with Claude Code and Codex, but ship generated code only after checking data distribution, run conditions, and metrics.

<br/>

## Technical Capabilities

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**ML, Statistics, and Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logoColor=white)

</div>

<br/>

## Publications and Awards

- **Publication** — *Electricity Demand in the Age of AI and Cloud*, APJIS Vol. 35 No. 4 (2025), pp. 933–954. First author.
- **Talk** — SIBR 2025 (Osaka): *Structuring the Generative AI Function Space*.
- **Grand Prize** — Financial Services Commission D-Testbed, Korea Fintech Center Director's Award (2025), explainable credit scoring.
- **Grand Prize** — Korea Society for e-Business (GEO Auditor).
- **4× Grand Prize** — national data and AI competitions, including KOPIS Big Data, adversarial prompt detection, and TwinCept.
- **Encouragement Award** — Korea Knowledge Management Society (FINZ).
- **Top 5%** — LG Aimers 5th, 33rd of 698 teams, industrial process anomaly detection.

<br/>

## Archived Research

**Explainable Adversarial-Prompt Detection Research**
<sub>RIP · Archived research · Internal model name intentionally undisclosed · No longer maintained</sub>

- Structured recurring manipulation patterns into 13 IMT-based concepts and decided on those concepts alone, so each prediction is backed by human-reviewable evidence.
- Result: F1 0.979, above explainable baselines.

**Weather-Aware Sales Forecasting Research**
<sub>RIP · Archived research · Internal model name intentionally undisclosed · No longer maintained</sub>

- Multimodal sales forecasting fusing lagged weather signals across roughly 100K live-commerce broadcasts, with a scheduling decision-support simulation.
- Result: MAE reduced by 5.93% (5-fold, ~100K records).

<br/>

## Contact and GitHub Statistics

<div align="center">

[![Email](https://img.shields.io/badge/jinho5080@yonsei.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jinho5080@yonsei.ac.kr)

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jinh0k&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=percentile&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinh0k&layout=compact&hide_border=true&langs_count=8&title_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=jinh0k&style=flat-square&color=4fc3f7" alt="profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:203a43&height=120&section=footer" width="100%"/>
