<!--
  GitHub 프로필 README — 영어(README.md)가 원본(source of truth)입니다.
  이 한국어 문서는 영어 원문의 사실·수치·순서를 충실히 옮긴 해석본입니다.
-->

<div align="center">

[English](README.md) | [한국어](README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:203a43,100:2c5364&height=200&section=header&text=Jinho%20Kang&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Data%20Scientist%20%C2%B7%20ML%20Researcher&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3500&pause=800&color=4FC3F7&center=true&vCenter=true&width=700&lines=Building+ML+artifacts+that+support+decisions;Prediction%2C+forecasting%2C+scoring%2C+anomaly+detection;Explainable+by+design%2C+built+to+be+acted+on" alt="Typing SVG"/>

**Data Scientist — 실제 의사결정을 돕는 설명 가능한 ML 아티팩트를 만듭니다.**

[![Email](https://img.shields.io/badge/jinho5080@yonsei.ac.kr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jinho5080@yonsei.ac.kr)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=DjM_5hkAAAAJ&hl=en)

<br/>

![Decision Support](https://img.shields.io/badge/Decision_Support-4FC3F7?style=flat-square&labelColor=203a43)
![Structured-Data ML](https://img.shields.io/badge/Structured--Data_ML-203a43?style=flat-square)
![Demand Forecasting](https://img.shields.io/badge/Demand_Forecasting-234b60?style=flat-square)
![Credit Scoring](https://img.shields.io/badge/Credit_Scoring-2c5364?style=flat-square)
![Anomaly Detection](https://img.shields.io/badge/Anomaly_Detection-234b60?style=flat-square)
![Explainable AI](https://img.shields.io/badge/Explainable_AI-2c5364?style=flat-square)

</div>

<br/>

## 소개

정형 데이터 기반 머신러닝 — 예측, 수요예측, 신용평가, 이상 탐지 — 을 다루며, 목표는 하나입니다. 비즈니스 문제를 실제 의사결정을 돕는 설명 가능한 아티팩트로 바꾸는 것. 하나의 높은 지표보다, 그 결과를 신뢰하고 설명하고 실행에 옮길 수 있는지를 더 중요하게 봅니다.

- 모델링에 앞서 비즈니스 질문을 데이터·ML 문제로 구조화합니다
- 문제 정의 → 데이터·피처 설계 → 모델링 → 검증 → 의사결정 지원까지 전체 사이클을 수행합니다
- 쓰이기 위한 결과를 만듭니다 — 읽히고, 근거를 댈 수 있고, 의사결정으로 이어지도록
- 설명가능성, 견고한 실험 설계, 재현 가능한 작업을 중요하게 생각합니다
- 금융·산업 데이터를 다룹니다

<br/>

## 주요 성과

- APJIS 제1저자 논문 (국제, 동료 심사) — AI 시대의 전력 수요
- 동료 심사 학술지 논문 3편 (APJIS + 국내 학술지 2편)
- 전국 규모 및 대학 데이터·AI 공모전 최우수상 4회, 장려상 2회
- LG Aimers 5기 상위 5% (698팀 중 33위) — 디스플레이 공정 이상 탐지
- 국제 학술대회 발표 — SIBR 2025 (Osaka)
- 진행 중 연구 결과: 설명 가능한 적대적 프롬프트 탐지 F1 0.979, 날씨 정보 기반 판매 예측 MAE 5.93% 개선

<br/>

## 주요 프로젝트 및 연구

### 설명 가능한 신용평가 — 여신 의사결정 지원

- **문제** — 신용 판단은 정확할 뿐 아니라 신청자와 규제 기관에 정당화될 수 있어야 합니다. 불투명한 점수는 반박하거나 활용하기 어렵습니다.
- **기여** — 설명을 사후 부가물이 아닌 일차 산출물로 다루는 그래프 기반 신용평가 방식을 공동 개발해, 판단마다 검토 가능한 근거가 함께 나오게 했습니다.
- **방법론** — 평면적 정형 모델이 놓치는 관계 구조를 포착하기 위해 그래프 표현을 사용하고, 판단마다 근거를 제시했습니다.
- **검증** — 금융위원회(FSC) D-테스트베드 규제 샌드박스에 선정·실증했습니다.
- **성과** — 최우수상, 한국핀테크지원센터장상 (2025.12).
- **의사결정 의의** — 심사역이 신뢰하고 근거를 댈 수 있는 평가 아티팩트, 단순한 점수가 아닙니다.

### AI 시대의 전력 수요 예측 — 설비·에너지 계획 지원

- **문제** — 장기 전력 수요는 점점 AI·클라우드 확산의 영향을 받지만, 전통적 수요 모델은 이 요인을 반영하지 못합니다.
- **기여** — AI·클라우드 기술 확산과 주기적 수요 특성을 함께 모델링해, 계획 수립에 쓸 수 있는 장기 예측을 만들었습니다.
- **방법론** — 기술 확산 신호(GPT 검색량, 클라우드 시장 규모, 전기차 보급률, 데이터센터 변수)와 주기적 특성을 결합하고, SSP585 시나리오를 2045년까지 시뮬레이션했습니다.
- **성과** — APJIS 제1저자 논문, Vol. 35 No. 4 (2025), pp. 933–954.
- **의사결정 의의** — AI 주도 성장 아래의 수요 궤적을 제시해 설비·에너지 정책 의사결정을 지원합니다.

### 설명 가능한 적대적 프롬프트 탐지 — 콘텐츠 안전 검토 지원

<sub>진행 중 연구 · 내부 모델명 비공개</sub>

- 반복되는 조작 방식을 IMT 기반 13개 개념으로 구조화하고 그 개념만을 근거로 판단해, 탐지마다 사람이 검토할 수 있는 근거를 남깁니다.
- 결과: F1 0.979, 설명 가능한 baseline 상회. 연세대학교 지역사회 경험학습 공모전 최우수상 (2024.12).
- 의사결정 의의: 검토자에게 각 탐지의 근거를 제공해 조치 판단을 지원합니다.

### 날씨 정보를 활용한 판매량 예측 — 편성·머천다이징 지원

<sub>진행 중 연구 · 내부 모델명 비공개</sub>

- 약 10만 건의 라이브커머스 방송에 기상 시차 정보를 결합한 멀티모달 판매 예측으로, 편성 의사결정 지원 시뮬레이션에 연결됩니다.
- 결과: MAE 5.93% 개선 (5-fold, 약 10만 건).
- 의사결정 의의: 예측을 편성·머천다이징 의사결정 보조 도구로 바꿉니다.

### GEO Auditor Agent — 콘텐츠 최적화 의사결정 지원

웹페이지 코드를 파싱해 해당 페이지가 AI 검색에 인용될 가능성을 진단하고, 수정 지점을 짚어 줍니다. 한국전자거래학회 대상.

### 디스플레이 공정 이상 탐지

디스플레이 제조 공정 데이터의 이상 탐지. LG Aimers 5기 (2024.09).

<br/>

## 일하는 방식

1. **문제부터 정의합니다.** 어떤 의사결정을 개선하려는지 합의하고 시작합니다.
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

## 논문 · 발표 · 수상

![APJIS First Author](https://img.shields.io/badge/APJIS-First_Author-203a43?style=flat-square)
![Journal Papers ×3](https://img.shields.io/badge/Journal_Papers-%C3%973-234b60?style=flat-square)
![Grand Prize ×4](https://img.shields.io/badge/Grand_Prize-%C3%974-2c5364?style=flat-square)
![SIBR 2025 Speaker](https://img.shields.io/badge/SIBR_2025-Speaker-234b60?style=flat-square)
![LG Aimers 5th](https://img.shields.io/badge/LG_Aimers-Top_5%25-EE4C2C?style=flat-square)

**학술지 논문**

- Jinho Kang, Min-ho Song, So-Hyun Lee, Hee-Woong Kim. "Electricity Demand in the Age of AI and Cloud: Integrating Technology Diffusion and Periodic Features." *Asia Pacific Journal of Information Systems (APJIS)*, 35(4), 2025, pp. 933–954. **제1저자.**
- 강진호, 송민호, 이소현. "생성형 AI의 부작용 요인 도출과 대응방안 제안: 텍스트마이닝과 인터뷰 접근." *한국IT서비스학회지*, 24(1), 2025, pp. 109–128. **제1저자.**
- 허원진, 강진호, 이소현. "클러스터링 기법을 이용한 이륜차 사고의 특징 분류." *지식경영연구*, 25(1), 2024, pp. 217–233.

**학술대회 발표**

- Jinho Kang. "Structuring the Generative AI Function Space: A Clustered Use Case Analysis." *Society of Interdisciplinary Business Research Conference (SIBR 2025)*, Osaka, Japan, July 2025.
- 강진호 외. "미래 전력 수요 예측: AI·전기차 보급률·데이터센터 변수 활용." 한국지능정보시스템학회 추계학술대회, 2024.10.
- 강진호 외. "생성형 AI 부작용 요인 도출 및 대응방안 제안: 텍스트 마이닝 활용." 한국경영정보학회 춘계학술대회, 2024.05.
- 송민호, 강진호, 이소현. "ODR 서비스: 차량 지연 시 대기허용범위 확대를 위한 주요 요인 도출 — 텍스트 마이닝." 한국전자거래학회·한국스마트미디어학회 춘계학술대회, 2024.05.

**수상 및 공모전**

- **최우수상** — "관리자가 이해하는 공장 AI: TwinCept", 한국디지털산업학회·한국스마트미디어학회 2026 춘계 대학(원)생 아이디어 공모전 (2026.04).
- **최우수상** — 설명 가능한 그래프 기반 XAI 신용평가, 금융위원회 D-테스트베드, 한국핀테크지원센터장상 (2025.12).
- **최우수상** — 설명 가능한 적대적 프롬프트 탐지, 연세대학교 지역사회 경험학습 공모전 (2024.12).
- **최우수상** — 공연 수명주기 예측, 제4회 KOPIS 빅데이터 공모전 (2024.09).
- **대상** — GEO Auditor, 한국전자거래학회.
- **장려상** — "MZ세대를 위한 맥락 인지형 금융 Agent: FINZ", 한국지식경영학회 추계학술대회 대학(원)생 아이디어 공모전 (2025.11).
- **장려상** — 생성형 AI를 활용한 소상공인 마케팅 방안 제안 (2024.11).
- **LG Aimers 5기 수료** — 디스플레이 공정 이상 탐지, LG Aimers 5기 (2024.09).

<br/>

## GitHub 통계

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jinh0k&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=percentile&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinh0k&layout=compact&hide_border=true&langs_count=8&title_color=4FC3F7&text_color=c9d1d9&bg_color=0d1117"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=jinh0k&style=flat-square&color=4fc3f7" alt="profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:203a43&height=120&section=footer" width="100%"/>
