# Metamorphosis

[![Support me on Patreon](https://img.shields.io/badge/Patreon-Support%20my%20work-FF424D?style=flat&logo=patreon&logoColor=white)](https://www.patreon.com/AndersBjarby)

METAMORPHOSIS adds governance to evolutionary AI in Claude Code. It runs multiple solution "timelines" that compete and evolve, but every significant decision passes through a Council of multi-model judges (Claude + GPT + Gemini) and humans, with an immutable Ledger recording everything.

## What it does

- **The Council** — multi-model judges plus humans (via Slack) review evolution decisions
- **Pattern plasmids** — successful patterns spread between timelines
- **Heritage prompts** — hybrids inherit distilled wisdom, not raw code
- **The Ledger** — an immutable record of all decisions for later audit
- **Co-evolution** — the Council improves based on outcomes
- **Governance tiers** — routine changes auto-approve; major and critical changes require full Council plus one or more humans

## Commands

- `/awaken "<goal>"` — start a new evolution with context detection
- `/evolve` — advance all timelines one generation
- `/status` — view ecosystem state
- `/cross α β` — crossover two timelines
- `/council` — manually invoke a Council review
- `/select` — choose the winner for production
- `/ledger` — query decision history

## Agents

`flux-core` (evolution engine with governance), `council` (multi-model + human governance), `heritage-extractor` (extract wisdom from elite parents), and `ledger-keeper` (record decisions immutably).

## Quick start

This is a Claude Code project — open it with Claude Code and drive it through the slash commands.

```bash
cd metamorphosis
claude
/awaken "Build authentication system"
```

## Tech

Claude Code (CLAUDE.md, `.claude/` agents and commands, plus a `genome/` and `data/` directory layout for traits, skills, evolutions, plasmids, winners, graveyard, ledger, and Council config). Markdown-based; no build step.
