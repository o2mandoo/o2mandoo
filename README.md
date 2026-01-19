<p align="center">
  <a href="./README.md">한국어</a> ·
  <a href="./README.eng.md">English</a> ·
  <a href="./README.ja.md">日本語</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=200&section=header&text=Taemin%20Cho&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Developer%20%7C%20Data%20Engineer&descAlignY=55&descAlign=50" />
</div>

<div align="center">
  
### 👋 Welcome to My GitHub

**"Why(본질)에 집중해, 명확한 성능 지표로 AI 파이프라인과 에이전트를 설계합니다."**  
비즈니스 문제를 데이터 흐름으로 구조화하고, *환각 제어·비용 효율·운영 자동화*로 임팩트를 만듭니다.

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=o2mandoo.o2mandoo)

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Agentic Workflow, RAG/GraphRAG, Memory Optimization, 데이터 기반 의사결정 자동화
- 🧠 **Strength**: “기술이 왜 필요한지”를 먼저 정의하고, **지표 기반으로 설계/검증**
- 🧩 **Collaboration**: PM 관점 + 장교 복무 경험 기반으로 목표/리스크/리소스 균형을 맞추며 실행
- 🏗️ **Background**: 기계/배관 설계 엔지니어 경험 → AI 엔지니어 전향

**Highlights**
- GraphRAG + 3-Tier Memory로 **페르소나 붕괴/환각률 감소**, 토큰/비용 최적화
- SQL Agent 기반 매출 분석 + 마케팅 실행 자동화로 **분석→제안 시간을 분 단위로 단축**
- “이탈 컬럼이 없는 데이터”에서 **논리적 이탈 정의**를 만들고 예측 성능 개선

---

## 💼 Featured Projects

### 1) 🧑‍🍳 AI 점장 에이전트 (매출 분석 & 마케팅·운영 자동화 플랫폼) — 진행 중
> POS/매출 + 날씨/경쟁/트렌드를 통합 분석해 하락 원인을 설명하고, 인플루언서 컨택·캠페인 실행까지 자동화

- **목표**: 점주의 “감” 의존을 줄이고, **마케팅 ROI + 운영 효율**을 함께 올리는 의사결정 도구
- **주요 기능(기획/개발 범위)**  
  - **매출 급락 원인 자동 설명(내/외부 데이터 결합)**  
  - **라이징 인플루언서 발굴/스코어링 + 컨택 메일 초안 생성**  
  - 네이버 플레이스 **키워드 순위 추적**, 리뷰/트렌드 분석  
  - 운영 자동화: **직원 스케줄 추천**, **손익계산서(P&L) 자동화**, **재고·발주 알림**
- **운영 방식(예시)**: 현황 분석 → 계획 → 실행 → 검토 → 제안 루프(ReAct 기반)로 자동화

**🔗 Links**

**🛠 Tech Stack (planned / in progress)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 2) 🗡️ 멀티 페르소나 챗봇 (GraphRAG & 3-Tier Memory)
> 캐릭터 관계/사건을 “기억”하는 멀티턴 챗봇: 환각 제어 + 비용 효율 최적화

- **핵심 문제**: 턴이 길어질수록 관계 오류/환각 및 비용 급증
- **해결**  
  - **GraphRAG**로 관계/사건을 그래프 조회 기반으로 분기 제어  
  - **3-Tier Memory(Recent/Chunk Summary/User Memory)**로 필요한 기억만 인출  
  - Router/Generator/Validator 분리로 **LangGraph 오케스트레이션** 구성
- **성과 예시**  
  - 토큰 사용량 절감(계층 요약), 장기 대화 품질 유지  
  - 로컬 sLLM + 상용 API 조합으로 비용/속도 균형

**🔗 Links**
- Repo: https://github.com/o2mandoo/Graph-RAG-based-gamified-multi-persona-chatbot-SKN-Final-Project-

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

### 3) 🛒 Instacart 고객 이탈 정의 & 예측 (Churn Modeling)
> “이탈 컬럼이 없는 데이터”에서 고객별 구매 주기 기반으로 이탈을 정의하고 예측 모델링

