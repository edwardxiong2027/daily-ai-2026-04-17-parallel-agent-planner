# Parallel Agent Planner

A tiny static web app for splitting a software backlog across multiple AI coding agents.

## Why this matters
This project is tied to two timely themes from the last 24 hours:

1. OpenAI's **Codex for (almost) everything** update said Codex can now run **multiple agents in parallel**, operate the computer, use the web, and work across more of the software lifecycle.
2. TechCrunch reported that **Factory** raised **$150M at a $1.5B valuation** to build **multi-model AI coding workflows** for enterprise teams.

The result is a tiny planner that helps you answer a practical question before you spin up agents: **is this backlog actually parallelizable, and where will coordination drag kill the speedup?**

## Features
- Paste a backlog as `task | type | points`
- Choose agent count, routing strategy, and context overhead
- Compare single-agent vs parallel completion time
- View automatic task routing into agent lanes
- Get model-fit suggestions per task type

## Demo link
Live URL: _to be filled after deploy_

## Build / run locally
Because this is a static site, no build step is required.

```bash
cd /opt/data/workspace/daily-ai-2026-04-17-parallel-agent-planner
python3 -m http.server 8123
```

Then open <http://localhost:8123>.

## Sources
- OpenAI — Codex for (almost) everything: https://openai.com/index/codex-for-almost-everything/
- TechCrunch — Factory hits $1.5B valuation to build AI coding for enterprises: https://techcrunch.com/2026/04/16/factory-hits-1-5b-valuation-to-build-ai-coding-for-enterprises/

## License
MIT
