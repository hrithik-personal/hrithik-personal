# Hi, I'm Hrithik 👋

**Senior Software Engineer @ MoEngage** — I build the backend **platform services** other teams build features on, and the **AI-integrated tooling** on top of them.

- 🏗️ Platform engineering — multi-tenant services at scale (200K+ RPM, <10ms p99)
- 🤖 AI systems — semantic search, MCP servers, and LLM agents
- 📍 Bengaluru, India

## 🔦 Featured project

### [NL2SQL Agent Harness →](https://github.com/hrithik-personal/nl2sql-agent-harness)
A multi-agent **Text-to-SQL analytics agent**: ask a question about your data in plain English, get back a verified answer, the SQL behind it, and a full trace of how the agents got there.

Built as a reference for **production agent engineering** — the parts that make an agent *operable*:
- **Evals gated in CI** — 72% execution-match / 100% valid-SQL, fully deterministic & offline (recorded LLM cassettes + pinned retrieval)
- **Per-agent model routing & budgets** behind a LiteLLM gateway (~$0.012/query), with timeouts + cross-model fallback
- **Defense-in-depth SQL sandbox** (AST guard + read-only txn + least-privilege role + EXPLAIN cost gate)
- **End-to-end observability** (OpenTelemetry → Arize Phoenix)

`Python` · `LangGraph` · `LiteLLM` · `PostgreSQL + pgvector` · `FastAPI` · `MCP` · `OpenTelemetry / Arize Phoenix` · `Docker` · `GitHub Actions`

## 🛠️ Tech I work with
**Backend:** Java · Spring Boot · Python · Kafka · MongoDB · OpenSearch · Redis
**Cloud/infra:** AWS (Lambda, SQS, EventBridge) · Docker · Nginx
**AI:** LangGraph · LiteLLM · RAG · pgvector · Model Context Protocol (MCP) · AWS Bedrock

## ✍️ I write about systems & reliability
[Medium](https://hrithik-notes.medium.com) · [LinkedIn](https://www.linkedin.com/in/hrithik-kumar-public/)
