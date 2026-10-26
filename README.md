<!--
SEO: llmops radar
-->

<div align="center">

# LLMOps Radar

Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment

[![Stars](https://img.shields.io/github/stars/linny006/llmops-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llmops-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llmops-radar?style=for-the-badge)](https://github.com/linny006/llmops-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-15-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-26 13:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [Haohao-end/openagent](https://github.com/Haohao-end/openagent) | 774 | Python | 2026-10-26 | What if OpenAI Deep Research and Dify were one platform? OpenAgent — harness architecture for rapidly building vertical  |
| 2 | [sergey-homenko/llm_cost_tracker](https://github.com/sergey-homenko/llm_cost_tracker) | 45 | Ruby | 2026-10-26 | LLM spend tracking and budgets for Rails — by user, feature, or any tag, in your own database, no proxy. |
| 3 | [NVIDIA-NeMo/nemo-helix](https://github.com/NVIDIA-NeMo/nemo-helix) | 128 | Python | 2026-10-26 | NeMo Helix: Make the agents you ship faster, more accurate, and safer. |
| 4 | [api7/aisix](https://github.com/api7/aisix) | 207 | Rust | 2026-10-26 | Open-source AI gateway for LLMs & AI agents, built in Rust. One OpenAI-compatible API for OpenAI, Anthropic, Gemini, Bed |
| 5 | [AixleHQ/flow](https://github.com/AixleHQ/flow) | 27 | Ruby | 2026-10-26 | Aixle Flow — orchestrate coding agents through durable, inspectable workflows. |
| 6 | [andypalmi/amicu](https://github.com/andypalmi/amicu) | 1 | Rust | 2026-10-26 | Terraform for your own LLMs: an open-source CLI that deploys vLLM and llama.cpp to your own machine or to GPU cloud prov |
| 7 | [dyronrh/awesome-agentops-landscape](https://github.com/dyronrh/awesome-agentops-landscape) | 23 | Python | 2026-10-26 | A curated list of the best AgentOps tools for 2026 — observability, tracing, evaluation, cost monitoring, and guardrails |
| 8 | [cubxxw/blog](https://github.com/cubxxw/blog) | 30 | JavaScript | 2026-10-26 | 顶级审美的个人博客！！！写一些关于 AI、Agent、技术、产品、营销、一些生活思考，个人成长类的精文 |
| 9 | [xuerp/ai-knowledge-explorer](https://github.com/xuerp/ai-knowledge-explorer) | 0 | Python | 2026-10-26 | AI Radar \| 基于证据的 AI 技术研究与选型平台。React + FastAPI，提供可核验官方资料与可复现作品集入口。 |
| 10 | [runcycles/cycles-dashboard](https://github.com/runcycles/cycles-dashboard) | 0 | TypeScript | 2026-10-26 | AI agent governance dashboard for Cycles — budgets, action authority, tenants, webhooks, reservations, audit |
| 11 | [runcycles/.github](https://github.com/runcycles/.github) | 0 | Shell | 2026-10-26 | GitHub org config, CI workflows, and community health files for Cycles |
| 12 | [a-novel/service-genai](https://github.com/a-novel/service-genai) | 2 | Go | 2026-10-26 | Durable execution for AI provider calls: crash-safe, idempotent and pollable. |
| 13 | [GeiserX/LynxPrompt](https://github.com/GeiserX/LynxPrompt) | 54 | TypeScript | 2026-10-26 | Self-hosted & federated platform for AI IDE/Tools Rules and Commands via WebUI & CLI - Generate, browse, store, share AG |
| 14 | [delivstat/swarmkit](https://github.com/delivstat/swarmkit) | 3 | Python | 2026-10-26 | Open-source runtime for governed multi-agent AI — define agents, tools and human-approval gates as data (YAML), run unde |
| 15 | [santifer/cv-santiago](https://github.com/santifer/cv-santiago) | 857 | HTML | 2026-10-26 | Interactive CV with AI chat integration. Built with React 19, TypeScript, Claude API. Chat with my AI avatar about my ex |
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
