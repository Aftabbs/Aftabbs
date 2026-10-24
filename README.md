## Hi, I'm Aftab 👋

**Senior AI Engineer at Tiger Analytics (Bengaluru).** I build production AI that enterprises can trust: agents that plan and act, retrieval grounded in real data, and the guardrails, evaluation and tracing that make them safe to ship.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohammed%20Aftab-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-aftab-526b7a257/)
[![X](https://img.shields.io/badge/X-@BsAftab-000000?logo=x&logoColor=white)](https://x.com/BsAftab)
[![Medium](https://img.shields.io/badge/Medium-@aftab001x-12100E?logo=medium&logoColor=white)](https://medium.com/@aftab001x)
[![Email](https://img.shields.io/badge/Email-aftab001x%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:aftab001x@gmail.com)

### What I work on

- **LLM guardrails.** Small fine-tuned models that catch PII leaks and prompt injection at low latency, with traceability from training data to the deployed model.
- **Agentic AI for financial services.** Multi-agent workflows, Text-to-SQL and RAG analytics, and governance (identity, human approval, audit logs) on AWS Bedrock.
- **Evaluation and observability.** Testing AI behaviour in CI, tracing agents with OpenTelemetry, and scoring output quality.

### Open source: 25+ merged PRs

| Project | What I fixed or added |
| --- | --- |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) and [haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) | Silent data corruption from shared dataclass mutation across pipeline branches; Anthropic server tools; cache-token usage for LiteLLM, Gemini and Bedrock; async document stores |
| [NVIDIA/garak](https://github.com/NVIDIA/garak/pull/2019) | Retry transient NIM HTTP errors and report the real status code |
| [openclaw/openclaw](https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) | Plugin registry re-activating on every MCP connection; Linux daemon crash on bus permission errors |
| [Arize-ai/openinference](https://github.com/Arize-ai/openinference/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) | MCP uninstrumentation; cost propagation to span attributes |
| [openlit/openlit](https://github.com/openlit/openlit/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) | Token counts and tool-call spans across providers; offline evaluations after restart |
| [truera/trulens](https://github.com/truera/trulens/pulls?q=is%3Apr+author%3AAftabbs+is%3Amerged) | SQL-level leaderboard aggregation; correct cost for unknown models |
| [comet-ml/opik](https://github.com/comet-ml/opik/pull/8147) · [langsmith-sdk](https://github.com/langchain-ai/langsmith-sdk/pull/2738) | Streaming usage helpers; Pydantic warnings in the Anthropic wrapper |
| [Azure Cosmos DB MCP samples](https://github.com/AzureCosmosDB/azure-cosmos-mcp-server-samples/pull/18) | The first Python MCP server for Azure Cosmos DB |

### Things I built

| Project | What it does |
| --- | --- |
| [**BehaviorCI**](https://github.com/Aftabbs/BehaviourCI) | CI for LLM behaviour: describe how your AI feature should behave, and it generates adversarial tests and blocks the PR when behaviour regresses. `npx behaviourci demo` |
| [**greenwash**](https://github.com/Aftabbs/greenwash) | Catches coding agents that weaken your tests and then report success. Deterministic: reads `git diff`, no model, no API key. |
| [**Native Place**](https://github.com/Aftabbs/native-place) | Find the train to your hometown: any town in India, official 2026 timetable, fares and festival specials. [Live ↗](https://native-place.pages.dev) |
| [**SLM Guardrails Chat**](https://github.com/Aftabbs/Groq-SLM-Guardrails-Chat) | Local small language models acting as safety, topic, format and PII guards in front of a Groq-powered chatbot |
| [**Prompt Injection Gym**](https://github.com/Aftabbs/Prompt-Injection-Gym) | A small, reproducible playground to attack and defend a tool-using agent |
| [**Book Writing AI Agent**](https://github.com/Aftabbs/Book-Writing-AI-Agent) | Multi-agent system that plans, writes and edits a full book |

### Stack

Python · TypeScript · FastAPI · LangGraph · Strands · MCP · AWS (Bedrock, AgentCore, S3, Athena) · Azure · PyTorch · Hugging Face · MLflow · OpenTelemetry · PostgreSQL · Redis · Docker

---

<sub>Open to conversations about AI engineering roles and open-source collaboration.</sub>

![Contribution snake](https://raw.githubusercontent.com/Aftabbs/Aftabbs/output/github-contribution-grid-snake.svg)
