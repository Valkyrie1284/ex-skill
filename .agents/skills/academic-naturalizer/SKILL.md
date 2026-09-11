---
name: academic-naturalizer
description: Revise academic prose so it reads like deliberate human scholarship rather than formulaic model output. Preserve meaning, evidence, citations, terminology, uncertainty, and argument structure. Use for essays, reports, literature reviews, case analyses, abstracts, and assignment drafts when the user asks to remove AI-like writing, make the prose more natural, or improve academic voice without weakening the argument.
---

# Academic Naturalizer

Improve academic prose by fixing observable writing defects, not by chasing detector scores.

## Priority order

1. Preserve the author's actual claim, evidence, numbers, citations, scope, causal strength, and uncertainty.
2. Preserve technical terminology and proper nouns unless the user explicitly asks to simplify them.
3. Preserve the logical relation between sentences and paragraphs.
4. Remove formulaic, repetitive, inflated, or process-leaking language.
5. Make the smallest coherent edit that improves the passage.

## What to remove

Flag and revise only when they are actually present:

- generic openings that delay the argument;
- empty significance claims such as "this highlights the importance of" when no new analysis follows;
- repetitive paragraph templates;
- excessive "Furthermore / Moreover / In addition" transitions when the logic is already clear;
- repeated contrast scaffolds such as "not only X but also Y" or "it is not X, but Y";
- unnecessary hedging or defensive language that avoids making a supported judgment;
- abstract nouns where a direct verb is clearer;
- inflated vocabulary chosen only to sound academic;
- restating the same conclusion at the end of every paragraph;
- overly symmetrical sentence patterns, repeated triads, and mechanically even sentence lengths.

Do not ban a word or construction merely because it is common in AI output. Keep it when it is the clearest academic choice.

## Academic register

Natural does not mean casual. Keep discipline-appropriate hedging, passive voice, nominalization, and technical language when they serve a real scholarly function. Do not introduce contractions, slang, fake personal experience, invented examples, or unsupported certainty just to make the prose look human.

## Document-level pass

For multi-paragraph text, inspect the whole editable scope before rewriting. Look for repeated paragraph openings, identical rhetorical moves, over-regular sentence rhythm, terminology drift, and transitions that are verbal rather than logical.

A strong paragraph should usually contain:

- a defensible claim or analytical point;
- evidence, example, or source material where required;
- reasoning that explains why the evidence matters;
- a clear connection to the larger argument.

## Rewrite rule

Leave already competent prose alone. Prefer deletion, compression, or a direct sentence over decorative paraphrase. Never add facts, citations, mechanisms, limitations, or examples that are not supported by the supplied material.

## Output

Unless the user asks for diagnostics, return the revised text only.

If diagnostics are requested, separate them from the manuscript and report formulaic patterns found, logic or terminology risks, major edits made, and any passage that cannot be safely revised without more evidence.

## Provenance

This skill is a compact original adaptation informed by the MIT-licensed `academic-humanizer` skill from `dongshuyan/compass-skills` and general writing-quality approaches from public agent skills. It is focused on prose quality rather than detector evasion.
