<!doctype html>
<html lang="en"><head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<title>Sparsh Gupta — GitHub Profile Preview</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.5.1/github-markdown-dark.min.css">
<style>
  body { background:#010409; margin:0; padding:32px 16px; }
  .frame { max-width:900px; margin:0 auto; border:1px solid #30363d; border-radius:12px;
           background:#0d1117; box-shadow:0 8px 40px rgba(0,0,0,.6); overflow:hidden; }
  .bar { background:#161b22; border-bottom:1px solid #30363d; padding:10px 16px;
         font:600 13px/1 -apple-system,Segoe UI,sans-serif; color:#8b949e; display:flex; gap:8px; align-items:center; }
  .dot { width:11px; height:11px; border-radius:50%; display:inline-block; }
  .markdown-body { box-sizing:border-box; padding:40px 44px; }
  .markdown-body img { background:transparent; }
  .markdown-body > table:first-of-type, .markdown-body table tr { background:transparent; }
  .markdown-body table td, .markdown-body table th { border:1px solid #21262d; }
</style></head>
<body>
  <div class="frame">
    <div class="bar">
      <span class="dot" style="background:#ff5f56"></span>
      <span class="dot" style="background:#ffbd2e"></span>
      <span class="dot" style="background:#27c93f"></span>
      &nbsp; github.com/Sparshg3011 — README.md preview
    </div>
    <article class="markdown-body">
      <div align="center">
<h1>Sparsh Gupta</h1>
<p><strong>Backend &amp; Distributed Systems · Agentic AI &amp; RAG</strong></p>
<p>Master's in Computer Science @ USC</p>
<p><a href="https://www.linkedin.com/in/sparshg3011/">LinkedIn</a> · <a href="mailto:sparshgupta643@gmail.com">Email</a> · <a href="https://sparsh-gupta-portfolio.vercel.app/#projects">Portfolio</a></p>
</div>
<hr />
<h2>About</h2>
<p>I'm a software engineer and a Master's student in Computer Science at USC, focused on backend systems, distributed architecture, and applied AI. Most of my work is about designing services that stay fast, correct, and resilient under real-world conditions.</p>
<p>What draws me to agentic AI and RAG is the problem of making language models behave predictably inside production infrastructure, where reliability matters as much as intelligence. I care about systems that are dependable by design, and I'm looking for work where strong systems thinking and practical AI experience come together to build products people can rely on.</p>
<hr />
<h2>Tech Stack</h2>
<table>
<thead>
<tr>
<th>Area</th>
<th>Technologies</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Backend &amp; APIs</strong></td>
<td>Node.js, FastAPI, Fastify, Express, .NET, GraphQL, REST</td>
</tr>
<tr>
<td><strong>Distributed Systems &amp; Infrastructure</strong></td>
<td>Apache Kafka, RabbitMQ, Redis, Docker, AWS, PostgreSQL, MongoDB</td>
</tr>
<tr>
<td><strong>Agentic AI &amp; ML</strong></td>
<td>LangGraph, LangChain, OpenAI, Claude API, PyTorch, HuggingFace, ChromaDB, Pinecone, FAISS</td>
</tr>
<tr>
<td><strong>Languages</strong></td>
<td>Python, TypeScript, JavaScript, C++, C#, SQL</td>
</tr>
<tr>
<td><strong>Frontend</strong></td>
<td>React, Next.js, Vue.js, Flutter, Tailwind</td>
</tr>
</tbody>
</table>
<hr />
<h2>Featured Projects</h2>
<h3>Systems, Distributed Infrastructure &amp; Backends</h3>
<p><strong><a href="https://github.com/Sparshg3011/Timefork">Timefork</a></strong> — A durable execution runtime that keeps AI agents crash-proof. Every step an agent takes is written to an append-only event log in Postgres and replayed deterministically, so a worker killed mid-task resumes exactly where it stopped. A two-phase intent/completion protocol with idempotency keys and fencing tokens guarantees side effects run once and only once, even when stale workers linger. <em>(Python · PostgreSQL)</em></p>
<p><strong><a href="https://github.com/Sparshg3011/vector-search-engine">Vector Search Engine (HNSW)</a></strong> — A hand-built implementation of the HNSW approximate nearest-neighbor algorithm in pure NumPy, with the layered navigable graph, diversity heuristic, and beam search all written from scratch. It behaves like a production vector index while staying small and readable, and ships with a CI suite covering recall, graph reachability, and save/load determinism. <em>(Python · NumPy)</em></p>
<p><strong><a href="https://github.com/rohang1411/Infinitune-Realtime-LLM-Fine-Tuning-Framework">Infinitune</a></strong> — A distributed streaming framework for adapting large language models while they stay in production. Three Kafka-coordinated services stream LoRA adapter updates through the pipeline so a served model keeps improving in near real time, with no downtime during a swap. <em>(Apache Kafka · PyTorch · HuggingFace · LoRA)</em></p>
<p><strong><a href="https://github.com/Sparshg3011/rentcasaya">CasaYa</a></strong> — A rental marketplace built on an event-driven RabbitMQ microservice backend. It runs the full tenant journey — listing discovery, automated screening, payments, and digital lease signing — as decoupled services that stay responsive under load. <em>(Next.js · Node.js · RabbitMQ · Redis · Supabase)</em></p>
<h3>Agentic AI, RAG &amp; Applied ML</h3>
<p><strong><a href="https://github.com/Sparshg3011/litmus">Litmus</a></strong> — An autonomous agent that puts machine-learning papers to the test by re-running them. It reads a paper and its dataset, generates the analysis pipeline the paper describes using the Claude API, and executes that pipeline inside a network-isolated Docker sandbox. A bounded self-repair loop feeds runtime errors back into code generation, and every result is checked against pinned ground-truth data so the agent can never grade its own output. <em>(Python · Claude API · Docker)</em></p>
<p><strong><a href="https://github.com/Sparshg3011/VocaMind">VocaMind</a></strong> — A real-time voice-agent platform for outbound calling. It stitches together speech recognition, text-to-speech, and live sentiment analysis to hold natural multi-turn conversations and adapt its tone as the call unfolds, with dialog state persisted so long conversations stay coherent. <em>(Fastify · Next.js · Twilio · ElevenLabs · MongoDB)</em></p>
<p><strong><a href="https://github.com/Sparshg3011/PodSearch">PodSearch</a></strong> — A semantic search engine over long-form podcast audio that answers natural-language questions with the exact timestamp where the answer appears. An agentic fact-checking layer verifies each retrieved passage before responding, keeping answers grounded in what was actually said. <em>(FastAPI · ChromaDB · GPT-4 · LangChain)</em></p>
<p><strong><a href="https://github.com/Sparshg3011/HaluGuard">HaluGuard</a></strong> — A contrastive context-selection method that curbs hallucination in code-generation models. It scores candidate snippets of repository context and selects the most relevant ones, so the model conditions on the right code before it writes anything. <em>(PyTorch · Transformers · UniXcoder)</em></p>
<hr />
<h2>Hackathon Projects</h2>
<p><strong>Clara</strong> · <em>UC Berkeley AI Hackathon</em> — <em>One line from you and I'll write it up.</em></p>
<p><strong><a href="https://github.com/Sparshg3011/HealthSwarm">HealthSwarm</a></strong> · <em>LA Hacks</em> — Multi-agent healthcare orchestration. A FastAPI backend coordinates a swarm of autonomous agents over a LangGraph state machine that searches clinics and places live outbound voice calls, carrying a patient from request to booked appointment without a human in the loop. <em>(LangGraph · FastAPI · MongoDB · Twilio · ElevenLabs)</em></p>
<p><strong>SOLA</strong> · <em>Hack4SC</em> — <em>One line from you and I'll write it up.</em></p>
<p><strong>Nina</strong> · <em>CalHacks 12.0</em> — <em>One line from you and I'll write it up.</em></p>
<hr />
<h2>Research &amp; Achievements</h2>
<ul>
<li><strong>Co-author, <em>Cognitive Weave</em></strong> — a hybrid vector and graph memory orchestrator for multi-agent systems (<a href="https://arxiv.org/abs/2506.08098">arXiv:2506.08098</a>).</li>
<li><strong>Selected for Summer of Open AI Research</strong> — built context compression using AST and LSP analysis to reduce hallucinations in code-generation agents.</li>
<li><strong>Research Assistant, USC ISI (INK Lab)</strong> — a structured survey of LLM watermarking and distillation privacy risks.</li>
</ul>
<hr />
<h2>Education</h2>
<ul>
<li><strong>University of Southern California</strong> — M.S. in Computer Science <em>(2025–2026)</em></li>
<li><strong>Guru Gobind Singh Indraprastha University</strong> — B.Tech in Computer Science and Engineering</li>
</ul>
<hr />
<div align="center">
<p>Let's connect — <a href="https://www.linkedin.com/in/sparshg3011/">LinkedIn</a> · <a href="mailto:sparshgupta643@gmail.com">Email</a> · <a href="https://sparsh-gupta-portfolio.vercel.app/#projects">Portfolio</a></p>
<p>Los Angeles, CA · Open to Backend, Distributed Systems, and Agentic AI roles</p>
</div>
    </article>
  </div>
</body></html>
