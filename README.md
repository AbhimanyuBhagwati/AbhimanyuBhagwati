<div align="center">

# Abhimanyu Bhagwati

**Generative AI Engineer** · Building production LLM systems, multi-agent architectures, and AI infrastructure

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhimanyubhagwati/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhiwati97@gmail.com)
[![PyPI](https://img.shields.io/badge/pip_install_traceforge-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/traceforge/)

</div>

---

I build AI systems that handle real workloads — multi-agent routing, fine-tuned LLMs, hybrid retrieval pipelines, and the infrastructure to run them reliably at scale. Currently at **22nd Century Technologies** engineering GenAI platforms for government clients.

```python
about_me = {
    "role":     "Generative AI Engineer",
    "focus":    ["Multi-Agent Systems", "RAG", "LLM Fine-tuning", "AI Infrastructure"],
    "stack":    ["Python", "LangChain", "NeMo", "Rust", "Kubernetes"],
    "built":    "17x throughput · 500K daily interactions · 93% RAGAS accuracy",
    "open_to":  "AI Platform / ML Infrastructure roles",
}
```

---

## What I Work On

**Agentic Systems**  
Multi-agent routing with 3B-param LLMs, LangChain tool-calling, Text-to-SQL agents, ReAct workflows, MCP integration for dynamic context injection.

**RAG & Retrieval**  
Hybrid dense-sparse search with Milvus, pgvector, ChromaDB. IBM Granite reranking. RAGAS evaluation pipelines. 100% local LLM architectures where data never leaves the server.

**LLM Fine-tuning**  
NVIDIA NeMo (12B) fine-tuning on enterprise schemas. LoRA. Hallucination reduction, AI governance controls, toxicity filtering.

**Infrastructure**  
Rust/PyO3 performance engineering. FastAPI backends. Docker, Kubernetes. AWS, Azure, GCP. CI/CD. Grafana/Prometheus observability.

---

## Featured Project

### [TraceForge](https://github.com/AbhimanyuBhagwati/TraceForge) · `pip install traceforge`

> Test harness for tool-calling AI agents.

Records executions as **SHA-256 content-addressed traces**, replays deterministically without re-running models, fuzzes tool responses, and mines behavioral invariants Daikon-style. The debugging layer the AI agent ecosystem was missing.

```bash
pip install traceforge
```

```python
from traceforge import Tracer

tracer = Tracer()
with tracer.record() as t:
    result = agent.run(query)

t.replay()     # deterministic, no model calls
t.fuzz()       # surface edge cases
t.attribute()  # causal attribution
```

**183 tests · Published on PyPI · Open Source**

---

## Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [FilingNectar](https://github.com/AbhimanyuBhagwati) | Local RAG for 74 SEC 10-K filings · 9,334 sections · 65% query improvement | FastAPI · Next.js · Ollama · RAGAS |
| [gRPC Microservices](https://github.com/AbhimanyuBhagwati) | 100K+ daily requests · 30% latency reduction · 99.9% uptime | Go · gRPC · Prometheus |

---

## Stack

```
Languages     Python · Rust (PyO3) · Go · TypeScript · SQL
AI/LLM        LangChain · LlamaIndex · NeMo · LoRA · RAG · RAGAS · MCP
Vector DBs    Milvus · pgvector · ChromaDB · Qdrant
Cloud         AWS · Azure · GCP · Docker · Kubernetes
Observability Grafana · Prometheus · Azure DevOps
```

---

## Numbers

```
17×      throughput improvement   Rust/PyO3 hybrid pipeline
500K+    daily AI interactions    Multi-agent routing system
93%      answer accuracy          Hybrid search · RAGAS validated
60%      token reduction          Optimized JSON schema pipeline
35%      hallucination drop       NeMo fine-tune + MCP context
```

---

<div align="center">

*MS Computer Science · Virginia Tech · 2025*  
*Open to AI Platform · ML Infrastructure · LLM Systems roles*

</div>
