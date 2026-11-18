<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/bento-dark.svg" />
  <img src="./assets/bento-light.svg" alt="Madhunika Danam: AI/ML Engineer" width="100%" />
</picture>

## ✦ About

At Northern Trust, I develop AI copilots and RAG platforms. Before that, I engineered backend AI services for Webex Contact Center, processing 2.5M conversation and workflow events daily for 4,000+ agents.

## ✦ Selected work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| **AIO Paydown Simulator** | Chat interface for modeling loan repayment scenarios | Serves **100+** end users, reduced dependency on manual financial calculations | Python, RAG, AI agents, n8n |
| **Enterprise RAG Platform** | Semantic search and retrieval across business documents | Processed **250,000+** documents, improved search accuracy by **37%** | Pinecone, embedding models, hybrid search, LangChain |
| **Webex Agent Assist Backend** | Real-time summarization, intent detection, and guidance for contact center agents | Served **4,000+** agents across **25+** tenants, processed **2.5M** events daily | Python, FastAPI, Kafka, PySpark, vLLM, Triton |
| **AI Copilot Solutions** | Enterprise assistants using OpenAI APIs and agentic workflows | Reduced information retrieval time by **42%**, automated processes reducing manual effort by **34%** | OpenAI APIs, LangChain, LangGraph, FastAPI |
| **guardrail-gw** | OpenAI-compatible LLM gateway that redacts PII, scores prompt injection, and audits requests | Rate-limits per key, filters streaming SSE, writes hash-chained audit log | Go, OpenAI-compatible API, Prometheus |
| **AI Job Search & Application Agent** | Automated workflow retrieving job postings, evaluating fit, and generating application content | Built centralized tracking with SQLite, implemented **100+** automated tests | Python, Claude API, Adzuna API, SQLAlchemy, PyTest |

<details>
<summary>Webex Agent Assist Backend, in depth</summary>

Engineered distributed Python and FastAPI services processing **2.5M** conversation and workflow events daily. Built agent guidance retrieval using pgvector HNSW search, cross-encoder reranking, and per-tenant Redis semantic cache. Deployed vLLM and Triton Inference Server on Kubernetes.

Reduced p95 inference latency from 920 ms to **610 ms** (**34%**). Reduced ungrounded responses by **18%**. Built offline and online evaluation pipelines across **1,500+** labeled scenarios and caught **12+** regressions before production.

</details>

<details>
<summary>Enterprise RAG Platform, in depth</summary>

Built RAG platforms processing **250,000+** enterprise documents using vector embeddings, semantic search, and contextual retrieval.

Improved search accuracy by **37%**. Lowered response latency by **36%**. Reduced recurring operational issues by **27%**.

</details>

## ✦ Experience

| Period | Role | Company | Highlights |
|--------|------|---------|------------|
| *Feb 2025 – Present* | AI Engineer | Northern Trust | Built AI copilots and RAG platforms processing **250,000+** documents. |
| *Jan 2022 – June 2023* | AI/ML Engineer | Hexaware Technology | Engineered backend AI services for Webex Contact Center serving **4,000+** agents across **25+** enterprise tenants, processing **2.5M** daily events. |

## ✦ Credentials

### Education
- **M.S. Computer Science and Information Technology**, Sacred Heart University, Fairfield, CT – *Dec 2024*
- **B.Sc. Mathematics, Statistics and Computer Science**, Osmania University, India – *July 2023*

## ✦ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,java,go,bash,powershell,fastapi,flask,githubactions,jenkins,docker,kubernetes,git,linux,aws,azure,gcp&theme=dark&perline=8" alt="py, java, go, bash, powershell, fastapi, flask, githubactions, jenkins, docker, kubernetes, git, linux, aws, azure, gcp" />
</p>

<p align="center"><a href="mailto:madhunika.danam@belvionus.com"><b>Email</b></a> &nbsp;·&nbsp; <a href="https://github.com/Danammadhunika"><b>GitHub</b></a></p>

## ✦ Projects

- [guardrail-gw](https://github.com/Danammadhunika/guardrail-gw) — An OpenAI-compatible LLM gateway in Go that redacts PII and secrets, scores prompt injection, filters streaming SSE safely, rate-limits per key and writes a…
