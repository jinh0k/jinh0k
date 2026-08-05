<!--
  GitHub 프로필 README — 영어(README.md)가 원본(source of truth)입니다.
  이 한국어 문서는 영어 원문의 사실·수치·순서를 충실히 옮긴 해석본입니다.
-->

<div align="center">

[English](README.md) | [한국어](README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:203a43,100:2c5364&height=200&section=header&text=Jinho%20Kang&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Data%20Scientist%20%C2%B7%20ML%20Researcher&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3500&pause=800&color=4FC3F7&center=true&vCenter=true&width=680&lines=Framing+business+problems+as+ML+problems;Explainable%2C+testable%2C+decision-ready+models;From+problem+framing+to+something+you+can+ship" alt="Typing SVG"/>

**Data Scientist — 비즈니스 문제를 구조화되고, 설명 가능하며, 검증 가능한 머신러닝 솔루션으로 바꿉니다.**

<br/>

![Structured-Data ML](https://img.shields.io/badge/Structured--Data_ML-203a43?style=flat-square)
![Demand Forecasting](https://img.shields.io/badge/Demand_Forecasting-234b60?style=flat-square)
![Credit Scoring](https://img.shields.io/badge/Credit_Scoring-2c5364?style=flat-square)
![Anomaly Detection](https://img.shields.io/badge/Anomaly_Detection-234b60?style=flat-square)
![Explainable AI](https://img.shields.io/badge/Explainable_AI-4FC3F7?style=flat-square&labelColor=2c5364)

</div>

<br/>

## 소개

정형 데이터 기반 머신러닝을 중심으로 예측, 신용평가, 수요예측, 이상 탐지를 다룹니다. 하나의 높은 지표보다, 모델이 올바른 문제를 중심으로 설계되었는지, 그 판단을 설명할 수 있는지, 그리고 그 결과가 실제 의사결정을 바꾸는지를 더 중요하게 봅니다.

- 모델링에 앞서 비즈니스 질문을 데이터·ML 문제로 구조화합니다
- 문제 정의 → 데이터·피처 설계 → 모델링 → 검증 → 활용까지 전체 사이클을 수행합니다
- 모델 정확도와 함께 비용, 활용 가능성, 의사결정 효과를 같이 평가합니다
- 설명가능성, 실험 설계, 인과적 검증, 재현 가능한 작업을 중요하게 생각합니다
- 금융·산업 데이터를 다루며, 복잡한 문제를 설명 가능하고 실행 가능한 형태로 바꿉니다

<br/>

## 주요 성과

- APJIS 제1저자 등재 논문 — AI 시대의 전력 수요를 다룬 동료 심사 논문
- 금융위원회 D-테스트베드 최우수상 — 설명 가능한 신용평가 (2025)
- 전국 규모 데이터·AI 공모전 최우수상 4회, 그리고 학회 대상 1회
- LG Aimers 5기 상위 5% (698팀 중 33위) — 산업 공정 이상 탐지
- 종료·보관된 연구 결과: 설명 가능한 적대적 프롬프트 탐지 F1 0.979, 날씨 정보 기반 판매 예측 MAE 5.93% 개선

<br/>

## 주요 프로젝트 및 연구

### 그래프 기반 설명 가능한 신용평가

- **문제** — 신용 판단은 정확해야 할 뿐 아니라 신청자와 규제 기관에 정당화될 수 있어야 합니다. 불투명한 점수는 반박하거나 활용하기 어렵습니다.
- **기여** — 설명을 사후 부가물이 아닌 일차 산출물로 다루는 그래프 기반 신용평가 방식을 설계했습니다.
- **방법론** — 평면적 정형 모델이 놓치는 관계 구조를 포착하기 위해 그래프 표현을 사용하고, 판단마다 근거를 제시했습니다.
- **검증** — 금융위원회 D-테스트베드(규제 샌드박스 실증)에 선정·실증했습니다.
- **성과** — 최우수상, 한국핀테크지원센터장상 (2025).
- **의의** — 신용 리스크, 이상거래 탐지 등 예측력과 설명력을 동시에 요구하는 의사결정에 직접 적용됩니다.

### AI 시대의 전력 수요 예측

- **문제** — 장기 전력 수요는 점점 AI·클라우드 확산의 영향을 받지만, 전통적 수요 모델은 이 요인을 반영하지 못합니다.
- **기여** — AI·클라우드 성장을 수요 요인 후보로 설정하고, 예측에 반영하기 전에 실제로 유효한 신호를 담고 있는지 검증했습니다.
- **방법론** — Double Machine Learning(DML)으로 교란 요인을 통제하며 GPT 검색량과 클라우드 시장 규모의 효과를 검증한 뒤, 검증된 요인을 반영하고 SSP585 시나리오를 2045년까지 시뮬레이션했습니다.
- **검증** — DML을 통한 인과적 검증 후 시나리오 시뮬레이션.
- **성과** — APJIS 제1저자 논문 게재 (Vol. 35 No. 4, 2025, pp. 933–954).
- **의의** — 상관과 실제로 쓸 수 있는 신호를 의사결정에 반영하기 전에 구분하는 인과-예측 워크플로를 보여줍니다.

### GEO Auditor Agent

웹페이지 코드를 파싱해 해당 페이지가 AI 검색에 인용될 가능성을 진단하고, 수정 지점을 짚어 줍니다. 한국전자거래학회 대상.

### FINZ: 맥락 인지형 금융 Agent

MZ세대를 위해 설계한 맥락 인지형 금융 어시스턴트. 한국지식경영학회 장려상.

<br/>

## 일하는 방식

1. **문제부터 정의합니다.** 무엇을 개선하려는지 합의하고 시작합니다.
2. **근거 있게 설계합니다.** 구조를 왜 그렇게 잡았는지 설명할 수 있어야 합니다.
3. **만든 것을 평가합니다.** 하나의 종합 점수가 아니라 설계 요소별 기여를 확인합니다.
4. **AI와 함께 만들되, 검증 후 씁니다.** Claude Code와 Codex로 실험하되, 생성된 코드는 데이터 분포·실행 조건·평가지표를 확인한 뒤에만 사용합니다.

<br/>

## 기술 역량

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

## 논문 및 수상

![APJIS First Author](https://img.shields.io/badge/APJIS-First_Author-203a43?style=flat-square)
![Grand Prize ×4](https://img.shields.io/badge/Grand_Prize-%C3%974-2c5364?style=flat-square)
![SIBR 2025 Speaker](https://img.shields.io/badge/SIBR_2025-Speaker-234b60?style=flat-square)
![LG Aimers Top 5%](https://img.shields.io/badge/LG_Aimers-Top_5%25-EE4C2C?style=flat-square)

- **논문** — *Electricity Demand in the Age of AI and Cloud*, APJIS Vol. 35 No. 4 (2025), pp. 933–954. 제1저자.
- **발표** — SIBR 2025 (Osaka): *Structuring the Generative AI Function Space*.
- **최우수상** — 금융위원회 D-테스트베드, 한국핀테크지원센터장상 (2025), 설명 가능한 신용평가.
- **대상** — 한국전자거래학회 (GEO Auditor).
- **최우수상 4회** — 전국 규모 데이터·AI 공모전 (KOPIS 빅데이터, 적대적 프롬프트 탐지, TwinCept 등).
- **장려상** — 한국지식경영학회 (FINZ).
- **상위 5%** — LG Aimers 5기, 698팀 중 33위, 산업 공정 이상 탐지.

<br/>

## 종료된 연구

**설명 가능한 적대적 프롬프트 탐지 연구**
<sub>RIP · 종료·보관된 연구 · 내부 모델명 비공개 · 현재 유지보수하지 않음</sub>

- 반복되는 조작 방식을 IMT 기반 13개 개념으로 구조화하고 그 개념만을 근거로 판단해, 예측마다 사람이 검토할 수 있는 근거를 남겼습니다.
- 결과: F1 0.979, 설명 가능한 baseline을 상회.

**날씨 정보를 활용한 판매량 예측 연구**
<sub>RIP · 종료·보관된 연구 · 내부 모델명 비공개 · 현재 유지보수하지 않음</sub>

- 약 10만 건의 라이브커머스 방송에 기상 시차 정보를 결합한 멀티모달 판매 예측과 편성 의사결정 지원 시뮬레이션.
- 결과: MAE 5.93% 개선 (5-fold, 약 10만 건).

<br/>

## 연락처 및 GitHub 통계

<div align="center">

[![Email](https://img.shields.io/badge/jinho5080@yonsei.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jinho5080@yonsei.ac.kr)

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jinh0k&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=percentile&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinh0k&layout=compact&hide_border=true&langs_count=8&title_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=jinh0k&style=flat-square&color=4fc3f7" alt="profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:203a43&height=120&section=footer" width="100%"/>
