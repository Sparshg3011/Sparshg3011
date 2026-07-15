<div align="center">

# Sparsh Gupta

**Backend · Distributed Systems · Agentic AI / RAG**

Software Engineer Intern @ [Endgame.ai](https://endgame.ai/) · M.S. Computer Science @ USC · Los Angeles, CA

Open to full-time roles · Graduating December 2026

[LinkedIn](https://www.linkedin.com/in/sparshg3011/) · [Email](mailto:sparshgupta643@gmail.com) · [Portfolio](https://sparsh-gupta-portfolio.vercel.app/#projects)

</div>

---

## About

I'm a software engineer and Master's student in Computer Science at USC, focused on backend systems, distributed architecture, and applied AI. Most of my work is designing services that stay fast, correct, and resilient under real-world conditions.

What draws me to agentic AI and RAG is making language models behave predictably inside production infrastructure — where reliability matters as much as raw intelligence. I'm looking for work where strong systems thinking and hands-on AI experience meet.

---

## Tech Stack

| Area | Technologies |
|------|--------------|
| **Backend & APIs** | Node.js, FastAPI, Fastify, Express, .NET, GraphQL, REST |
| **Distributed Systems & Infrastructure** | Apache Kafka, RabbitMQ, Redis, Docker, AWS, PostgreSQL, MongoDB |
| **Agentic AI & ML** | LangGraph, LangChain, OpenAI, Claude API, PyTorch, HuggingFace, ChromaDB, Pinecone, FAISS |
| **Languages** | Python, TypeScript, JavaScript, C++, C#, SQL |
| **Frontend** | React, Next.js, Vue.js, Flutter, Tailwind |

---

## Research & Achievements

- **Co-author, *Cognitive Weave*** — a hybrid vector and graph memory orchestrator for multi-agent systems ([arXiv:2506.08098](https://arxiv.org/abs/2506.08098)).
- **Selected for EleutherAI's Summer of Open AI Research** — context compression using AST and LSP analysis that reduces hallucinations in code-generation agents.
- **Research Assistant, USC ISI (INK Lab)** — a structured survey of the privacy risks in LLM watermarking and distillation.

---

## Featured Projects

### Systems, Distributed Infrastructure & Backends

**[Timefork](https://github.com/Sparshg3011/Timefork)** — A durable execution runtime that makes AI agents crash-resilient. Every step an agent takes is written to an append-only event log in Postgres and replayed deterministically, so a worker killed mid-task resumes exactly where it stopped. A two-phase intent/completion protocol with idempotency keys and fencing tokens keeps side effects idempotent, so each one applies once even when stale workers linger. *(Python · PostgreSQL)*

**[Vector Search Engine (HNSW)](https://github.com/Sparshg3011/vector-search-engine)** — A hand-built implementation of the HNSW approximate nearest-neighbor algorithm in pure NumPy, with the layered navigable graph, diversity heuristic, and beam search all written from scratch. It behaves like a production vector index while staying small and readable, and ships with a CI suite covering recall, graph reachability, and save/load determinism. *(Python · NumPy)*

**[Infinitune](https://github.com/rohang1411/Infinitune-Realtime-LLM-Fine-Tuning-Framework)** — A distributed streaming framework for adapting large language models while they stay in production. Three Kafka-coordinated services stream LoRA adapter updates through the pipeline so a served model keeps improving in near real time, with no downtime during a swap. *(Apache Kafka · PyTorch · HuggingFace · LoRA)*

**[CasaYa](https://github.com/Sparshg3011/rentcasaya)** — A rental marketplace built on an event-driven RabbitMQ microservice backend. It runs the full tenant journey — listing discovery, automated screening, payments, and digital lease signing — as decoupled services that stay responsive under load. *(Next.js · Node.js · RabbitMQ · Redis · Supabase)*

### Agentic AI, RAG & Applied ML

**[Litmus](https://github.com/Sparshg3011/litmus)** — An autonomous agent that puts machine-learning papers to the test by re-running them. It reads a paper and its dataset, generates the analysis pipeline the paper describes using the Claude API, and executes that pipeline inside a network-isolated Docker sandbox. A bounded self-repair loop feeds runtime errors back into code generation, and every result is checked against pinned ground-truth data so the agent can never grade its own output. *(Python · Claude API · Docker)*

**[VocaMind](https://github.com/Sparshg3011/VocaMind)** — A real-time voice-agent platform for outbound calling. It stitches together speech recognition, text-to-speech, and live sentiment analysis to hold natural multi-turn conversations and adapt its tone as the call unfolds, with dialog state persisted so long conversations stay coherent. *(Fastify · Next.js · Twilio · ElevenLabs · MongoDB)*

**[PodSearch](https://github.com/Sparshg3011/PodSearch)** — A semantic search engine over long-form podcast audio that answers natural-language questions with the exact timestamp where the answer appears. An agentic fact-checking layer verifies each retrieved passage before responding, keeping answers grounded in what was actually said. *(FastAPI · ChromaDB · OpenAI · LangChain)*

**[HaluGuard](https://github.com/Sparshg3011/HaluGuard)** — A contrastive context-selection method that curbs hallucination in code-generation models. It scores candidate snippets of repository context and selects the most relevant ones, so the model conditions on the right code before it writes anything. *(PyTorch · Transformers · UniXcoder)*

---

## Hackathon Projects

**[HealthSwarm](https://github.com/Sparshg3011/HealthSwarm)** · *LA Hacks* — Multi-agent healthcare orchestration. A FastAPI backend coordinates a swarm of autonomous agents over a LangGraph state machine that searches clinics and places live outbound voice calls, carrying a patient from request to booked appointment without a human in the loop. *(LangGraph · FastAPI · MongoDB · Twilio · ElevenLabs)*

---

## Education

- **University of Southern California** — M.S. in Computer Science *(Jan 2025 – Dec 2026, Expected)*
- **Guru Gobind Singh Indraprastha University** — B.Tech in Computer Science and Engineering *(2020 – 2024)*

---

<div align="center">

Let's connect — [LinkedIn](https://www.linkedin.com/in/sparshg3011/) · [Email](mailto:sparshgupta643@gmail.com) · [Portfolio](https://sparsh-gupta-portfolio.vercel.app/#projects)

Los Angeles, CA

</div>
