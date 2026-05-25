# AGENTS.md

## Repo Role

This is a research and decision repository, not a production app repository.

## Agent Responsibilities

- Maintain clean markdown structure.
- Classify new docs before creating them: `docs/00-09` for the main research pipeline, `docs/product/` for product shape and first launch product design, `docs/audits/` for audits, and `docs/templates/` for reusable templates.
- Keep templates reusable.
- Turn rough notes into structured documents.
- Preserve the distinction between evidence, inference, and decision.
- Mark assumptions clearly.
- Refuse to invent market facts.
- Avoid product code unless explicitly requested in another repository.

## Output Standard

After each task, provide:

1. changed files
2. decision summary
3. assumptions
4. next verification step

## Research Guardrails

- New raw material belongs under `research/raw/inbox/`.
- Absorbed raw material belongs under `research/raw/absorbed/`.
- Product-repo or downstream execution input belongs under `research/raw/migration/`.
- Rejected or inactive raw material belongs under `research/raw/deprecated/`.
- Structured synthesis belongs under `docs/`.
- Product shape and first launch product design belong under `docs/product/`.
- Repository or decision-chain audits belong under `docs/audits/`.
- Final directional decisions belong under `decisions/`.
- If evidence is missing, say “证据不足” instead of filling gaps with guesses.

## Graduation Trigger

Once there is enough evidence to lock:

1. primary direction
2. backup direction
3. MVP scope
4. first revenue point
5. execution roadmap

the repository should stop expanding in breadth and start execution planning.
