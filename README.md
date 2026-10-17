<!--
SEO: llmops radar
-->

<div align="center">

# LLMOps Radar

Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment

[![Stars](https://img.shields.io/github/stars/linny006/llmops-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llmops-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llmops-radar?style=for-the-badge)](https://github.com/linny006/llmops-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-50-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

A continuously-updated tracker that discovers, catalogs, and scores new LLMOps tools as they appear on GitHub and Product Hunt. Unlike static awesome-lists, it runs daily via GitHub Actions to surface tools launched in the past week across categories like observability, prompt management, cost tracking, and gateways.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-17 13:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [xeeshan16/agent-replay](https://github.com/xeeshan16/agent-replay) | 0 | Python | 2026-10-17 | Record, replay and regression-test AI agent runs: ingests OpenTelemetry GenAI traces into PostgreSQL, replays tool calls |
| 2 | [IlaKhan17/proofstep](https://github.com/IlaKhan17/proofstep) | 0 | Python | 2026-10-17 | Evaluation CI, observability, and trajectory testing for production AI agents. The exit code your CI acts on and the ver |
| 3 | [negativexq/knowledge-base-rag](https://github.com/negativexq/knowledge-base-rag) | 1 | Python | 2026-10-17 | Production-style multilingual RAG with tenant-safe retrieval, evidence provenance, deterministic validation, observabili |
| 4 | [korczis/prismatic-majordomus](https://github.com/korczis/prismatic-majordomus) | 0 | Rust | 2026-10-17 | A lightweight supervisory control layer for AI-assisted work: one policy, generated instructions for every AI tool, dura |
| 5 | [ngu-gif/genai-role-playbook](https://github.com/ngu-gif/genai-role-playbook) | 1 | HTML | 2026-10-17 | GenAI Career Roadmap 2026 🚀 \| AI Job Paths & Skills Guide |
| 6 | [tahircengiz/LLMScale](https://github.com/tahircengiz/LLMScale) | 0 | TypeScript | 2026-10-17 | Estimate LLM VRAM — model weights, KV cache, context window & concurrent users — and find the right GPU. Live Hugging Fa |
| 7 | [digline/digline](https://github.com/digline/digline) | 9 | Python | 2026-10-17 | Regression testing for LLM applications in CI. Sample your reference and a score drop is read against how much that scor |
| 8 | [linny006/llmops-radar](https://github.com/linny006/llmops-radar) | 3 | Python | 2026-10-17 | Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment |
| 9 | [Analytical-Tradecraft-Technologies/llm-temporal-worker](https://github.com/Analytical-Tradecraft-Technologies/llm-temporal-worker) | 1 | Go | 2026-10-17 | Temporal workers and clients for wrapping access to different LLMs |
| 10 | [anthony-chaudhary/fak](https://github.com/anthony-chaudhary/fak) | 41 | Go | 2026-10-17 | Agentic Runtime |
| 11 | [mozilla-ai/otari](https://github.com/mozilla-ai/otari) | 597 | Python | 2026-10-17 | Open-source, OpenAI-compatible LLM gateway you run yourself. One endpoint for 40+ providers, with virtual keys, budgets, |
| 12 | [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | 30604 | TypeScript | 2026-10-17 | Composio powers 1000+ toolkits, tool search, context management, authentication, and a sandboxed workbench to help you b |
| 13 | [BerriAI/litellm](https://github.com/BerriAI/litellm) | 61434 | Python | 2026-10-17 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tra |
| 14 | [vllm-project/vllm-ascend](https://github.com/vllm-project/vllm-ascend) | 2995 | Python | 2026-10-17 | Community maintained hardware plugin for vLLM on Huawei Ascend |
| 15 | [ahmeddoghri/vllm-cost-router](https://github.com/ahmeddoghri/vllm-cost-router) | 0 | Python | 2026-10-17 | Routes, caches, and batches LLM requests: 73% cheaper. Now also measures whether the routing is correct, which the keywo |
| 16 | [ahmeddoghri/speculabench](https://github.com/ahmeddoghri/speculabench) | 0 | Python | 2026-10-17 | Model what speculative decoding actually buys you, no GPU required. Found the i.i.d.-agreement assumption was hiding a r |
| 17 | [BurraRohan/PersonaAI](https://github.com/BurraRohan/PersonaAI) | 0 | Python | 2026-10-17 | Multi-agent LinkedIn branding system with ReAct tool-calling, human-in-the-loop review, full agent traces, and a securit |
| 18 | [GetBusbar/busbar](https://github.com/GetBusbar/busbar) | 196 | Rust | 2026-10-17 | The execution control plane for AI agents. Govern every model request, MCP tool call, A2A delegation, and downstream act |
| 19 | [ahmeddoghri/kvsqueeze](https://github.com/ahmeddoghri/kvsqueeze) | 0 | Python | 2026-10-17 | How much KV cache can you throw away before the model forgets? Found the H2O-style policy was freezing the cache after i |
| 20 | [ahmeddoghri/guardrail-gate](https://github.com/ahmeddoghri/guardrail-gate) | 0 | Python | 2026-10-17 | Catches PII leaks and ungrounded claims in one pass. Now measured against the hard half: hallucinations that reuse the s |
| 21 | [SourceShift/mini-ork](https://github.com/SourceShift/mini-ork) | 32 | Python | 2026-10-17 | Prove an AI-written fix actually fixes the bug. mini-ork certify reproduces the bug against your repo's own code, attack |
| 22 | [naim-munshi/metriqen-llm-serving-optimization](https://github.com/naim-munshi/metriqen-llm-serving-optimization) | 0 | Python | 2026-10-17 | Local LLM serving gateway in Go with FIFO admission scheduling, reproducible inference benchmarks, and quality evaluatio |
| 23 | [Ray0907/spanbox](https://github.com/Ray0907/spanbox) | 1 | Go | 2026-10-17 | Single-binary LLM observability for Claude Code, Codex and OpenAI/Gemini apps: OTLP or proxy in, SQLite inside, UI and a |
| 24 | [JavisBot-Service/javis-transparency](https://github.com/JavisBot-Service/javis-transparency) | 1 | Python | 2026-10-17 | Third-party-verifiable model-authenticity audit for the javis.bot Claude/GPT relay — open-source probe, runs on GitHub A |
| 25 | [toxicwind/ranch](https://github.com/toxicwind/ranch) | 0 | Rust | 2026-10-17 | The self-hosted LLM estate in one monorepo — local model serving, cloud provider routing, MCP gateway, build jobs. All O |
| 26 | [ALLMA-dev/allma-core](https://github.com/ALLMA-dev/allma-core) | 2 | TypeScript | 2026-10-17 | Open-source, 100% serverless AI-workflow orchestration on AWS Step Functions + Lambda — build, version & time-travel-deb |
| 27 | [AcruxCore/AcruxCore](https://github.com/AcruxCore/AcruxCore) | 11 | TypeScript | 2026-10-17 | Open-source LLMOps platform with prompt management, an OpenAI-compatible AI gateway, OpenTelemetry tracing, a versioned  |
| 28 | [gabrielk83/AntCV](https://github.com/gabrielk83/AntCV) | 1 | JavaScript | 2026-10-17 | Multi-agent job application orchestration platform with provider routing, validation, provenance, and ATS-aware document |
| 29 | [lgcorzo/llmops-python-package](https://github.com/lgcorzo/llmops-python-package) | 1 | Jupyter Notebook | 2026-10-17 | Dark Gravity LLMOps Standard: ISO/IEC/IEEE 42010 agent observability, prompt lineage, and runtime guardrails for autonom |
| 30 | [Peter-A-P/fraction-of-the-bill](https://github.com/Peter-A-P/fraction-of-the-bill) | 0 | Python | 2026-10-17 | A small fine-tuned model that matches frontier APIs on SEC filing extraction at a tenth of the per-call cost: QLoRA fine |
| 31 | [Peter-A-P/compliant-ai-gateway](https://github.com/Peter-A-P/compliant-ai-gateway) | 0 | Python | 2026-10-17 | Every model call through one library: raw-HTTP provider adapters, a cost ledger row and an OpenTelemetry span per call,  |
| 32 | [Peter-A-P/ai-release-gate](https://github.com/Peter-A-P/ai-release-gate) | 0 | Python | 2026-10-17 | No prompt or model change ships unless proven not to have regressed: calibrated judges, confidence intervals, CI gating, |
| 33 | [hjongc/openrouter-endpoint-watch](https://github.com/hjongc/openrouter-endpoint-watch) | 0 | Python | 2026-10-17 | Daily snapshots and diffs of OpenRouter endpoint metadata: catch quantization flips and vanished providers before your p |
| 34 | [veerarakesh56/warden](https://github.com/veerarakesh56/warden) | 0 | Python | 2026-10-17 | AI incident-response orchestrator: the model proposes, a deterministic verifier decides. LangGraph + verified redaction  |
| 35 | [runcycles/cycles-server-events](https://github.com/runcycles/cycles-server-events) | 1 | Java | 2026-10-17 | Signed webhook/event delivery for Cycles — retries, HMAC, replay, audit, governance events |
| 36 | [garcetemedinamateoandres-sketch/agent-deployment-orchestrator](https://github.com/garcetemedinamateoandres-sketch/agent-deployment-orchestrator) | 1 | HTML | 2026-10-17 | 🚀 AI Agent Deployment on GCP 2026: Fast-Track Production Templates & CI/CD |
| 37 | [DiogoRibeiro7/rag-quality-engine](https://github.com/DiogoRibeiro7/rag-quality-engine) | 0 | Jupyter Notebook | 2026-10-17 | Evaluation-first RAG and LLMOps platform for production-grade document QA, tracing, regression testing, and cost-aware e |
| 38 | [runcycles/cycles-server](https://github.com/runcycles/cycles-server) | 5 | Java | 2026-10-17 | Self-hosted runtime authority server for AI agents — budgets, risk, actions, tenant isolation |
| 39 | [vivek-541/vivek-541](https://github.com/vivek-541/vivek-541) | 4 | HTML | 2026-10-17 | AI Engineer building production-grade ML systems \| LLMs, RAG, ML Pipelines \| Python, TensorFlow, LangChain \| Open to opp |
| 40 | [SynaLinks/synalinks](https://github.com/SynaLinks/synalinks) | 464 | Python | 2026-10-17 | Keras based framework for neuro-symbolic LM systems |
| 41 | [BudEcosystem/simulator](https://github.com/BudEcosystem/simulator) | 4 | Python | 2026-10-17 | Decoder only, Encoder only, Diffusion model simulation for SLO, Memory, Infra calculations. For model inference and trai |
| 42 | [santifer/cv-santiago](https://github.com/santifer/cv-santiago) | 858 | HTML | 2026-10-17 | Interactive CV with AI chat integration. Built with React 19, TypeScript, Claude API. Chat with my AI avatar about my ex |
| 43 | [Amz34/awesome-agent-infrastructure](https://github.com/Amz34/awesome-agent-infrastructure) | 1 | Python | 2026-10-17 | A live-checked index of production-grade, self-hostable building blocks for AI agents and LLM workloads. |
| 44 | [sergey-homenko/llm_cost_tracker](https://github.com/sergey-homenko/llm_cost_tracker) | 46 | Ruby | 2026-10-17 | LLM spend tracking and budgets for Rails — by user, feature, or any tag, in your own database, no proxy. |
| 45 | [OmurBianchi727/llmix](https://github.com/OmurBianchi727/llmix) | 0 | Python | 2026-10-17 | Production LLM call layer for AI agents and tools: keep OpenAI/Anthropic/AI SDK/LiteLLM, hot-swap models with MDA preset |
| 46 | [JoniMartin27/lookspan](https://github.com/JoniMartin27/lookspan) | 7 | TypeScript | 2026-10-17 | Local-first observability dashboard for AI agents. MCP-native. Look at every span your agents emit. |
| 47 | [data-gras/savi-sdk](https://github.com/data-gras/savi-sdk) | 0 | Python | 2026-10-17 | Lightweight observability SDK for LLM cost, latency, and PII, that wraps OpenAI, Anthropic, Bedrock, Cohere, Mistral & V |
| 48 | [scttfrdmn/hf-bedrock-map](https://github.com/scttfrdmn/hf-bedrock-map) | 1 | Go | 2026-10-17 | Is a Hugging Face model already served by Amazon Bedrock? Daily-refreshed HF↔Bedrock mapping (US regions) with a free st |
| 49 | [Cyrax321/CONTINUUM](https://github.com/Cyrax321/CONTINUUM) | 24 | Python | 2026-10-17 | CONTINUUM: Verifiable semantic recovery for long-running AI agents. Semantic checkpoints (not conversation dumps), an id |
| 50 | [laurentross/llmaker](https://github.com/laurentross/llmaker) | 0 | Go | 2026-10-17 | Selfhost modern LLM stacks. Run the whole fleet from your terminal |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
