<h1 align="center">Hi, I’m Gopal 👋</h1>
<p align="center">
  <a href="https://gopalcb.github.io/" target="_blank">https://gopalcb.github.io/</a>
</p>

## Stack

- REST Frameworks and Runtime: Python, FastAPI, Flask | TypeScript, Node.js, Express.js, NestJS.
- Auth and IdP: OAuth 2.0, OpenID Connect, Auth0, AWS Cognito, Cloudflare Zero Trust.
- Core AWS Infra/Services: ALB, EKS, API Gateway, Lambda, SQS/SNS, Event Bridge | Nginx, Kong | Glue ETL.
- Databases: PostgreSQL | DynamoDB, Redis | OpenSearch, ChromaDB | FalkorDBLite, Neo4j.
- Predictive Modeling: Classic ML, Deep Learning | scikit-learn, XGBoost, PyTorch.
- Data, RAG and Agent Frameworks: PySpark, Haystack, LangGraph, NumPy | n8n workflow | AWS Bedrock.
- LLM and Embedding Models: Claude Haiku and Sonnet, Qwen3 8-32B, text-embedding-3-small, Titan.
- Unit testing, Eval and Sandboxing: Pytest, Jest, DeepEval, Ragas | langchain-sandbox, llm-sandbox.
- CICD and Observability: Terraform, GitHub workflow, Docker | OpenTelemetry, CloudWatch, Splunk.
- Development and Automation Tools: VS Code, Jupyter Lab, Codex/Claude Code, Crawl4AI web crawler, Playwright.


## Projects

| Project | What it explores |
| --- | --- |
| [rag-memory-mesh-cli](https://github.com/gopalcb/rag-memory-mesh-cli) | A RAG embedding (Code + Markdown text), retrieval based vector memory system for Codex agent developed using Python and Haystack. It works through collaboration between the Main coding agent and the isolated Memory-agent by asking the Memory-agent for semantic memory lookup. The Main agent can use that memory for faster plan creation and implementation if memory hits. The memory-agent runs the embedding pipeline after Main agent’s every turn completion. Additionally, it can run a one-time embedding on an entire repo. |
| [MCP server for sharing markdown files across agents and chats](https://github.com/gopalcb/markdown-file-sharing-network-across-agents) | A custom MCP server running on AWS Lambda and exposed via an API Gateway endpoint gated behind OAuth2. It can stream cross tools and agents markdown content to a central S3 bucket, organizing documents and access. The MCP plugin integrates with Codex, ChatGPT and Claude across mobile and web interfaces, making shared content easy for people and coding agents to search and access as ready-to-use context for agent tasks. |
| [POC: API Builder Agent](https://github.com/gopalcb/api-builder-agent) | An entity-driven and event-driven Flask and Angular workbench with LangGraph, LangChain Deep Agents and Codex-powered API builder. The agent enables faster and structured way of building REST APIs, enabling quick integration of identity, authentication, OpenTelemetry, endpoint & routing config, caching and other advance tools like embeddings and semantic search. |
| [OpenTelemetry Lab](https://github.com/gopalcb/opentelemetry-lab-gb) | An observability blueprint using OpenTelemetry, Tempo, Loki, Elasticsearch, and Kibana. |
| [Custom Codex Runtime](https://github.com/gopalcb/custom-tools-and-runtime-for-agent-work) | A compact runtime with YAML workflows, durable messaging, memory and custom tools. It uses Playwright to let users generate prompt visually and preciously targeting specific UI elements and coding agent can directly jump in and implement. It significantly reduces token consumption and other overhead. |

---

<a href="mailto:gopalcbala@gmail.com"><img src="https://d3bgmkj8219hsy.cloudfront.net/api/gh-resource?icon=email" width="18" height="18" alt="" /> Email</a> | <a href="https://www.linkedin.com/in/gopal-c-bala/"><img src="https://d3bgmkj8219hsy.cloudfront.net/api/gh-resource?icon=linkedin" width="18" height="18" alt="" /> LinkedIn</a>