- **핵심 문제**: 정답 라벨이 없는 데이터 + 고객별 구매 주기 편차
- **해결**  
  - 고객별 평균 재구매 주기와 표준편차로 **개인화 이탈 기준** 정의  
  - XGBoost + SHAP으로 핵심 요인 식별 및 실행 가능한 시나리오 제안
- **성과 예시**: 단순 기간 기준 대비 예측 성능(F1) 개선

**🔗 Links**
- Repo: https://github.com/o2mandoo/Instacart-customer-churn-prediction-and-prevention-strategy-Mini-Project-2-


**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-000000?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 4) 🤖 멀티에이전트 RAG 검색 시스템
> 로컬 LLM 기반 다중 에이전트 문서 검색 및 질의응답 시스템

**🎯 프로젝트 개요**
- Parent-Child 에이전트 구조로 복잡한 쿼리 처리
- Vector Database 기반 의미론적 문서 검색
- 컨텍스트 보존 및 에이전트 간 협업
- 로컬 환경에서 프라이버시 보장하며 실행

**🛠 Tech Stack**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat-square&logoColor=white)

**📌 주요 기능**
- 복잡한 쿼리를 여러 에이전트가 협업하여 처리
- 임베딩 기반 의미론적 검색 (Semantic Search)
- 다중 문서 소스에서 정보 통합
- 로컬 LLM(Ollama)으로 프라이버시 보장

**🔗 Links**
- Repo: https://github.com/o2mandoo/Lecture-based-RAG-learning-assistant-web-app-Mini-Project-4-Django-deployment-
---

### 5) 📊 자동차 선호도 및 FAQ 제공 데이터 분석 대시보드
> 비즈니스 인텔리전스를 위한 인터랙티브 시각화 대시보드

**🎯 프로젝트 개요**
- 실시간 데이터 수집 및 처리
- 대시보드를 통한 비즈니스 인사이트 시각화
- 자동 리포트 생성 및 배포
- 사용자 맞춤형 대시보드 구성

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**📌 주요 기능**
- 실시간 데이터 시각화
- 다양한 차트 및 그래프 제공
- 필터링 및 검색 기능
- 자동 리포트 생성 및 다운로드
**🔗 Links**
- Repo: https://github.com/o2mandoo/Korean-automobile-preference-data-analysis-and-company-specific-FAQ-system-Mini-Project-1-
---
### 6)  📚 SK Networks Family AI Camp 학습 기록
**🔗 Links**
- Record : https://www.notion.so/SKN-family-ai-camp-15-21aa65c2efb780378138e8125db1ff17?source=copy_link
- Repo: https://github.com/o2mandoo/Learning-records-from-SK-Networks-Family-AI-Camp

## 🛠 Tech Stack

### 📝 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### 🤖 AI & ML
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### 🌐 Backend & Frameworks
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)

### 💾 Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=for-the-badge&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### ☁️ DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Mac OS](https://img.shields.io/badge/MacOS-000000?style=for-the-badge&logo=apple&logoColor=white)

---

## 🏆 Certifications & Education

### 📜 자격증
- 🎓 **ADSP** (데이터분석 준전문가) - ✅ 25.09.05 합격
- 🎓 **DASP** (데이터아키텍처 준전문가) - ✅ 25.10.24 합격

### 🎓 교육 이력
- ✅ **AI/ML 부트캠프** 수료 (데이터분석 & LLM 활용)
- ✅ **SK Networks Family AI Camp (25.05.20 - 25.11.21)** 참여
- 🎓 **냉동공조공학 전공**

---

## 🌱 Interests

- LLM 응용
- RAG / GraphRAG
- Multi-Agent Architecture
- Vector DB 최적화
- 실시간 데이터 분석 & 시각화

---

### 💡 *"끊임없는 학습과 도전을 통해 AI로 미래를 만드는 개발자가 되겠습니다"*

#### *From Car Pipe Design to AI Innovation* 🚀

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=120&section=footer)
