<div align="center">

# Saad Aziz

### GenAI Infrastructure Engineer · Multi-Agent Systems · RAG · Voice AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saadaziz-ai)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saadaziz.2910@gmail.com)
[![pydantic-ai contributor](https://img.shields.io/badge/pydantic--ai-merged_PR-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pydantic/pydantic-ai/pull/4431)

</div>

---

I design, build, and ship **production-grade multi-agent AI systems** end-to-end — from architecture through deployment and continuous production monitoring. My work spans healthcare, real estate, and enterprise automation, turning complex LLM architectures into reliable, containerized systems with measurable business impact.

I specialise in **reflective agentic systems** that detect and recover from tool-call failures and transient LLM errors automatically, **growing agents** that update their memory with each interaction, and **self-healing pipelines** that resume from the last checkpoint on failure — all instrumented with **LangSmith** for full observability in production.

**Currently:** GenAI Infrastructure Engineer @ Tectanic — shipping self-learning clinical AI, HIPAA-compliant multi-tenant RAG, and NLP-to-SQL systems.

---

## What I Build

- **Reflective Multi-Agent Systems** — LangGraph pipelines with automatic tool-call error recovery, LLM retry on transient failures, and human-in-the-loop confirmation for high-risk operations
- **Growing / Self-Learning Agents** — Agents that update persistent memory after every interaction, adapting behaviour based on user feedback over time
- **Production RAG Platforms** — Multi-tenant vector DB systems for healthcare (HIPAA) and enterprise knowledge bases with source citations and strict data isolation
- **NLP-to-SQL Engines** — Natural language interfaces over relational databases with read-only query validation and schema-aware prompt engineering
- **Self-Healing Pipelines** — Checkpoint-based multi-agent workflows that automatically resume from the last successful step on failure
- **AI Automation** — End-to-end integrations across Monday.com, HubSpot, Microsoft Teams, and Asana via N8N, Make.com, and custom APIs
- **Observability** — All production systems instrumented with LangSmith for distributed tracing, performance monitoring, prompt versioning, and evaluation datasets

---

## Tech Stack

**AI & LLMs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)

**Vector DBs & Search**

![Weaviate](https://img.shields.io/badge/Weaviate-FF6F61?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)
![PgVector](https://img.shields.io/badge/PgVector-336791?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make.com-6D00CC?style=flat-square)
![Flowise](https://img.shields.io/badge/Flowise-4285F4?style=flat-square)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Digital Ocean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## Featured Work

### Tectanic (Current · Oct 2025 – Present)

| Project | Impact | Stack |
|---------|--------|-------|
| **Self-Learning Clinical Multi-Agent System** | Persistent PostgreSQL memory that adapts per physician; reflective agents retry failed tool calls; 95%+ approval on drug interaction alerts; 70% payload reduction | LangGraph, LangChain, GPT-4o, PostgreSQL, LangSmith, Docker |
| **Multi-Tenant Agentic RAG — 20+ Clinics** | Zero cross-tenant data leakage; SHA-256 dedup cut storage costs 35%; fixed critical bug in langchain-weaviate 0.0.6 | LangChain, Weaviate v4, OpenAI Embeddings, LangSmith, FastAPI |
| **NLP-to-SQL Query Engine (50+ EHR Tables)** | 92% query accuracy on complex multi-table joins; HIPAA-compliant read-only validation; reflective error recovery retries corrected SQL autonomously | LangGraph, LangChain, PgVector, LangSmith, AWS |
| **Self-Healing Monday → HubSpot Pipeline** | Multi-agent SEO content automation; checkpoint-based recovery resumes from last success on failure | Make.com, OpenAI, Anthropic |

### Reporteq Solutions (Mar 2025 – Oct 2025)

| Project | Impact | Stack |
|---------|--------|-------|
| **HIPAA Doctor Assistant — 50+ Physicians** | Real-time text/voice/WebSocket agent with EHR access; reflective tool-call retry; mandatory confirmation for high-risk ops cut medical errors 40%; LangSmith production monitoring | LangChain, OpenAI, LangSmith, FastAPI, WebSocket, React.js |
| **Medical Report Analysis (Vision AI)** | PDF/DICOM/MRI/CT/X-Ray analysis with GPT-4o vision; SSE streaming cut time-to-first-token 60%; ICD-10/CPT code generation | LangGraph, GPT-4o, FastAPI, Docker |
| **RAG Chatbot with References & Voice** | Multi-format document ingestion via S3 Lambda triggers; source-cited answers with voice interface | LangGraph, ChromaDB, OpenAI, AWS Lambda/S3, React.js |

### Fantech Labs (Jan 2024 – Mar 2025)

| Project | Description | Stack |
|---------|-------------|-------|
| **Intelligent SQL Query Chatbot** | Natural-language-to-SQL over relational databases with semantic schema search | LangChain, FAISS, OpenAI Embeddings, FastAPI, Docker |
| **Real Estate AI Assistant** | NLP chatbot querying millions of property records with multi-filter support | n8n, MySQL |
| **AI Meeting Co-Pilot (Microsoft Teams)** | Joins live Teams meetings and provides RAG-based spoken responses in real time | n8n, Recall.ai |
| **Call Center AI Co-Pilot** | Real-time agent assistant with speech-to-text, response suggestions, and post-call automation | CrewAI, Whisper, WebSocket |

---

## Open Source Contributions

### pydantic-ai — Core Bug Fix · Merged ✅
[![pydantic-ai](https://img.shields.io/badge/pydantic--ai-8.5K+_Stars-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pydantic/pydantic-ai/pull/4431)

**PR #4431** — Fixed a production crash across all model providers (Anthropic, Gemini, Google, Bedrock, Mistral, xAI) where malformed JSON in tool-call arguments caused an unrecoverable `ValueError` during the retry flow, preventing agents from self-correcting.

- Refactored `args_as_dict()` on `BaseToolCallPart` to be **safe-by-default** — wraps malformed args using the Anthropic-recommended `INVALID_JSON` key instead of raising, so the retry loop can continue
- Updated **7 provider integrations** and the Vercel AI UI adapter
- Defined a module-level constant with link to Anthropic docs, added snapshot-asserted unit + integration tests
- Reviewed and merged by pydantic-ai maintainer **DouweM**

### GenAI_Agents — Community Contributor
[![GenAI Agents](https://img.shields.io/badge/GenAI_Agents-20K+_Stars-yellow?style=for-the-badge&logo=github)](https://github.com/NirDiamant/GenAI_Agents)

Contributor to one of the most starred GenAI repositories (20,000+ stars). Added agent implementations for real-world agentic use cases using LangChain and CrewAI.

---

## Achievements

🏆 **Top 25 / 620** — AgentCraft Hackathon (Diamant AI, Nov 2024)

Built a real-time call center AI co-pilot and a meeting preparation agent in a 3-day competitive hackathon. Stack: LangChain, CrewAI, Whisper, local LLaMA, WebSocket, JWT.

---

## GitHub Stats

<div align="center">

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Saad-Azi&theme=github-dark-blue&hide_border=true)

</div>

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Saad-Azi&color=blue&style=flat-square)

**Open to GenAI Engineering, AI Infrastructure, and LLM Systems roles.**

</div>
