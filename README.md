<h1 align="center">Hey 👋 I'm Shashank Rawat</h1>
<h3 align="center">B.Tech AI/ML · Building at the intersection of LLMs, Multi-Agent Systems & Real-Time Pipelines</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/shashank-rawat-2768272ab"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:rawatshashank32@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=LitFix0.LitFix0" alt="visitors"/>
</p>

---

## 🧠 About Me

- 🎓 B.Tech AI/ML · Dr. Akhilesh Das Gupta Institute, New Delhi
- 🔭 Currently building: **LLM Gateway** — production-grade API gateway for multiple LLM providers
- 🚀 Open to: **GenAI Engineer · AI Agent Developer · LLM Engineer · Backend AI Engineer** roles
- 🏗️ I ship end-to-end — from architecture to deployment
- ⚡ Fun fact: Fine-tuned Whisper on Hindi speech with a 4GB GPU and beat baseline by 26 WER points

---

## 🚀 Featured Projects

### 🤖 [Research Autopilot](https://github.com/LitFix0/Research-Autopilot)
> Fully automated multi-agent AI research system — 5 specialized CrewAI agents (Planner, 3 Searchers, Synthesizer, Critic) powered by Groq LLaMA 3.3 70B decompose queries, retrieve live web data via Tavily, and produce cited markdown reports in ~27 seconds. Critic-driven retry loop ensures quality without human intervention. React dashboard + FastAPI backend + SQLite persistence.

`CrewAI` `Groq` `LLaMA 3.3 70B` `Tavily` `FastAPI` `React` `SQLite` `LiteLLM`

---

### 🔍 [AI Code Review Agent](https://github.com/LitFix0/AI_CODE_REVIEWER) · *[Live Demo](https://aicodereviewer-cgd6nbbjdkq8dbttnihrjo.streamlit.app/)*
> Autonomous agentic pipeline: clones any GitHub repo → structurally parses Python, Rust & JavaScript → sends chunks to **LLaMA 3.3 70B via Groq** → returns confidence-scored, severity-rated review comments on a Streamlit dashboard. Dispatcher-pattern registry makes adding a new language a single file change.

`Python` `Groq` `LLaMA 3.3 70B` `AST` `Streamlit` `GitPython`

---

### ⚡ [KafkaPulse 2.0](https://github.com/LitFix0/KAFKA-PULSE)
> Real-time news intelligence platform. Producer fetches live articles → Apache Kafka streams to dual consumers → VADER sentiment pipeline stores to MongoDB → embedding consumer indexes 384-dim vectors in ChromaDB → Groq-hosted LLaMA enables conversational RAG Q&A → live React dashboard with sentiment analytics and source-grounded chat. 6 backend services, single command startup.

`Apache Kafka` `ChromaDB` `SentenceTransformers` `Groq` `MongoDB` `FastAPI` `React` `Docker`

---

### 🔧 [LLM Gateway](https://github.com/LitFix0/LLM-Gateway)
> Production-grade API gateway for OpenAI, Claude, Gemini & Groq — Redis-backed caching, rate limiting, provider health monitoring, automatic retry/fallback, and smart routing strategies (round-robin, least latency, lowest cost). Full observability via Prometheus metrics and live Grafana dashboards. PostgreSQL usage tracking with real per-model cost calculation.

`FastAPI` `PostgreSQL` `Redis` `Prometheus` `Grafana` `Docker Compose` `SQLAlchemy` `Alembic`

---

### 🎙️ [Whisper Hindi ASR Fine-tune](https://github.com/LitFix0/whisper-hindi-asr)
> Fine-tuned `openai/whisper-small` on IndicVoices Hindi dataset. **WER dropped from 67.36% → 40.47% (↓26.89 pp)** on FLEURS benchmark — trained on an RTX 3050 4GB laptop GPU using FP16 mixed precision and gradient checkpointing.

`Whisper` `HuggingFace` `PyTorch` `IndicVoices` `ASR` `Fine-tuning`

---

### 🧳 [Luggage Intel](https://github.com/LitFix0/LUGGAGE-INTEL)
> End-to-end competitive intelligence pipeline scraping 3,900+ Amazon India reviews across 6 brands and 60+ products via Playwright. Multi-stage NLP pipeline combining VADER sentiment, aspect-based keyword extraction, and price-aware value scoring — visualized in an interactive React dashboard with brand comparison and sentiment heatmaps.

`Playwright` `VADER` `NLTK` `React` `Recharts` `Python`

---

### 🤖 [AutoStream AI Agent](https://github.com/LitFix0/AutoStream-AI-Agent) · [RAGBrain](https://github.com/LitFix0/RAGBrain) · [Doc Chat](https://github.com/LitFix0/DOC-CHAT)
> More LLM-powered tools — conversational lead capture agent, local RAG document assistant, and intelligent document chat.

---

## 🛠️ Tech Stack

**LLM & GenAI**

![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=for-the-badge&logo=robot&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Monitoring & Infra**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=LitFix0&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LitFix0&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LitFix0/LitFix0/output/github-contribution-grid-snake-dark.svg" alt="snake animation"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=LitFix0&theme=tokyo-night&hide_border=true"/>
</p>

---

<p align="center"><i>"Ship things. Break things. Fix things. Repeat."</i></p>
