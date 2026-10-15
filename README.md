# Hi, I'm Yuri Marca

**AI Engineer & Solution Architect** · Production LLM systems · Evaluation · RAG · Agents · GCP

I design, build, and ship production LLM systems end to end, from shaping the solution with clients in pre-sales through architecture, implementation, cloud deployment, and knowledge transfer.

I focus on the layers that decide whether an LLM system works in production: **evaluation**, **retrieval and data design**, and **compliance**. I build evaluation harnesses that show where accuracy is lost, and I use them to drive architecture and roadmap decisions. Before this, I spent years in industrial ML (predictive maintenance and MLOps, edge ML, computer vision, and IoT).

## What I work on

- **Evaluation-driven LLM engineering:** LLM-as-judge suites, trace-based root-cause analysis, and benchmarks of model, cost, and latency trade-offs before committing to an approach.
- **Retrieval & data architecture for agents:** RAG with incremental ingestion and citation-grounded answers, NL2SQL agents, schema and retrieval design, and abstention policies so agents hold back rather than guess.
- **Agentic & real-time multimodal systems:** Multi-agent workflows with human-in-the-loop review, and voice agents that operate web applications through live native-audio models and function calling.
- **Regulated AI & cloud architecture:** HIPAA-compliant, event-driven pipelines on GCP, with compliance by design, architecture decision records, and full monitoring.
- **Production ML & MLOps:** Reproducible training, deployment, and monitoring pipelines from prototype to production.

## Open-source projects

| Project | Description | Tech |
|---|---|---|
| [**Agentic RAG**](https://github.com/yurimarca/agentic-rag) | RAG with conditional routing, hallucination detection, and dynamic tool use. | LangGraph · LangChain · Supabase |
| [**Reflexion Agent**](https://github.com/yurimarca/reflexion-agent) | An agent that reflects on its own output and revises it, for reasoning and tool use. | LangGraph · LangChain |
| [**MLOps**](https://github.com/yurimarca/mlops) | The full ML lifecycle: CI/CD, model and data versioning, drift monitoring, and API deployment. | MLflow · Docker · GitHub Actions |
| [**Client Risk ML Pipeline**](https://github.com/yurimarca/client-risk-ml-pipeline) | End-to-end attrition-risk pipeline with automated retraining and deployment. | MLflow · FastAPI · GitHub Actions |

## Tech stack

- **LLM & agents:** Google ADK, LangGraph, LangChain, Gemini (incl. Live), Vertex AI RAG Engine, Claude
- **Evaluation & tracing:** LLM-as-judge, Langfuse, LangSmith, OpenTelemetry, Grafana
- **Cloud:** GCP (Vertex AI, Document AI, Cloud Run, Pub/Sub, BigQuery), AWS (SageMaker)
- **ML:** PyTorch, Hugging Face, scikit-learn, XGBoost
- **MLOps:** MLflow, Docker, Kubernetes, GitHub Actions
- **Backend, frontend & data:** Python, FastAPI, WebSockets/SSE, React, TypeScript, PostgreSQL, Firestore, BigQuery

## Certifications

- [Claude Certified Architect – Foundations](https://www.credly.com/badges/25838dd7-bd89-4994-a060-ec7bbb5e2243/public_url) (Anthropic)
