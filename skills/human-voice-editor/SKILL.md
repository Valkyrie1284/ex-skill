---
name: human-voice-editor
description: Make prose sound more like a thoughtful person and less like a generic language model while preserving meaning. Use for essays, reports, emails, reflections, explanations, and polished drafts when the user says the text feels robotic, too polished, too generic, repetitive, or lacking a human voice.
---

# Human Voice Editor

The goal is not to imitate mistakes. The goal is to make the prose feel authored.

## First principle

A human-sounding paragraph usually has a point of view about what matters. It does not merely present information in polished sequence.

Before rewriting, identify:

- what the writer actually wants the reader to notice;
- which sentence carries the judgment;
- which details are necessary;
- what can be deleted without losing meaning.

## Common machine-like patterns

Repair these when they appear repeatedly:

- every sentence having similar length and complexity;
- perfectly symmetrical lists and repeated groups of three;
- paragraphs that all open with a topic sentence and end with a mini-conclusion;
- generic evaluative phrases that could fit any topic;
- excessive signposting such as "Furthermore", "Moreover", "It is important to note";
- over-explaining obvious links;
- repeating the same noun instead of using normal reference and sentence flow;
- stacking abstract nouns where a verb would be clearer;
- decorative adjectives and prestige vocabulary with no analytical function;
- fake balance, where every claim gets an automatic "however" sentence even when no real tension exists;
- conclusions that repeat the introduction almost word-for-word.

## Make prose feel authored

Prefer:

- concrete verbs;
- selective emphasis rather than equal emphasis on everything;
- sentence-length variation that follows the thought;
- direct judgments when the evidence supports them;
- transitions created by meaning, not by transition words alone;
- paragraph endings that lead naturally into the next idea rather than summarizing mechanically;
- specific nouns over vague abstractions;
- occasional short sentences when a point genuinely deserves emphasis.

## Preserve the writer

Do not replace the user's voice with a generic "human" voice. If the user provides samples, imitate their level of formality, sentence density, preferred vocabulary, and degree of directness.

Do not add fake anecdotes, opinions, uncertainty, slang, typos, or personal experience. Do not deliberately damage grammar to appear human.

## Read-aloud test

After editing, ask internally:

- Would a competent person actually say this sentence this way?
- Does the paragraph sound like someone chose what to emphasize?
- Is any sentence present only because academic or professional writing is "supposed" to contain it?
- Did the edit improve the paragraph as a whole rather than merely swap words?

If a sentence fails the test, rewrite the whole sentence instead of patching isolated synonyms.

## Editing intensity

**Light**: remove filler, awkward phrasing, and repetitive transitions.

**Medium**: vary syntax, improve paragraph rhythm, sharpen judgments, and remove template structure.

**Heavy**: rebuild sentences and paragraph flow while preserving all substantive claims and evidence.

Default to light or medium unless the user asks for a full rewrite.

## Provenance

This is an original compact skill informed by the Apache-licensed `good-writing` skill in `alecs5am/ralphy` and public anti-formulaic-writing guidance.
