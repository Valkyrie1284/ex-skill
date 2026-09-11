---
name: academic-writing-suite
description: Coordinate academic assignment editing across logic, natural academic style, and human voice. Use when the user asks for a full paper pass, essay revision, assignment polishing, or wants a draft to be stronger, less formulaic, and more coherent without changing evidence or citations.
---

# Academic Writing Suite

Use three passes in this order:

1. **Argument logic** — apply the principles of `argument-logic-editor`. Fix thesis alignment, paragraph roles, claim-evidence-reasoning links, hidden assumptions, false transitions, and structural gaps before touching style.
2. **Academic naturalization** — apply `academic-naturalizer`. Remove formulaic scaffolding, empty significance claims, repeated templates, inflated wording, and unnecessary defensive language while preserving academic register, evidence, citations, terminology, and uncertainty.
3. **Human voice** — apply `human-voice-editor` lightly. Improve rhythm, selective emphasis, sentence variety, and authored feel without casualizing the paper or introducing fake imperfections.

## Non-negotiable constraints

- Never invent evidence, citations, data, examples, quotations, limitations, or author experiences.
- Never change numbers, citation keys, proper nouns, or technical terms without a clear reason.
- Do not weaken or strengthen causal claims, certainty, scope, or comparison direction unless the evidence requires it.
- Do not optimize for an AI-detector percentage. Optimize for clarity, coherence, specificity, and authentic authorial judgment.
- Leave already strong passages alone.

## Recommended workflow for assignments

Read the assignment requirements, rubric, source material, and full draft first. Build a short internal map of the thesis and paragraph jobs. Repair logic first, then style. If the user asks for minimal editing, preserve wording wherever possible and prefer deletion over wholesale rewriting.

If the user has already manually rewritten or humanized parts of the paper, treat those passages as high-preservation zones unless there is a factual, logical, citation, or grammar problem.

## Output

Default: return the clean revised text only.

When the user asks for a review, provide a compact diagnosis covering logic, evidence use, AI-like/formulaic patterns, human voice, and any risky changes that require the author's decision.
