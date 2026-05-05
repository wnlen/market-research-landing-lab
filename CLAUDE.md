# CLAUDE.md

## Repo Purpose

This repository is a market research and landing-strategy decision repository.
It is not a production code repository.

The goal is to help decide:

1. short-term cashflow direction
2. long-term moat direction
3. a fusion path between the two
4. the first executable MVP

## Working Rules

- Use Chinese for analysis unless a task explicitly requires another language.
- Do not start product coding in this repository.
- Do not expand research endlessly.
- Every material update should produce one of:
  - a decision
  - a rejection
  - a next verification step
- Keep raw notes and final judgments separate.
- Keep one file focused on one topic.
- Never present unverified market claims as facts.
- Always separate `证据 / 推断 / 决策`.
- If evidence is weak, say so directly.

## Boundary

- This repo is for decision support before execution.
- Do not create frontend, backend, app, or database code here.
- Do not auto-run research tasks unless explicitly asked.
- Do not turn assumptions into conclusions.

## Bootstrap

When the user first opens a freshly-derived copy of this template and says
"开始这个项目" / "启动项目" / "初始化这个项目" / "start this project",
invoke the `start-project` skill to collect executor premises
and fill `docs/00-research-question.md` interactively.

## Expected Output For Each Task

1. files changed
2. decision produced
3. unresolved questions
4. next recommended task

## Graduation Reminder

Research should stop when the team can clearly answer:

1. what to build first
2. what not to build
3. what the 7-day demo is
4. what the 30-day MVP is
5. what the first monetization point is
6. how the short-term project feeds the long-term moat
