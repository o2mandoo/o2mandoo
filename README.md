<p align="center">
  <a href="./README.md">한국語</a> ·
  <a href="./README.eng.md">English</a> ·
  <a href="./README.ja.md">日本語</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=200&section=header&text=Taemin%20Cho&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Developer%20%7C%20Data%20Engineer&descAlignY=55&descAlign=50" />
</div>

<div align="center">

### 👋 GitHubへようこそ

**「Why（本質）に集中し、明確な性能指標に基づいてAIパイプラインとエージェントを設計します。」**  
ビジネス課題をデータフローとして構造化し、*ハルシネーション制御・コスト効率・運用自動化*でインパクトを生み出します。

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=o2mandoo.o2mandoo)

</div>

---

## 🙋‍♂️ 私について（About Me）

- 🎯 **Focus**: Agentic Workflow、RAG/GraphRAG、Memory Optimization、データ駆動の意思決定自動化
- 🧠 **Strength**: 「なぜその技術が必要か」を先に定義し、**指標ベースで設計・検証**
- 🧩 **Collaboration**: PM視点＋将校としての経験を活かし、目標／リスク／リソースのバランスを取りながら推進
- 🏗️ **Background**: 機械／配管設計エンジニア → AIエンジニアへ転向

**Highlights**
- GraphRAG + 3-Tier Memoryで **ペルソナ崩壊／ハルシネーション率を低減**、トークン／コストを最適化
- SQL Agentによる売上分析＋マーケ運用の自動化で **分析→提案までの時間を分単位に短縮**
- 「離脱カラムがないデータ」から **論理的な離脱定義**を設計し、予測性能を改善

---

## 💼 注目プロジェクト（Featured Projects）

### 1) 🧑‍🍳 AI店長エージェント（売上分析 & マーケ・運用自動化プラットフォーム）— 進行中
> POS/売上 + 天気/競合/トレンドを統合分析し、売上低下の原因を説明。インフルエンサーのコンタクト～施策実行まで自動化

- **目的**: 店長の「勘」依存を減らし、**マーケROI + 運用効率**を同時に高める意思決定ツール
- **主な機能（企画/開発範囲）**  
  - **売上急落の原因を自動説明（内外データの統合）**  
  - **成長中インフルエンサーの発掘/スコアリング + 連絡メール草案の生成**  
  - Naver Placeの **キーワード順位トラッキング**、レビュー/トレンド分析  
  - 運用自動化：**スタッフシフト推薦**、**損益計算書（P&L）自動化**、**在庫・発注アラート**
- **運用フロー（例）**: 現状分析 → 計画 → 実行 → 振り返り → 提案（ReActループで自動化）

**🔗 Links**

**🛠 Tech Stack（planned / in progress）**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

**📌 主な機能**
- 加盟店情報および売上の統合管理
- マーケティングキャンペーンの自動生成（ターゲティング基盤）
- ダッシュボードによるリアルタイム成果モニタリング
- 自動レポート生成および配信

---

### 2) 🗡️ マルチペルソナチャットボット（GraphRAG & 3-Tier Memory）
> キャラクターの関係/事件を「記憶」するマルチターンチャットボット：ハルシネーション制御 + コスト効率の最適化

- **課題**: ターンが長くなるほど関係の誤り/ハルシネーションが増え、コストも増大
- **解決**  
  - **GraphRAG**で関係/事件をグラフ検索ベースで分岐制御  
  - **3-Tier Memory（Recent/Chunk Summary/User Memory）**で必要な記憶のみを抽出  
  - Router/Generator/Validatorを分離し、**LangGraphでオーケストレーション**
- **成果例**  
  - トークン消費を削減（階層要約）、長期対話品質の維持  
  - ローカルsLLM + 商用APIの併用で速度/コストをバランス

**🔗 Links**

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

### 3) 🛒 Instacart 顧客離脱の定義 & 予測（Churn Modeling）
> 「離脱カラムがないデータ」から、顧客ごとの購入周期を基に離脱を定義し予測モデルを構築

- **課題**: 正解ラベルがないデータ + 顧客ごとの購入周期のばらつき
- **解決**  
  - 顧客別の平均再購入周期と標準偏差から **個別最適な離脱基準**を定義  
  - XGBoost + SHAPで主要因子を可視化し、実行可能なシナリオを提案
- **成果例**: 単純な期間基準より予測性能（F1）を改善

**🔗 Links**

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-000000?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 4) 🤖 マルチエージェント RAG 検索システム
> ローカルLLM基盤のマルチエージェント文書検索・QAシステム

**🎯 プロジェクト概要**
- Parent-Child エージェント構造で複雑なクエリを処理
- ベクトルDBによる意味検索（Semantic Search）
- コンテキスト保持とエージェント協調
- ローカル実行でプライバシーを確保

**🛠 Tech Stack**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat-square&logoColor=white)

**📌 主な機能**
- 複雑なクエリを複数エージェントが協調して処理
- 埋め込みベースの意味検索（Semantic Search）
- 複数ソース文書の情報統合
- ローカルLLM（Ollama）でプライバシーを確保

---

### 5) 📊 自動車の嗜好・FAQ提供 データ分析ダッシュボード
> ビジネスインテリジェンスのためのインタラクティブ可視化ダッシュボード

**🎯 プロジェクト概要**
- リアルタイムデータ収集・処理
- ダッシュボードでビジネスインサイトを可視化
- 自動レポート生成・配信
- ユーザー別にカスタマイズ可能な構成

**🛠 Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**📌 主な機能**
- リアルタイム可視化
- 多様なチャート/グラフ
- フィルタリング/検索
- レポート生成・ダウンロード

---

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

## 📂 次のプロジェクト計画（Next Project Plans）

---

## 🏆 資格 & 学歴（Certifications & Education）

### 📜 資格（取得済み / 進行中）
- 🎓 **ADSP**（データ分析 準専門家）- ✅ 2025.09.05 合格
- 🎓 **DASP**（データアーキテクチャ 準専門家）- ✅ 2025.10.24 合格

### 🎓 教育履歴
- ✅ **AI/ML ブートキャンプ** 修了（データ分析 & LLM活用）
  - 主な学習：Python / Django / FastAPI / LangChain / Vector DB
  - プロジェクトベースで実務力を習得
  
- ✅ **SK Networks Family AI Camp（2025.05.20 - 2025.11.21）** 参加
  - AI基礎理論 + 実戦プロジェクト

- 🎓 **冷凍空調工学 専攻**（Engineering Background）
  - 自動車配管設計・シミュレーション経験

---

## 🌱 Interests

### 🎯 関心分野
- Large Language Models（LLM）応用
- Retrieval-Augmented Generation（RAG）
- Multi-Agent System Architecture
- Vector Database 最適化
- リアルタイム分析・可視化
- GraphRAG 構築および性能改善

---

### 💡 *「継続的な学習と挑戦を通じて、AIで未来を創る開発者を目指します」*

#### *From Car Pipe Design to AI Innovation* 🚀

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=120&section=footer)
