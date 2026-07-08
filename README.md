<h1 align="center">안녕하세요, 박형건입니다 👋</h1>

<p align="center">
  <b>분석은 의사결정으로 끝나야 한다고 믿는 데이터 분야 취업 지망생</b><br/>
  가천대학교 응용통계학과 · 컴퓨터공학 복수전공
</p>

<p align="center">
  <i>데이터를 보기 전에 문제를 먼저 의심하고, 가설을 세운 뒤 통계로 검증하고,<br/>
  그 결과가 현장에서 실제로 쓰일 수 있는지까지 확인하는 것을 분석의 기본 자세로 삼고 있습니다.<br/>
  현재는 다양한 도메인을 탐색하며 데이터 분야의 시야를 넓혀가고 있습니다.</i>
</p>

<p align="center">
  <a href="mailto:afs35331@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-afs35331-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Gachon_Univ.-Applied_Statistics_%2B_CS-005BAC?style=flat&logo=graduation-cap&logoColor=white"/>
</p>

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)

**데이터 처리**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

**머신러닝**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-4B8BBE?style=flat&logo=python&logoColor=white)

**딥러닝**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**시각화**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=flat&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat&logo=looker&logoColor=white)

**도구**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📂 Projects

### 🔔 성동구 소상공인 경영위기 조기경보 시스템
> **2025 빅콘테스트 AI데이터 분석분야** · 학과 학술제 최우수상 · P-실무 프로젝트 A+

폐업률 0.72%의 극단적 불균형 환경에서 **LightGBM 위험 등급 탐지**와 **EWS 동종 업종 비교**를 병렬 구조로 결합한 조기경보 시스템 개발.  
Temporal Decay 피처 엔지니어링 · SHAP 예측 근거 분해 · 3단계 검증 파이프라인 · Streamlit 실시간 대시보드 배포.

| 지표 | 값 |
|------|-----|
| LightGBM CV AUC | **0.798** |
| Lift@5% | **7.3x** |
| Temporal Holdout (2023→2024) | AUC 0.611, Z = 4.55σ (p < 0.001) |

[![GitHub](https://img.shields.io/badge/GitHub-bigcontest--2025--ews-181717?style=flat&logo=github)](https://github.com/Broogun/bigcontest-2025-ews)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://bigcontest-2025-ews-5yrcwa6beml2fdp7czwez9.streamlit.app)
[![Report](https://img.shields.io/badge/최종_보고서-PDF-blue?style=flat&logo=adobeacrobatreader)](https://github.com/Broogun/bigcontest-2025-ews/raw/main/docs/보고서_성동구_소상공인_경영위기_조기경보_시스템.pdf)

---

### 📈 BDA 학습자 수료 예측 AI 경진대회
> **데이콘** · 733팀 중 **26위 (상위 3.5%)**

Train/Test 기수 간 분포 불일치 환경에서 L1 Distance 기반 변수 안정성 분석으로 일반화 가능한 신호만 선별.  
확률 임계값 대신 순위 기반 선발(Top-k)으로 Public 43위 → Private 26위 (+17등) 달성.

| 지표 | 값 |
|------|-----|
| Public F1 | 0.44897 (43위) |
| Private F1 | 0.41071 (26위) |
| Rule 기여 | +0.065 (ML 0.384 → 0.449) |

[![GitHub](https://img.shields.io/badge/GitHub-dacon--bda2--completion--prediction-181717?style=flat&logo=github)](https://github.com/Broogun/dacon-bda2-completion-prediction)
[![Portfolio](https://img.shields.io/badge/포트폴리오-PDF-blue?style=flat&logo=adobeacrobatreader)](https://github.com/Broogun/dacon-bda2-completion-prediction/raw/main/docs/BDA_학습자_수료_예측_AI_경진대회_포트폴리오.pdf)

---

