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

> ⏰ Last updated: 2026-10-18 09:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [BerriAI/litellm](https://github.com/BerriAI/litellm) | 61465 | Python | 2026-10-18 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tra |
| 2 | [Phat1911/Tributary](https://github.com/Phat1911/Tributary) | 0 | Rust | 2026-10-18 | Self-hostable AI token pools — govern your org's AI usage with per-member keys, quotas, and leak detection; or deposit s |
| 3 | [antonij-simonovski/tracium](https://github.com/antonij-simonovski/tracium) | 3 | TypeScript | 2026-10-18 | Open-source, self-hosted LLM observability built on OpenTelemetry |
| 4 | [darrshangovender/semantic-cache](https://github.com/darrshangovender/semantic-cache) | 1 | Python | 2026-10-18 | Semantic cache for LLM responses using pgvector kNN — serves near-duplicate questions from cache instead of paying for t |
| 5 | [darrshangovender/llm-cost-tracker](https://github.com/darrshangovender/llm-cost-tracker) | 0 | Python | 2026-10-18 | Per-call token, cost and latency attribution for LLM apps, keyed by feature and user. Catches spend leaks that aggregate |
| 6 | [darrshangovender/prompt-versioner](https://github.com/darrshangovender/prompt-versioner) | 0 | Python | 2026-10-18 | Git-style version control for prompts with hash-stable weighted A/B routing. Diff, roll back, and split traffic between  |
| 7 | [darrshangovender/prompt-eval-toolkit](https://github.com/darrshangovender/prompt-eval-toolkit) | 0 | Python | 2026-10-18 | A/B test prompt versions on a dataset with paired-bootstrap p-values. Fails the build on a regression, so prompt changes |
| 8 | [darrshangovender/rag-eval-harness](https://github.com/darrshangovender/rag-eval-harness) | 0 | Python | 2026-10-18 | Production evals for RAG — faithfulness, recall@k, latency and cost — wired into CI so a prompt change can't merge on a  |
| 9 | [darrshangovender/multi-agent-orchestrator](https://github.com/darrshangovender/multi-agent-orchestrator) | 0 | Python | 2026-10-18 | Multi-agent orchestration with typed Pydantic handoffs, shared workspace memory, and full trace observability. Structure |
| 10 | [ZIZKA-AI-SL/ZizkaDB](https://github.com/ZIZKA-AI-SL/ZizkaDB) | 144 | Python | 2026-10-18 | Audit trail database for AI agents. Tamper-evident, checksum-backed decision logs with session replay and time-travel de |
| 11 | [toxicwind/ranch](https://github.com/toxicwind/ranch) | 0 | Rust | 2026-10-18 | The self-hosted LLM estate in one monorepo — local model serving, cloud provider routing, MCP gateway, build jobs. All O |
| 12 | [darrshangovender/guardrail](https://github.com/darrshangovender/guardrail) | 0 | Python | 2026-10-18 | Safety gateway for LLM inputs and outputs: prompt-injection detection, PII redaction, groundedness checks, schema repair |
| 13 | [darrshangovender/context-compress](https://github.com/darrshangovender/context-compress) | 0 | Python | 2026-10-18 | Prompt and RAG context compression with a fidelity evaluator — 48% fewer tokens at 100% fact recall, where naive truncat |
| 14 | [darrshangovender/cascade](https://github.com/darrshangovender/cascade) | 0 | Python | 2026-10-18 | Route each LLM call to the cheapest model that will get it right. Verifier-gated cascades with an offline threshold opti |
| 15 | [thequantumfalcon/kry](https://github.com/thequantumfalcon/kry) | 1 | Python | 2026-10-18 | Tamper-evident, stranger-verifiable receipts for LLM cost-savings — anyone can recompute your caching/routing savings ma |
| 16 | [linny006/llmops-radar](https://github.com/linny006/llmops-radar) | 3 | Python | 2026-10-18 | Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment |
| 17 | [digline/digline](https://github.com/digline/digline) | 9 | Python | 2026-10-18 | Regression testing for LLM applications in CI. Sample your reference and a score drop is read against how much that scor |
| 18 | [VKanee/opsmind-ai](https://github.com/VKanee/opsmind-ai) | 0 | Python | 2026-10-18 | Enterprise AI operations and incident intelligence platform with RAG, agent workflows, approvals, RBAC, audit trails, an |
| 19 | [cloudrift-ai/emmy](https://github.com/cloudrift-ai/emmy) | 111 | Python | 2026-10-18 | Optimized GPU compiler for LLM inference. Choose from a list of optimized recipes or optimize your own model via kernel  |
| 20 | [cubxxw/blog](https://github.com/cubxxw/blog) | 29 | JavaScript | 2026-10-18 | 顶级审美的个人博客！！！写一些关于 AI、Agent、技术、产品、营销、一些生活思考，个人成长类的精文 |
| 21 | [valteresj2/agent-hangar](https://github.com/valteresj2/agent-hangar) | 3 | Python | 2026-10-18 | One home for every AI agent. Build, test and ship agents once, then use them from Claude, ChatGPT, Codex, Cursor, VS Cod |
| 22 | [ferro-labs/ai-gateway](https://github.com/ferro-labs/ai-gateway) | 271 | Go | 2026-10-18 | Unified AI Gateway for 30+ LLMs (OpenAI, Anthropic, Bedrock, Azure etc) with Caching, Guardrails, A/B test & cost contro |
| 23 | [HikaruEgashira/otel-hooks](https://github.com/HikaruEgashira/otel-hooks) | 9 | Python | 2026-10-18 | AI Agent hooks for LLM Observability. |
| 24 | [Amz34/awesome-agent-infrastructure](https://github.com/Amz34/awesome-agent-infrastructure) | 1 | Python | 2026-10-18 | A live-checked index of production-grade, self-hostable building blocks for AI agents and LLM workloads. |
| 25 | [Xander-Xai/Beauty-Industry-RAG-QA-System](https://github.com/Xander-Xai/Beauty-Industry-RAG-QA-System) | 0 | Python | 2026-10-18 | Multimodal RAG QA for cosmetics regulation: hybrid retrieval, two-stage reranking, evidence gating that refuses unsuppor |
| 26 | [kushagrasoni/governed-iceberg-agent](https://github.com/kushagrasoni/governed-iceberg-agent) | 0 | Python | 2026-10-18 | The evidence trail for agentic data pipelines: an LLM agent proposes Apache Iceberg changes; guardrails, branch dry-runs |
| 27 | [Abilityai/trinity](https://github.com/Abilityai/trinity) | 669 | Python | 2026-10-18 | Self-hosted AI Agents Platform for AI Native companies. Claude Code, Codex, Gemini, OpenCode agents. Apache 2.0.   |
| 28 | [langfuse/langfuse](https://github.com/langfuse/langfuse) | 35985 | TypeScript | 2026-10-18 | 🪢 Open source agent evals & observability: Trace, evaluate, and improve LLM applications with one open platform. |
| 29 | [sophie-nguyenthuthuy/llm-pricing-history](https://github.com/sophie-nguyenthuthuy/llm-pricing-history) | 1 | Python | 2026-10-18 | Daily CI-refreshed history of LLM API pricing — snapshot + append-only change log for ~2,500 chat models (CSV, CC BY 4.0 |
| 30 | [llmspendguard/llm-spendguard](https://github.com/llmspendguard/llm-spendguard) | 0 | Python | 2026-10-18 | Know what an LLM job will cost before you run it — and prove your ledger matches the provider's bill. Pre-submit estimat |
| 31 | [xuerp/ai-knowledge-explorer](https://github.com/xuerp/ai-knowledge-explorer) | 0 | Python | 2026-10-18 | AI Radar：具备证据链、人工审核、知识图谱与可信 RAG 的 AI 技术情报平台 |
| 32 | [BurraRohan/PersonaAI](https://github.com/BurraRohan/PersonaAI) | 0 | Python | 2026-10-18 | Multi-agent LinkedIn branding system with ReAct tool-calling, human-in-the-loop review, full agent traces, and a securit |
| 33 | [anthony-chaudhary/fak](https://github.com/anthony-chaudhary/fak) | 41 | Go | 2026-10-18 | Agentic Runtime |
| 34 | [Chris0Jeky/llm-release-gate](https://github.com/Chris0Jeky/llm-release-gate) | 1 | Python | 2026-10-18 | An open-source CLI plus GitHub Action that prevents unsafe prompt, model, retrieval, tool, or configuration changes from |
| 35 | [cuihuan/awesome-ai-gateway](https://github.com/cuihuan/awesome-ai-gateway) | 130 | HTML | 2026-10-18 | ⚡ Awesome AI Gateway — pick an AI gateway from 160+ (LiteLLM, OpenRouter, Portkey, Kong, Higress, new-api, Bifrost) by c |
| 36 | [JavisBot-Service/javis-transparency](https://github.com/JavisBot-Service/javis-transparency) | 1 | Python | 2026-10-18 | Third-party-verifiable model-authenticity audit for the javis.bot Claude/GPT relay — open-source probe, runs on GitHub A |
| 37 | [gabrielk83/AntCV](https://github.com/gabrielk83/AntCV) | 1 | JavaScript | 2026-10-18 | Multi-agent job application orchestration platform with provider routing, validation, provenance, and ATS-aware document |
| 38 | [asadhanif3188/InferOps](https://github.com/asadhanif3188/InferOps) | 0 | Python | 2026-10-18 | AI platform reference architecture for LLM serving on Kubernetes, with reliability, observability, failure testing, and  |
| 39 | [Red1-Rahman/NiriZan](https://github.com/Red1-Rahman/NiriZan) | 3 | Jupyter Notebook | 2026-10-18 | Continuous Evaluation Infrastructure for Production AI |
| 40 | [Thijsm92940/ZizkaDB](https://github.com/Thijsm92940/ZizkaDB) | 0 | Python | 2026-10-18 | Audit trail database for AI agents. Tamper-evident, checksum-backed decision logs with session replay and time-travel de |
| 41 | [SUDARSHANCHAUDHARI/FoldBackAI](https://github.com/SUDARSHANCHAUDHARI/FoldBackAI) | 1 | Python | 2026-10-18 | Lossless context compression for LLM agents — fold it down, fold it back. Compresses tool outputs/logs before the model, |
| 42 | [willemwalsh930/juror](https://github.com/willemwalsh930/juror) | 0 | TypeScript | 2026-10-18 | Cheaper and better Greptile alternative runs on your own github actions. |
| 43 | [petit5297/turbular](https://github.com/petit5297/turbular) | 0 | Python | 2026-10-18 | A MCP server allowing LLM agents to easily connect and retrieve data from any database |
| 44 | [raulbutt11749/juror](https://github.com/raulbutt11749/juror) | 0 | TypeScript | 2026-10-18 | Cheaper and better Greptile alternative runs on your own github actions. |
| 45 | [raymond9992/trubrics-python](https://github.com/raymond9992/trubrics-python) | 0 | Python | 2026-10-18 | Product analytics for AI Assistants |
| 46 | [Analytical-Tradecraft-Technologies/llm-temporal-worker](https://github.com/Analytical-Tradecraft-Technologies/llm-temporal-worker) | 1 | Go | 2026-10-18 | Temporal workers and clients for wrapping access to different LLMs |
| 47 | [adams30165/llmaker](https://github.com/adams30165/llmaker) | 0 | Go | 2026-10-18 | Selfhost modern LLM stacks. Run the whole fleet from your terminal |
| 48 | [gabrieley60801/trubrics-python](https://github.com/gabrieley60801/trubrics-python) | 0 | Python | 2026-10-18 | Product analytics for AI Assistants |
| 49 | [chensl139-ok/switchboard-ai-router](https://github.com/chensl139-ok/switchboard-ai-router) | 5 | JavaScript | 2026-10-18 | Self-hosted AI model gateway with routing, tenant isolation, per-member API keys and a model playground. Lightweight mac |
| 50 | [PanagiotisCattaneo/trubrics-python](https://github.com/PanagiotisCattaneo/trubrics-python) | 0 | Python | 2026-10-18 | Product analytics for AI Assistants |
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
