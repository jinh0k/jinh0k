<!--
  GitHub Profile README — English is the source of truth.
  Korean interpretation lives in README.ko.md and must mirror this file's facts, numbers, and order.
-->

<div align="center">

[English](README.md) | [한국어](README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:203a43,100:2c5364&height=200&section=header&text=Jinho%20Kang&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Data%20Scientist%20%C2%B7%20ML%20Researcher&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3500&pause=800&color=4FC3F7&center=true&vCenter=true&width=700&lines=Building+ML+artifacts+that+support+decisions;Prediction%2C+forecasting%2C+scoring%2C+anomaly+detection;Explainable+by+design%2C+built+to+be+acted+on" alt="Typing SVG"/>

**Data Scientist — I build explainable ML artifacts that support real decisions.**

[![Email](https://img.shields.io/badge/jinho5080@yonsei.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jinho5080@yonsei.ac.kr)

<br/>

![Decision Support](https://img.shields.io/badge/Decision_Support-4FC3F7?style=flat-square&labelColor=203a43)
![Structured-Data ML](https://img.shields.io/badge/Structured--Data_ML-203a43?style=flat-square)
![Demand Forecasting](https://img.shields.io/badge/Demand_Forecasting-234b60?style=flat-square)
![Credit Scoring](https://img.shields.io/badge/Credit_Scoring-2c5364?style=flat-square)
![Anomaly Detection](https://img.shields.io/badge/Anomaly_Detection-234b60?style=flat-square)
![Explainable AI](https://img.shields.io/badge/Explainable_AI-2c5364?style=flat-square)

</div>

<br/>

## About

I work on structured-data machine learning — prediction, forecasting, credit scoring, and anomaly detection — with one goal in mind: turning a business problem into an explainable artifact that supports a real decision. I care less about a single high metric and more about whether the output can be trusted, explained, and acted on.

- Frame business questions as data and ML problems before modeling
- Own the full cycle — problem framing → data and feature design → modeling → validation → decision support
- Build for use: outputs are meant to be read, defended, and turned into decisions
- Value explainability, sound experiment design, and reproducible work
- Comfortable with financial and industrial data

<br/>

## Selected Impact

- First-author paper in APJIS (international, peer-reviewed) on AI-era electricity demand
- 3 peer-reviewed journal papers (APJIS + two domestic journals)
- 4× Grand Prize and 2× Encouragement Award across national and university data/AI competitions
- Top 5% (33rd of 698 teams), LG Aimers 5th — display-process anomaly detection
- International conference talk at SIBR 2025 (Osaka)
- Ongoing research results: F1 0.979 on explainable adversarial-prompt detection; 5.93% MAE reduction on weather-aware sales forecasting

<br/>

## Selected Projects and Research

### Explainable Credit Scoring — supports lending decisions

- **Problem** — Credit decisions must be accurate and justifiable to applicants and regulators; opaque scores are hard to contest or act on.
- **Contribution** — Co-developed a graph-based credit-scoring approach where the explanation is a first-class output, so each decision comes with a reviewable rationale.
- **Methodology** — Graph representation to capture relational structure that flat tabular models miss, paired with per-decision explanations.
- **Validation** — Selected for and demonstrated at the Financial Services Commission (FSC) D-Testbed regulatory sandbox.
- **Outcome** — Grand Prize, Korea Fintech Center Director's Award (2025.12).
- **Decision relevance** — A scoring artifact a credit officer can trust and defend, not just a number.

### AI-Era Electricity Demand Forecasting — supports capacity and energy planning

- **Problem** — Long-horizon electricity demand is increasingly driven by AI and cloud adoption, factors traditional demand models do not capture.
- **Contribution** — Modeled AI and cloud technology diffusion together with periodic demand features to produce longer-range forecasts usable for planning.
- **Methodology** — Combined technology-diffusion signals (GPT search volume, cloud-market size, EV adoption, data-center variables) with periodic features, then simulated the SSP585 scenario to 2045.
- **Outcome** — First-author paper in APJIS, Vol. 35 No. 4 (2025), pp. 933–954.
- **Decision relevance** — Gives planners a demand trajectory under AI-driven growth to support capacity and energy-policy decisions.

### Explainable Adversarial-Prompt Detection — supports content-safety review

<sub>Ongoing research · internal model name undisclosed</sub>

- Structured recurring manipulation patterns into 13 IMT-based concepts and decided on those concepts alone, so each flag carries human-reviewable evidence.
- Result: F1 0.979, above explainable baselines. Grand Prize, Yonsei community experiential-learning competition (2024.12).
- Decision relevance: gives a reviewer the reasoning behind each flag, supporting moderation decisions.

### Weather-Aware Sales Forecasting — supports scheduling and merchandising

<sub>Ongoing research · internal model name undisclosed</sub>

- Multimodal sales forecasting fusing lagged weather signals across roughly 100K live-commerce broadcasts, feeding a scheduling decision-support simulation.
- Result: MAE reduced by 5.93% (5-fold, ~100K records).
- Decision relevance: turns a forecast into a scheduling and merchandising decision aid.

### GEO Auditor Agent — supports content-optimization decisions

Parses web-page code to diagnose how citable a page is to AI search and points to specific fixes. Grand Prize, Korea Society for e-Business.

### Display-Process Anomaly Detection

Anomaly detection on display-manufacturing process data. Top 5% (33rd of 698 teams), LG Aimers 5th (2024.09).

<br/>

## How I Work

1. **Define the problem first.** Agree on what decision we are improving before building.
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

## Publications, Presentations, and Awards

![APJIS First Author](https://img.shields.io/badge/APJIS-First_Author-203a43?style=flat-square)
![Journal Papers ×3](https://img.shields.io/badge/Journal_Papers-%C3%973-234b60?style=flat-square)
![Grand Prize ×4](https://img.shields.io/badge/Grand_Prize-%C3%974-2c5364?style=flat-square)
![SIBR 2025 Speaker](https://img.shields.io/badge/SIBR_2025-Speaker-234b60?style=flat-square)
![LG Aimers Top 5%](https://img.shields.io/badge/LG_Aimers-Top_5%25-EE4C2C?style=flat-square)

**Journal Publications**

- Jinho Kang, Min-ho Song, So-Hyun Lee, Hee-Woong Kim. "Electricity Demand in the Age of AI and Cloud: Integrating Technology Diffusion and Periodic Features." *Asia Pacific Journal of Information Systems (APJIS)*, 35(4), 2025, pp. 933–954. **First author.**
- 강진호, 송민호, 이소현. "생성형 AI의 부작용 요인 도출과 대응방안 제안: 텍스트마이닝과 인터뷰 접근." *한국IT서비스학회지*, 24(1), 2025, pp. 109–128. **First author.**
- 허원진, 강진호, 이소현. "클러스터링 기법을 이용한 이륜차 사고의 특징 분류." *지식경영연구*, 25(1), 2024, pp. 217–233.

**Conference Presentation**

- Jinho Kang. "Structuring the Generative AI Function Space: A Clustered Use Case Analysis." *Society of Interdisciplinary Business Research Conference (SIBR 2025)*, Osaka, Japan, July 2025.
- 강진호 외. "미래 전력 수요 예측: AI·전기차 보급률·데이터센터 변수 활용." 한국지능정보시스템학회 추계학술대회, 2024.10.
- 강진호 외. "생성형 AI 부작용 요인 도출 및 대응방안 제안: 텍스트 마이닝 활용." 한국경영정보학회 춘계학술대회, 2024.05.
- 송민호, 강진호, 이소현. "ODR 서비스: 차량 지연 시 대기허용범위 확대를 위한 주요 요인 도출 — 텍스트 마이닝." 한국전자거래학회·한국스마트미디어학회 춘계학술대회, 2024.05.

**Awards and Competitions**

- **Grand Prize** — "TwinCept: factory AI that managers understand," Korea Digital Industry Society & Korea Smart Media Society 2026 Spring Student Idea Competition (2026.04).
- **Grand Prize** — Explainable graph-based XAI credit scoring, FSC D-Testbed, Korea Fintech Center Director's Award (2025.12).
- **Grand Prize** — Explainable adversarial-prompt detection, Yonsei community experiential-learning competition (2024.12).
- **Grand Prize** — Performance lifecycle prediction, 4th KOPIS Big Data Competition (2024.09).
- **Grand Prize** — GEO Auditor, Korea Society for e-Business.
- **Encouragement Award** — "FINZ: context-aware financial agent for the MZ generation," Korea Knowledge Management Society autumn student idea competition (2025.11).
- **Encouragement Award** — Generative-AI marketing proposal for small businesses (2024.11).
- **Top 5% (33rd of 698 teams)** — Display-process anomaly detection, LG Aimers 5th (2024.09).

<br/>

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jinh0k&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=percentile&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinh0k&layout=compact&hide_border=true&langs_count=8&title_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=jinh0k&style=flat-square&color=4fc3f7" alt="profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:203a43&height=120&section=footer" width="100%"/>
