<!--
SEO: llmops radar
-->

<div align="center">

# LLMOps Radar

Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment

[![Stars](https://img.shields.io/github/stars/linny006/llmops-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llmops-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llmops-radar?style=for-the-badge)](https://github.com/linny006/llmops-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-17-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-26 10:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [langfuse/langfuse](https://github.com/langfuse/langfuse) | 36509 | TypeScript | 2026-10-26 | 🪢 Open source agent evals & observability: Trace, evaluate, and improve LLM applications with one open platform. |
| 2 | [ThakiCloud/thakicloud.github.io](https://github.com/ThakiCloud/thakicloud.github.io) | 4 | JavaScript | 2026-10-26 | ThakiCloud Tech Blog |
| 3 | [dheerajkarwasra/spanlight](https://github.com/dheerajkarwasra/spanlight) | 0 | Python | 2026-10-26 | Open-source LLM observability. See every prompt, completion, token, cost, latency and error as traces and sessions. Pyth |
| 4 | [mlflow/mlflow](https://github.com/mlflow/mlflow) | 28537 | Python | 2026-10-26 | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, eva |
| 5 | [dynamiq-ai/dynamiq](https://github.com/dynamiq-ai/dynamiq) | 1071 | Python | 2026-10-26 | Dynamiq is an orchestration framework for agentic AI and LLM applications |
| 6 | [digline/digline](https://github.com/digline/digline) | 9 | Python | 2026-10-26 | Regression testing for LLM applications in CI. Sample your reference and a score drop is read against how much that scor |
| 7 | [Phat1911/Tributary](https://github.com/Phat1911/Tributary) | 5 | Rust | 2026-10-26 | Self-hostable AI token pools — govern your org's AI usage with per-member keys, quotas, and leak detection; or deposit s |
| 8 | [alibaba/rtp-llm](https://github.com/alibaba/rtp-llm) | 1376 | Python | 2026-10-26 | RTP-LLM: Alibaba's high-performance LLM inference engine for diverse applications. |
| 9 | [comet-ml/opik](https://github.com/comet-ml/opik) | 22930 | Python | 2026-10-26 | Debug, evaluate, and monitor your LLM applications, RAG systems, and agentic workflows with comprehensive tracing, autom |
| 10 | [garcetemedinamateoandres-sketch/agent-deployment-orchestrator](https://github.com/garcetemedinamateoandres-sketch/agent-deployment-orchestrator) | 1 | HTML | 2026-10-26 | 🚀 AI Agent Deployment on GCP 2026: Fast-Track Production Templates & CI/CD |
| 11 | [radicalbit/radicalbit-ai-gateway](https://github.com/radicalbit/radicalbit-ai-gateway) | 72 | Python | 2026-10-26 | Radicalbit AI Gateway |
| 12 | [mloda-ai/mloda](https://github.com/mloda-ai/mloda) | 96 | Python | 2026-10-26 | mloda.ai - Open Data Access for AI and ML. Plugin-based. Traceable. Framework-agnostic. |
| 13 | [euron-sde-team/euron-open-context-forge](https://github.com/euron-sde-team/euron-open-context-forge) | 0 | Python | 2026-10-26 | Self-hosted context optimizer for LLM apps: cuts input tokens 90% while keeping every critical fact and citation, with e |
| 14 | [agentcost-ai/agentcost-backend](https://github.com/agentcost-ai/agentcost-backend) | 3 | Python | 2026-10-26 | FastAPI backend for AgentCost: LLM event ingestion, cost attribution, budgets and analytics. |
| 15 | [agentcost-ai/agentcost-dashboard](https://github.com/agentcost-ai/agentcost-dashboard) | 2 | TypeScript | 2026-10-26 | Next.js dashboard for AgentCost: spend by agent, workflow and model, with budget guardrails. |
| 16 | [decimal-labs/decimalai-python](https://github.com/decimal-labs/decimalai-python) | 1 | Python | 2026-10-26 | Python SDK for agent evals and skill routing — measure a skill's real lift before you trust it |
| 17 | [euron-sde-team/euron-open-smart-router](https://github.com/euron-sde-team/euron-open-smart-router) | 0 | Python | 2026-10-26 | Self-hosted, OpenAI-compatible model router: the right AI model for every request. Measured quality, health-aware fallba |
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
