# Semih Işık

**AI Software Engineer & Full-Stack Systems Builder**  
Istanbul, Türkiye · [`semih.isk@outlook.com.tr`](mailto:semih.isk@outlook.com.tr)

I design and ship end-to-end production systems—taking early-stage R&D initiatives from zero to commercial SaaS across distributed backends, real-time multimodal voice/video agents, enterprise LLM infrastructure, and cloud/edge runtimes.

---

### Core Engineering Capabilities (By System Layer)

* **Backend, Concurrency & Distributed Systems:** **Python** (`FastAPI`, `Asyncio`, `SQLAlchemy 2.0`, `Pydantic`), **Rust**, **TypeScript / Node.js / V8 Edge**, **C# / .NET**, high-throughput asynchronous pipelines (`Celery`, `ARQ`, `Redis`), `PostgreSQL`, `SQLite / D1`.
* **Applied AI, Gateways & Agentic RAG:** Multi-provider **LLM Gateways** (fallback routing, virtual API keys, token/budget quotas, MCP/tool standardization), Bounded Native ReAct orchestration, Hybrid RAG (`LlamaIndex`, `Qdrant`, `Cloudflare Vectorize`), Long-Term Memory (`Mem0`), Constrained Decoding (`Instructor`, `Outlines`, strict JSON Schema).
* **Real-Time Multimodal, Voice & Telephony:** `LiveKit` (`WebRTC`), real-time streaming video avatars, Telephony / SIP voice agents, `ElevenLabs` TTS, and automated live meeting bots (Google Meet / Zoom transcription & structured evaluation).
* **LLMOps, Evaluation & FinOps:** 3-layer AI evaluation pyramids (`DeepEval` LLM-as-a-Judge, G-Eval rubrics, Faithfulness benchmarks), `Langfuse` OpenTelemetry tracing, unit-economics modeling, and production error monitoring (`Sentry`).
* **Frontend, Desktop & Cloud Infrastructure:** `Vue 3`, `React`, `Preact` (Shadow DOM micro-frontends), `Tailwind CSS`, multi-window desktop IPC (`Overwolf`), **AWS** (`ECS`, `EC2`, `Lambda`, `S3`, `ECR`), **Cloudflare Edge** (`Workers`, `D1`, `R2`, `Zero Trust`), `Docker`, and CI/CD pipelines.

---

### Selected Public Architecture Case Study

> Most of my production work—including real-time WebRTC/SIP voice platforms, high-throughput Python/FastAPI & Celery/ARQ pipelines, Rust LLM gateways, and AWS workloads—resides in private commercial and enterprise repositories. The repository below is a **selected public architecture case study and sanitized reference implementation** from an independent system:

| Repository | Runtime & Architectural Focus |
| :--- | :--- |
| **[`cewjh/commerce-copilot-architecture`](https://github.com/cewjh/commerce-copilot-architecture)** | **Cloud / Edge Multi-Tenant SaaS:** C4 architecture, 10 ADRs, 3-layer AI eval pyramid, Zero Trust FinOps control plane, Web Crypto merchant portal, and zero-dependency testable reference modules (`references/`) — covering both the horizontal e-commerce platform and its domain-calibrated **AquaBot** vertical. |
