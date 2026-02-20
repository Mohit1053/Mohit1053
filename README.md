<h1 align="center">Hi, I'm Mohit</h1>

<p align="center">
  <b>AI Product Manager</b> &middot; B.Tech CS + AI @ IIIT-Delhi<br/>
  Building production AI systems &mdash; from voice agents to quantitative trading platforms
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohit1005"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mohit21542@iiitd.ac.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## Top Projects

### 1. Enterprise Voice AI Platform *(private &mdash; proprietary)*

Production conversational AI system that automates outbound sales, support, and retention calls with human-like voice interactions at scale.

| Metric | Value |
|--------|-------|
| Voice-to-voice latency (P95) | **<700ms** (21% under budget) |
| ASR accuracy (Hindi + English) | **>95%** |
| Deployment approaches | **3** &mdash; Cloud APIs, 100% Local (offline), NVIDIA PersonaPlex |
| Microservices | **15** (voice gateway, ASR, TTS, NLU, policy engine, analytics, etc.) |
| Concurrent call capacity | **1,000** |
| Training data | **36,000+ call transcripts**, 25K fine-tuning conversations |

**Architecture:** SIP/WebRTC telephony &rarr; Silero VAD &rarr; Deepgram/Whisper ASR &rarr; XState conversation state machine &rarr; GPT-4o/Claude/Ollama LLM chain (with circuit breakers) &rarr; ElevenLabs/Coqui TTS &rarr; policy engine &rarr; compliance layer (HIPAA, GDPR, PII redaction)

**Stack:** TypeScript, Node.js, XState, WebSocket, Deepgram, Whisper, ElevenLabs, Coqui XTTS, Silero VAD, PostgreSQL, Redis, Pinecone, Docker

---

### 2. Indian Market Intelligence Platform *(private &mdash; proprietary)*

Enterprise-grade system combining Agentic RAG, fundamental scoring, backtesting, and smart portfolio rebalancing for Indian equities.

| Module | Details |
|--------|---------|
| Agentic RAG | 5 specialized agents (Planner &rarr; Retriever &rarr; Reasoning &rarr; Verification &rarr; Reporting), Neo4j knowledge graph, multi-modal RAG |
| Fundamental Scoring | 14-metric weighted system (0&ndash;100 scale) &mdash; ROE, ROCE, P/E, P/B, D/E, Current Ratio, etc. |
| Backtesting | 131,333 validated price records, 49 NIFTY50 companies (2015&ndash;2025), 35+ cyclical patterns |
| Smart Rebalancing | Up to 95% transaction cost reduction vs traditional rebalancing |

**Stack:** Python, LangChain, Neo4j, FastAPI, React, Flask, Pandas, NumPy

---

### 3. Stock Prediction & Quant Research

ML-powered stock prediction with deep learning models and quantitative research tools for Indian markets.

<table>
<tr><td width="50%">

