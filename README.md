<div align="center">

# Market Research Landing Lab

**Stop collecting. Start deciding.**

A Claude Code–native template for turning market research into executable business decisions.
Built-in graduation conditions tell you exactly when to stop researching and start building.

[English](README.md) · [中文](README.zh.md)

[![Use this template](https://img.shields.io/badge/-Use%20this%20template-2ea44f?style=flat-square&logo=github)](../../generate)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-ready-blueviolet?style=flat-square)](https://claude.ai/code)

</div>

---

## The Problem

Most market research never ends. You keep adding data, refining analysis, and postponing the one decision that matters. This template forces a different contract: research exists to produce a decision, not to delay it.

---

## Quick Start

**Just created a new repo from this template? One command to begin:**

```
Open Claude Code and type:  start this project
```

Claude runs a four-round interview (skills → channels → moat → constraints) and writes your answers into `docs/00-research-question.md`.

**Have existing docs?** Drop them into `research/raw/` first. Claude reads them before each round and opens with its understanding of that area — you react, correct, or expand rather than narrating from scratch. The docs are reference material, not answers; everything still goes through you.

Either way, Claude shows you the full proposed content for your approval **before** writing anything.

> Equivalent triggers: "begin this project" · "initialize this project" · "开始这个项目"
>
> If Claude doesn't auto-recognize: say "use the start-project skill"

---

## The Pipeline

Every derived project follows the same ten-document sequence:

```
docs/00   Research Question   ──  Define the decision before you research
docs/01   Market Map          ──  Landscape, segments, key players
docs/02   User Segments       ──  Who has the problem, who will pay
docs/03   Competitor Map      ──  First-screen hooks, pricing, weak spots
docs/04   Short-Term Options  ──  Paths to revenue within 30 days
docs/05   Long-Term Moat      ──  Defensible assets built in 12 months
docs/06   Fusion Strategy     ──  Where both paths share assets
docs/07   MVP Candidates      ──  Side-by-side comparable options
docs/08   Final Decision      ──  Locked direction, frozen reasoning
docs/09   Execution Roadmap   ──  Research ends here
```

---

## The Three-Segment Rule

Every entry in every document must separate:

```
Evidence   ──  What you actually observed. Sources required.
Inference  ──  Limited conclusions from that evidence. Confidence rated.
Decision   ──  Continue / eliminate / next verification step.
```

Weak evidence must be labeled as weak. Inference cannot be written in the Evidence section. No exceptions.

---

## Graduation Conditions

Research stops when all six questions have specific, executable answers:

- [ ] What to build first — a concrete product or service, not a direction
- [ ] What NOT to build — explicit exclusions with verifiable reasons
- [ ] 7-day demo scope — completable by one person in one week
- [ ] 30-day MVP scope — smallest version someone will pay for
- [ ] First revenue point — specific amount and payment scenario
- [ ] How the short-term project feeds the long-term moat — specific asset flow, not a slogan

---

## Directory Structure

```
.
├── .claude/
│   └── skills/start-project/    # Auto-triggered onboarding interview
├── ai/                          # Multi-agent handoff templates (Claude / Codex)
├── decisions/                   # Architecture Decision Records (ADRs)
├── docs/
│   ├── 00–09 *.md               # Fixed research pipeline
│   └── templates/               # Reusable tables and card formats
├── prompts/                     # Per-agent prompt library
├── research/
│   ├── raw/                     # Everything unprocessed: your own brainstorms, vision docs,
│   │                            # rough plans, external articles, interview notes, AI chat exports
│   ├── source-cards/            # Single-fact evidence cards
│   ├── competitor-cards/        # Standardized competitor profiles
│   └── user-cards/              # User pain points and interview notes
└── skills/                      # Workflow contracts for Claude
```

---

## Using This Template

1. Click **Use this template** → Create a new repository
2. Clone your new repo
3. Open Claude Code → type **"start this project"**
4. Complete the four-round interview (~5 min)
5. Start filling `docs/01` onward

**This base repo stays clean.** Never do domain-specific research here.
Derive a new repo per project. One project, one repo.

---

## What This Is Not

- Not a product code repository
- Not a place for frontend, backend, or app code
- Not a place to write market claims without sources
- Not a tool for open-ended research without a decision target
- Not a system that auto-generates conclusions from assumptions

---

## Multi-Agent Support

The `ai/` directory contains handoff templates for Claude Code, Codex, and ChatGPT.
Each agent operates on the same document structure with role-specific instructions in `AGENTS.md`.

---

<div align="center">

Research less. Decide more. Build sooner.

</div>
