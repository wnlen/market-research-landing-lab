# First Launch Product Design

> Status: placeholder.
> Purpose: translate the long-term product shape into a first launch product that can go live, serve real users, and meet the revenue standard.
> Boundary: do not write API specs, database schemas, pixel-level UI specs, or engineering tasks here.

## 1. Definition

```text
First launch product
= can go live
+ can serve real users
+ can meet the revenue standard
+ has explicit exclusions
+ feeds the long-term moat
```

## 2. Candidate Shape

- Candidate product:
- Target user:
- Core workflow:
- First paid scenario:
- Explicit exclusions:

## 3. Capability Landing Map

| Long-term capability | Product object | User action | System feedback | Validation signal | First launch decision |
|----------------------|----------------|-------------|-----------------|-------------------|-----------------------|
| [待填写] | [待填写] | [待填写] | [待填写] | [待填写] | required / candidate / excluded |

## 4. Concrete Page Design

Define every first launch page, page level, and concrete visible content. Do not design page transitions here.

| Level | Page | Concrete visible content | First launch decision |
|-------|------|--------------------------|-----------------------|
| primary / secondary / tertiary | [待填写] | [待填写] | required / candidate / excluded |

Page design rules:

- A capability is not launch-ready until it appears on a concrete page.
- Each required page must state the controls, content blocks, states, empty states, and policy links the user sees.
- A first launch product that needs revenue must include account, pricing / billing, payment result, and acquisition / promotion pages.
- A self-serve first launch product should include onboarding or first-run guidance unless there is explicit evidence that users do not need it.
- Page transitions, navigation hierarchy, pixel-level UI, and engineering tasks belong in downstream product repositories.
- Do not use abstract columns such as `Capabilities shown`, `User actions`, or `System feedback` as a substitute for concrete page content.

Input ownership:

- If the product has user input, define which page owns full input management.
- A home page may expose a quick input entry, but it should not silently become the full input management page unless explicitly decided.

## 5. Questions Requiring User Judgment

Do not silently decide these when evidence is missing:

- Launch surface: Web, mobile, desktop, service, template, or hybrid?
- First paid user: who pays first?
- First revenue point: subscription, one-time purchase, paid pilot, service package, template package, or another scenario?
- Data strategy: local-first, cloud-sync, hosted, export-only, or undecided?
- Human involvement: fully self-serve, assisted, concierge, or hybrid?
- Page ownership: which page owns primary input, review, history, settings, and paid actions?
- Commercial pages: which pages own login / signup, onboarding, pricing, billing, payment result, account management, and promotion?

Agent rule:

- The agent may propose candidates and a recommendation, but must ask the user before freezing decisions that affect launch surface, account system, billing, pricing, data strategy, AI cost, acquisition promise, or required page scope.
- If evidence is missing, write `证据不足`.
- If a change expands the first launch scope, state what scope expanded before editing.

## 6. Revenue Standard

### 证据

- [待填写]

### 推断

- [待填写]

### 决策

- Specific price:
- Payment scenario:
- What user pays for:
- Minimum proof required:

## 7. Not First Launch

- [待填写]
