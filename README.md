<div align="center">

# 孔岩彬 · Ivan Kong

**Full-stack developer building web products and production-minded AI systems.**

React / Node.js / Python · RAG / MCP agents / vLLM

把真实问题做成可维护的系统，而不只是能运行的 demo。

[Featured work](#selected-work) · [GitHub repositories](https://github.com/Tech-luoyi?tab=repositories)

</div>

---

## About

I am a student at Wuxi University, building across full-stack web, Python backends, RAG pipelines, agent workflows, and model-serving infrastructure.

I enjoy working across the whole product boundary: interface design, API contracts, retrieval quality, agent orchestration, data models, deployment, testing, and the unglamorous edge cases that decide whether software is actually useful.

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| [Community-Reuse](https://github.com/Tech-luoyi/Community-Reuse) | A neighborhood item circulation platform with explicit frontend/backend boundaries, a pgvector-backed RAG pipeline, retrieval-backed agent tools, AI-assisted pricing, and failure states that tell the truth. | Next.js 15 · TypeScript · PostgreSQL · Prisma · pgvector · LangGraph |
| [CSPortfolio](https://github.com/Tech-luoyi/CSPortfolio) | An end-to-end recruitment portal for a university computer association: applications, uploads, review, status tracking, CSV export, and deployment. | Nuxt 3 · Vue 3 · TypeScript · SQLite · Docker |
| [Remote2048](https://github.com/Tech-luoyi/Remote2048) | A real-time two-player 2048 variant with an authoritative game server, client prediction and recovery, reconnects, and an Expectimax solver. | JavaScript · Node.js · WebSocket · Canvas · WebAssembly |

## AI systems

I build AI features as complete systems, not isolated model calls. The hard parts are usually retrieval quality, tool contracts, state recovery, latency, and knowing what the product should do when a model or dependency fails.

| Layer | What I work with |
| --- | --- |
| Retrieval and RAG | Embeddings, pgvector semantic retrieval, context construction, and retrieval-backed features |
| Agent orchestration | LangGraph workflows, state and checkpoints, tool calling, structured outputs, and failure recovery |
| Tool integration | MCP servers and clients, typed tool boundaries, and explicit permission scopes |
| Model serving | vLLM, OpenAI-compatible APIs, local inference, and serving-path tradeoffs |

## Technical focus

| Area | Tools and practices |
| --- | --- |
| Frontend | React, Next.js, Vue, Nuxt, TypeScript, responsive UI |
| Backend | Node.js, Python, REST APIs, service boundaries, typed contracts |
| AI systems | RAG, LangGraph agents, MCP tooling, LLM integration, vLLM serving |
| Data | PostgreSQL, SQLite, Prisma, pgvector |
| Delivery | Docker, GitHub Actions, Linux, testing and deployment |

I care more about choosing the right abstraction than collecting tools. When a constraint is unclear, I prefer a small executable prototype, a written contract, and a test over a long speculative design.

## Current direction

- Building React and Vue products backed by Node.js or Python services.
- Designing RAG pipelines with embeddings, pgvector indexes, and retrieval evaluation.
- Building LangGraph agents with MCP-connected tools, explicit contracts, and observable failure states.
- Exploring vLLM serving paths, OpenAI-compatible APIs, and the latency/cost tradeoffs of local inference.
- Exploring AI-assisted experiences without hiding degraded behavior behind false success states.
- Improving developer experience through clearer contracts, better tests, and honest documentation.

## Engineering principles

> Clear boundaries over clever coupling.  
> Honest failure states over silent degradation.  
> Maintainability over demo speed.

## Elsewhere

- GitHub: [@Tech-luoyi](https://github.com/Tech-luoyi)
- Institution: Wuxi University

Open to thoughtful issues and pull requests on the projects above.
