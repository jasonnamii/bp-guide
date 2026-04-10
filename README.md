# bp-guide

> 🇰🇷 [한국어 README](./README.ko.md)

**VC-grade business plan writing guide — YC, Sequoia, and a16z frameworks unified into a single 11-section standard.**

## Prerequisites

- **Obsidian Vault** — vault path referenced for document storage
- **Claude Cowork or Claude Code** environment

## Goal

Different VCs read business plans differently. BP-Guide integrates all three reading patterns into a unified 11-section framework that covers investor expectations across the entire ecosystem. A single, well-written plan works everywhere.

## When & How to Use

Use this skill when writing a business plan, pitch deck, or strategic overview for investors. Structure: 30-second scan tier → 3-minute check tier → 10-minute deep read tier. Each section has clear success criteria and writing patterns.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Seed round pitch | `"bp-guide: write our business plan for Y Combinator"` | 11-section framework optimized for YC; headline→traction emphasized |
| Series A fundraising | `"Business plan for Sequoia pitch: enterprise SaaS"` | Tailored to Sequoia narrative depth; deep section on GTM, unit economics |
| Acquisition positioning | `"bp-guide: position for strategic acquisition talks"` | 11 sections emphasizing strategic fit, tech differentiation, revenue metrics |

## Key Features

- Unified 11-section framework integrating YC, Sequoia, and a16z best practices
- Three-tier reading structure: 30-second scan, 3-minute check, 10-minute deep read
- Investor reading pattern embedded: headline and traction emphasized in early sections
- Success criteria for each section with real-world examples

## Works With

- **[financial-model](https://github.com/jasonnamii/financial-model)** — bp-guide sections integrate financial-model outputs
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill diagnoses business strength; bp-guide structures it for investors
- **[deliverable-engine](https://github.com/jasonnamii/deliverable-engine)** — deliverable-engine formats plans as polished PDFs or pitch decks

## Installation

```bash
git clone https://github.com/jasonnamii/bp-guide.git ~/.claude/skills/bp-guide
```

## Update

```bash
cd ~/.claude/skills/bp-guide && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
