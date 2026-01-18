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

**"I design AI pipelines and agents with clear performance metrics, focusing on the Why (the essence)."**  
I structure business problems into data flows and create impact through *hallucination control, cost efficiency, and operations automation*.

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=o2mandoo.o2mandoo)

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Agentic workflows, RAG/GraphRAG, memory optimization, data-driven decision automation
- 🧠 **Strength**: Define *why* a technology is needed first, then **design/validate with metrics**
- 🧩 **Collaboration**: Execute with a PM mindset, balancing goals/risks/resources (military officer experience)
- 🏗️ **Background**: Mechanical/piping design engineer → AI engineer

**Highlights**
- Reduced persona breakdown / hallucination via **GraphRAG + 3-tier memory**, optimizing tokens & cost
- Built an SQL-agent workflow for sales analysis + marketing automation, cutting **analysis→proposal** time to minutes
- Defined churn logically from data **without an explicit churn label**, improving predictive performance

---

## 💼 Featured Projects

### 1) 🧑‍🍳 AI Store Manager Agent (Sales Analytics & Marketing/Ops Automation) — In Progress
> Integrates POS/sales + weather/competition/trends to explain sales drops and automate influencer outreach & campaign execution

- **Goal**: Reduce intuition-based decisions and improve **marketing ROI + operational efficiency**
- **Key scope (planning/dev)**  
  - **Auto-explain sudden sales drops (internal + external data fusion)**  
  - **Discover/score rising influencers + generate outreach email drafts**  
  - Track Naver Place keyword rankings, analyze reviews/trends  
  - Ops automation: staff scheduling recommendations, P&L automation, inventory/purchase alerts
- **Workflow (example)**: Diagnose → Plan → Execute → Review → Recommend (ReAct loop)

**🔗 Links**
- (To be added) Repo / Demo

**🛠 Tech Stack (planned / in progress)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 2) 🗡️ Multi-Persona Chatbot (GraphRAG & 3-Tier Memory)
> A multi-turn chatbot that “remembers” relationships/events: hallucination control + cost optimization

- **Problem**: Longer conversations increase relationship errors/hallucinations and raise costs
- **Solution**  
  - Branch control with **GraphRAG** (graph-based retrieval for relations/events)  
  - **3-tier memory (Recent/Chunk Summary/User Memory)** to retrieve only what matters  
  - Router/Generator/Validator separation with **LangGraph orchestration**
- **Outcome (example)**  
  - Reduced token usage via hierarchical summarization while keeping long-context quality  
  - Balanced speed/cost with local sLLM + hosted APIs

**🔗 Links**
- (To be added) Repo / Demo

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

### 3) 🛒 Instacart Churn Definition & Prediction (Churn Modeling)
> Defined churn per customer purchase cycle for data **without an explicit churn label**, then built predictive models

- **Problem**: No ground-truth churn column + varying repurchase cycles per customer
- **Solution**  
  - Personalized churn definition using mean/STD of repurchase intervals  
  - XGBoost + SHAP to identify key drivers and propose actionable scenarios
- **Outcome (example)**: Improved F1 vs. a naive time-based churn rule

**🔗 Links**
- (To be added) Repo / Notebook

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-000000?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 4) 🤖 Multi-Agent RAG Search System
> Local-LLM-based multi-agent document search & QA system

**🎯 Overview**
- Parent–child agent structure for complex queries
- Semantic retrieval with vector DB
- Context preservation and agent collaboration
- Privacy-friendly local execution

**🛠 Tech Stack**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat-square&logoColor=white)

**📌 Key Features**
- Collaborative multi-agent query handling
- Embedding-based semantic search
- Multi-source document aggregation
- Local LLM (Ollama) for privacy

---

### 5) 📊 Car Preference & FAQ Data Analytics Dashboard
> Interactive visualization dashboard for business intelligence

**🎯 Overview**
- Real-time data collection and processing
- Business insight visualization via dashboards
- Automated report generation and distribution
- User-customizable dashboard components

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**📌 Key Features**
- Real-time visualization
- Multiple charts and graphs
- Filtering & search
- Auto report generation & download

---

## 🛠 Tech Stack
(Kept as-is from your original.)

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

### 📜 Certifications
- 🎓 **ADSP** (Associate Data Analytics) - ✅ Passed (2025.09.05)
- 🎓 **DASP** (Associate Data Architecture) - ✅ Passed (2025.10.24)

### 🎓 Education
- ✅ **AI/ML Bootcamp** (Data Analysis & LLM Applications)
- ✅ **SK Networks Family AI Camp (2025.05.20 - 2025.11.21)**
- 🎓 **B.S. in Refrigeration & Air Conditioning Engineering**

---

## 🌱 Interests

- LLM applications
- RAG / GraphRAG
- Multi-agent system architecture
- Vector DB optimization
- Real-time analytics & visualization

---

### 💡 *"I will keep learning and challenging myself to build the future with AI."*

#### *From Car Pipe Design to AI Innovation* 🚀

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=120&section=footer)