**[stock-prediction-engine](https://github.com/Mohit1053/stock-prediction-engine)** *(private)*

- **350+ technical indicators** per stock (momentum, trend, volatility, volume)
- **6 LSTM model versions** &mdash; basic &rarr; stacked &rarr; bidirectional &rarr; attention &rarr; ensemble &rarr; production
- Automated **BUY/SELL signal generation** with confidence scores
- 100 experiment notebooks with full EDA and training pipelines

</td><td width="50%">

**[indian-stock-backtesting](https://github.com/Mohit1053/indian-stock-backtesting)**

- Dual-engine platform: **fundamental scoring** (Nifty 50, 14 metrics) + **technical analysis** (2,600+ stocks, 105+ indicators)
- Smart rebalancing with up to **95% cost reduction**
- Flask APIs + interactive Chart.js dashboards
- 5 dividend yield strategies with thesis reports

</td></tr>
</table>

**Also:** [Fundamental_Indicators](https://github.com/Mohit1053/Fundamental_Indicators) &mdash; professional toolkit for NIFTY50/500 fundamental analysis with 14-metric scoring, Flask APIs, and interactive dashboards

**Stack:** Python, PyTorch, LSTM, XGBoost, Pandas, Flask, Chart.js

---

### 4. RAG & LLM Systems

End-to-end retrieval-augmented generation pipelines and intelligent conversational agents.

<table>
<tr><td width="33%">

**[Cement-Concall-RAG](https://github.com/Mohit1053/Cement-Concall-RAG)**

RAG over cement industry earnings calls &mdash; 13 companies, 56 transcripts, 4,185 vector chunks. Auto-downloads from Screener.in, indexes with ChromaDB, queries via Streamlit UI. Pre-built analysis tasks for growth, profitability, cost, and market dynamics.

</td><td width="33%">

**[user-chatbot-langgraph](https://github.com/Mohit1053/user-chatbot-langgraph)**

LangGraph conversational agent with persistent memory, Google Gemini integration, and stateful multi-turn conversations.

</td><td width="33%">

**[techtransfer-chatbot-v2](https://github.com/Mohit1053/techtransfer-chatbot-v2)**

RAG chatbot for intellectual property analysis &mdash; processes research papers and tech transfer knowledge bases.

</td></tr>
</table>

**Stack:** Python, LangChain, LangGraph, ChromaDB, Pinecone, OpenAI, Gemini, Streamlit, FastAPI

---

### 5. Web Automation & Data Engineering

Production automation frameworks and financial data pipelines processing hundreds of thousands of operations.

<table>
<tr><td width="50%">

**[web-automation-framework](https://github.com/Mohit1053/web-automation-framework)**

Production-grade toolkit built from deploying **500K+ form submissions** &mdash; stealth browser control with fingerprint evasion (6 rotation surfaces), 4 IP rotation strategies (Tor, USB dongles, router reset, proxy pool), multi-LLM content generation with persona engine, and honeypot detection.

</td><td width="50%">

**Other Pipelines** *(private)*

- **Financial Data Pipelines** &mdash; Gmail API broker email extraction, recommendations scraping, factsheet downloads, portfolio analysis
- **Multi-LLM Content Pipeline** &mdash; bulk constrained text generation with browser automation, local GPU inference (Qwen2.5), and Colab notebooks
- **Exotel-to-Notion ETL** &mdash; call data sync to Notion + Google Sheets

</td></tr>
</table>

**Stack:** Python, Selenium, Tor, OpenAI, Claude, Ollama, AWS SQS, n8n

---

## Other Public Projects

| Project | What it does |
|---------|--------------|
| [classify-image-objects](https://github.com/Mohit1053/classify-image-objects) | FastAPI image classification with CLIP + BLIP + DETR ensemble |
| [object-detect-deploy](https://github.com/Mohit1053/object-detect-deploy) | Real-time YOLOv8 object detection deployed via Flask |
| [coupon-recommender-xgboost](https://github.com/Mohit1053/coupon-recommender-xgboost) | XGBoost coupon tier classifier for High/Mid/Low discount optimization |
| [Article-Summary-Insights](https://github.com/Mohit1053/Article-Summary-Insights) | Multi-agent financial article analysis with investment scoring |
| [Humanizer](https://github.com/Mohit1053/Humanizer) | Multi-prompt AI text humanizer to reduce detection scores |
| [NLP_Project](https://github.com/Mohit1053/NLP_Project) | Hindi-English code-mixed text classification (TF-IDF + BERT) |
| [speech-sentiment-api](https://github.com/Mohit1053/speech-sentiment-api) | Whisper STT + sentiment analysis API |
| [rocket-flight-controller](https://github.com/Mohit1053/rocket-flight-controller) | Rocket flight simulation with PID controller |
| [propensity](https://github.com/Mohit1053/propensity) | XGBoost propensity scoring for user conversion prediction |
| [text-summarizer-nlp](https://github.com/Mohit1053/text-summarizer-nlp) | Extractive + abstractive text summarization |

---

## Tech Stack

**AI/ML:** PyTorch, Transformers, LangChain, LangGraph, LSTM, XGBoost, CLIP, YOLO, Whisper, RAG, Reinforcement Learning

**Quant:** 350+ Technical Indicators, 14-Metric Fundamental Scoring, Backtesting (131K records), LSTM Prediction, Smart Rebalancing

**Backend:** FastAPI, Flask, Node.js, TypeScript, PostgreSQL, Redis, Neo4j, Docker, AWS SQS

**Frontend:** React, Vite, Streamlit, Chart.js, Tailwind CSS

---

## Background

- B.Tech Computer Science + AI @ **IIIT-Delhi** (Minor in Entrepreneurship)
- Former Research Intern @ **SBI Labs** (Survival Analysis) and **ECE Labs** (NLP/LLMs)
- Technical Secretary &mdash; Student Council, IIIT-Delhi
- Founder &mdash; CyFuse (Tech Club)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohit1053&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohit1053&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
</p>
