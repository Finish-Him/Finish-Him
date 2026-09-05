<div align="center">

# Moisés Costa
### Senior Python & AI Backend Engineer

Rio de Janeiro, Brazil 🇧🇷 · Remote Worldwide 🌐  
*Building resilient backend microservices, high-throughput APIs, and production Generative AI systems.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Moisés_Costa-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moises-costa-rj/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Finish--him-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Finish-him)
[![Email](https://img.shields.io/badge/Email-moises.costa12345%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:moises.costa12345@gmail.com)

```text
12+ Years in IT • 6+ Years with Python • 3+ Years Production GenAI / Agents
FastAPI • PostgreSQL • pgvector • Docker • GCP • RAG • MCP • LangGraph
```

---

</div>

## 🔭 Core Technical Stack

```text
Backend:      Python (3.10–3.13) · FastAPI · Pydantic v2 · SQLAlchemy · Elysia / Bun · REST APIs · Asyncio
AI & Agents:  OpenAI API · Anthropic Claude · Tool Calling · MCP · LangGraph · Hybrid RAG · Local LLMs
Databases:    PostgreSQL 16 · pgvector · Redis · SQLite · Supabase · Schema Modeling & Migrations
Infra & Ops:  Docker · Linux (Debian/Ubuntu) · GCP (GCE, Cloud Run, Secret Manager, IAP) · Traefik v3 · CI/CD
Quality:      Pytest · Ruff · Mypy · Clean Architecture · Observability & Structured Logging
```

---

## 🏛️ Featured Engineering Case Studies

### 🔍 [Atlas — Institutional Semantic Search & Asset Governance](https://github.com/Finish-Him)
- **Architecture:** Hybrid search microservice combining **PostgreSQL + pgvector (HNSW)** with Full-Text Search via Reciprocal Rank Fusion (RRF).
- **Impact:** Cut query retrieval latency from minutes to **<200ms** across millions of state records with **4.8x recall improvement**.
- *Stack:* `Python 3.12` · `FastAPI` · `PostgreSQL` · `pgvector` · `Docker` · `Redis`

### 📄 [Logos — Enterprise Document Intelligence & Schema Extraction](https://github.com/Finish-Him)
- **Architecture:** Automated PDF ingestion and data extraction pipeline using **LLM Tool Calling** and **Pydantic v2** validation with self-healing correction loops.
- **Impact:** Achieved **99.2% schema validation accuracy**, reducing manual document data entry time by **85%**.
- *Stack:* `Python` · `FastAPI` · `Pydantic v2` · `Claude/OpenAI APIs` · `Pytest`

### ⚡ [MSC Autonomous AI Gateway — Event-Driven Agent Orchestration](https://github.com/Finish-Him)
- **Architecture:** Dual-engine architecture (**Bun** perimeter ingestion + **FastAPI** reasoning core) connected to messaging protocols (Evolution API for WhatsApp).
- **Impact:** Processes thousands of real-time webhooks with **sub-1.2s agentic responses**, handling automated qualification, dynamic pricing, and CRM sync with zero message loss.
- *Stack:* `Bun` · `FastAPI` · `PostgreSQL` · `Redis` · `Docker` · `Evolution API`

### ⚖️ [Artemis & Arquimedes — Domain-Specific GenAI Tutoring Engines](https://github.com/Finish-Him)
- **Architecture:** Specialized vertical RAG engines with multi-stage retrieval, cross-encoder re-ranking, and deterministic legal/STEM citation guardrails.
- **Impact:** Reduced hallucination rates to **<1.5%** on rigorous multi-step legal reasoning benchmarks.
- *Stack:* `Python` · `RAG` · `LangGraph` · `pgvector` · `Hugging Face Datasets`

---

## 🏗️ High-Level System Architecture

```text
 ┌──────────────────────┐         ┌──────────────────────┐
 │   External Clients   │         │  Webhooks / Gateway  │
 │ (React/Next.js/Apps) │         │ (WhatsApp/Messaging) │
 └──────────┬───────────┘         └──────────┬───────────┘
            │                                │
            ▼                                ▼
 ┌────────────────────────────────────────────────────────┐
 │            Traefik v3 Cloud Edge (TLS/SSL)             │
 └──────────────────────────┬─────────────────────────────┘
                            │
            ┌───────────────┴───────────────┐
            ▼                               ▼
 ┌─────────────────────┐         ┌─────────────────────┐
 │  FastAPI Services   │         │ Bun/Elysia Gateway  │
 │  (Core Domain Logic)│         │ (High-Throughput In)│
 └──────────┬──────────┘         └──────────┬──────────┘
            │                               │
            ├───────────────┬───────────────┘
            ▼               ▼
 ┌────────────────────┐  ┌─────────────────────────────────┐
 │   PostgreSQL 16    │  │     Autonomous Agent Engine     │
 │  (pgvector / Rel.) │  │ (Tool Calling, MCP, Hybrid RAG) │
 └────────────────────┘  └────────────────┬────────────────┘
                                          │
                                          ▼
                         ┌─────────────────────────────────┐
                         │ LLMs: OpenAI / Claude / Local   │
                         └─────────────────────────────────┘
```

---

## 💬 Get In Touch

- **Email:** [moises.costa12345@gmail.com](mailto:moises.costa12345@gmail.com)
- **LinkedIn:** [linkedin.com/in/moises-costa-rj](https://www.linkedin.com/in/moises-costa-rj/)
- **Time Zone:** Rio de Janeiro, Brazil (UTC-3 / EDT-1) — *Smooth business hours overlap with US (EST/PST) and European (CET) teams.*
