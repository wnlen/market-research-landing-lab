# Raw Material Lifecycle Index

> Status: reusable raw material lifecycle template.
> Principle: `research/raw/` keeps traceable unprocessed material, but raw files should not be piled in the root directory.

## Directory Rules

| Directory | Purpose | Rule |
|-----------|---------|------|
| `inbox/` | New raw material not yet processed | Review, then move to `absorbed/`, `migration/`, or `deprecated/` |
| `absorbed/` | Raw material already absorbed into `docs/` or `decisions/` | Keep for traceability; no longer treated as active input |
| `migration/` | Material that belongs in a later product, docs, or execution repository | Keep as handoff input; do not expand into product specs here |
| `deprecated/` | Material explicitly rejected or not currently used | Keep history and record the rejection reason |

## Workflow

1. Put new brainstorms, articles, interview notes, imported docs, and AI chat exports into `research/raw/inbox/`.
2. When a document is synthesized into `docs/` or `decisions/`, move it to `research/raw/absorbed/`.
3. When a document is useful only for a downstream implementation repository, move it to `research/raw/migration/`.
4. When a document is explicitly not used, move it to `research/raw/deprecated/`.
5. Update this index whenever moving material between lifecycle states.

## Tracking Table

| File | Status | Absorbed into / target | Notes |
|------|--------|------------------------|-------|
| [待填写] | inbox / absorbed / migration / deprecated | [待填写] | [待填写] |

## Three-Segment Record

### 证据

- [待填写]

### 推断

- [待填写]

### 决策

- `research/raw/` uses lifecycle subdirectories.
- New raw material starts in `research/raw/inbox/`.
