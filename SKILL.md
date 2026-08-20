---
name: ai-humanizer
description: Rewrite or review text to sound more natural, direct, and human. Use when the user wants to reduce AI-style phrasing, remove clichés, simplify tone, vary sentence structure, or make writing feel less robotic while preserving meaning.
metadata:
  short-description: Make writing sound more human
---

# AI Humanizer

Use this skill when the user wants writing that feels natural instead of polished in a synthetic way.

## Workflow

1. Read the text once for meaning and audience.
2. Check it against the 35 AI-writing patterns (content, language/grammar, style, chatbot, filler/hedging) — see reference.
3. Rewrite: keep every claim, but shorten dull parts and expand thin ones; merge or split paragraphs as needed. Don't invent facts — names, numbers, dates, quotes, and citations must come from the source or the user.
4. Match the voice — formal, casual, or technical as the text calls for — and only add personality where it fits.
5. Preserve the original meaning, facts, and tone category. Leave code, data, and frontmatter untouched; only rewrite prose.
6. Do a final pass for anything that reads like a template, and strip stray em/en dashes (—, –) unless a provided writing sample uses them.

Optional: if the user supplies a writing sample, match its rhythm, word choice, and punctuation instead of the default style rules below.

## Core Rules

- Prefer simple words over theatrical ones.
- Avoid `delve`, `harness`, `leverage`, `robust`, `comprehensive`, `transformative`, and similar filler.
- Avoid stock phrases like `in conclusion`, `at the end of the day`, `low-hanging fruit`, and `think outside the box`.
- Avoid em/en dashes, title-cased headings, decorative emojis, and bold-mini-heading list items.
- Cut leftover chatbot phrasing ("I hope this helps!", "Let me know if...", knowledge-cutoff disclaimers) and overly agreeable openers ("Great question!").
- Vary sentence length.
- Keep transitions natural, not mechanical.
- Use contractions when the tone allows it.
- Keep the writing crisp rather than ornate.

## Tone Adjustments

- Business: direct, calm, and specific.
- Academic: formal, but not stiff.
- Casual: conversational and lightly personal.
- Creative: prioritize rhythm and voice, but still avoid clichés.

## Reference

- [ai_humanizer_knowledge.md](references/ai_humanizer_knowledge.md) — transformation checklist and before/after examples.
- [ai_writing_patterns_35.md](references/ai_writing_patterns_35.md) — the full 35-pattern checklist (content, language, style, chatbot, filler/hedging), adapted from Wikipedia's WikiProject AI Cleanup list via [blader/humanizer](https://github.com/blader/humanizer).
