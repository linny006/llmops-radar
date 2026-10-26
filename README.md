<!--
SEO: llmops radar
-->

<div align="center">

# LLMOps Radar

Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment

[![Stars](https://img.shields.io/github/stars/linny006/llmops-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llmops-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llmops-radar?style=for-the-badge)](https://github.com/linny006/llmops-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-9-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-26 17:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [anthony-chaudhary/fak](https://github.com/anthony-chaudhary/fak) | 42 | Go | 2026-10-26 | Agentic Runtime |
| 2 | [01men/ybkkasi](https://github.com/01men/ybkkasi) | 1 | JavaScript | 2026-10-26 | One control plane for every AI asset — MCP servers, skills, agents, AI apps. Self-hosted ledger with lifecycle state mac |
| 3 | [piotrekno1/second-shift](https://github.com/piotrekno1/second-shift) | 1 | Python | 2026-10-26 | Scheduled agent tasks for your repositories, defined in Git. Approved access, sandboxed runs, a full audit trail. |
| 4 | [umars28/llm-platform](https://github.com/umars28/llm-platform) | 0 | Python | 2026-10-26 | Seven components for building and operating LLM systems: hybrid retrieval, evaluation gating, OpenTelemetry tracing, cos |
| 5 | [sarkars/agent-failure-modes](https://github.com/sarkars/agent-failure-modes) | 1 | Python | 2026-10-26 | Agent Failure Patterns - A field guide to how AI agents fail in production - documented failure patterns, root causes, a |
| 6 | [Yacine-ai-tech/RAGeval](https://github.com/Yacine-ai-tech/RAGeval) | 0 | Python | 2026-10-26 | LLM and RAG evaluation library: multi-judge consensus with a disagreement alarm, bootstrap confidence intervals and Open |
| 7 | [xuerp/ai-knowledge-explorer](https://github.com/xuerp/ai-knowledge-explorer) | 0 | Python | 2026-10-26 | AI Radar \| 基于证据的 AI 技术研究与选型平台。React + FastAPI，提供可核验官方资料与可复现作品集入口。 |
| 8 | [Keesan12/martin-loop](https://github.com/Keesan12/martin-loop) | 393 | TypeScript | 2026-10-26 | Run coding agents without babysitting them. Keep jobs focused, bounded, checked and accountable from start to finish. Fi |
| 9 | [vllm-project/vllm-ascend](https://github.com/vllm-project/vllm-ascend) | 3017 | Python | 2026-10-26 | Community maintained hardware plugin for vLLM on Huawei Ascend |
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
