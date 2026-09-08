# Engineering Review Paper Reviewer

A focused AI Skill for reviewing **engineering review papers** before journal submission or revision.

It is designed for narrative, structured, systematic-style, and methodology-focused reviews in engineering fields such as energy, CFD, built environment, thermal engineering, mechanical engineering, environmental engineering, and related areas.

Unlike generic review prompts, this Skill prioritises whether the review has a defensible literature boundary and produces a genuine synthesis.

## Three hard checks

Every manuscript is tested against three core questions:

### 1. Novelty
Does the review add something meaningfully different from the closest existing reviews?

### 2. Coverage
Is the core literature set complete enough, transparent enough, and reproducible enough to support the manuscript's claims?

### 3. Synthesis
Does the paper generate cross-study knowledge, or mainly summarise studies one by one?

## Ten review modules

1. Scope & research question
2. Novelty against existing reviews
3. Search strategy & literature coverage
4. Inclusion / exclusion transparency
5. Literature quality & evidence hierarchy
6. Critical synthesis depth
7. Quantitative synthesis
8. Mechanism / framework / taxonomy contribution
9. Figures, tables & evidence mapping
10. Conclusions, limitations & research gaps

## What makes it different

This Skill was built after comparing existing peer-review, systematic-review, PRISMA-style, narrative-review, and literature-review Skills and retaining their strongest ideas while adapting them for engineering reviews.

It does **not** mechanically force every review into PRISMA.

Instead, it first identifies the review type, then applies the transparency standard appropriate to that type.

It also checks issues that generic manuscript reviewers often miss:

- whether the closest previous reviews already cover the claimed contribution;
- whether cited candidate studies challenge the stated core sample;
- whether inclusion and exclusion decisions are traceable;
- whether tables and figures actually create new knowledge;
- whether reported percentages can be reproduced from the underlying coding;
- whether incompatible studies are explicitly marked as non-comparable and why;
- whether proposed frameworks can actually be applied to new studies;
- whether research gaps are derived from evidence rather than asserted;
- whether conclusions are stronger than the evidence base allows;
- whether the paper is genuinely synthesising rather than producing a sequence of mini-summaries.

## Evidence-first output

For each substantive issue, the reviewer reports:

- **Location**
- **Issue**
- **Severity** — Critical / Major / Minor
- **Why it matters**
- **Evidence from the manuscript**
- **What to do**
- **Confidence** — High / Medium / Low

The reviewer must distinguish between:

- a confirmed problem;
- a plausible concern;
- information not reported.

Missing information is never treated automatically as proof that the authors did not perform the work.

## Token-conscious design

The Skill uses a compact main workflow and loads specialised reference checks only when needed.

For example:

- PRISMA-style checks are used only when the manuscript claims systematic or structured searching;
- quantitative synthesis checks are skipped when no quantitative comparison is attempted;
- framework-operationalisation checks are triggered only when the review proposes a taxonomy, level system, decision framework, or conceptual model.

## Suitable for

Especially useful for review papers in:

- renewable energy
- photovoltaic research
- CFD and fluid mechanics
- wind-tunnel research
- thermal engineering
- building and environmental engineering
- mechanical engineering
- environmental engineering
- experimental methodology reviews
- engineering measurement and scaling reviews

## Use

Place `SKILL.md` and the `references/` folder in a compatible Skill environment such as Claude Code or Codex.

Example:

```text
Use engineering-review-paper-reviewer to review this manuscript.
Prioritise Novelty, Coverage, and Synthesis.
Focus on substantive scientific and methodological weaknesses rather than language editing.
Do not invent missing information.
```

For a stricter review:

```text
Act as a demanding reviewer for a high-quality engineering review journal.
Use engineering-review-paper-reviewer and independently verify the manuscript's literature boundary, quantitative claims, synthesis logic, and research gaps.
```

## Design principle

**Do not ask only whether the manuscript reviewed enough papers. Ask whether those papers were transformed into reliable new knowledge.**

Created by **Wendy.z**.
