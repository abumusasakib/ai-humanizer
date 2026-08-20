# ai-humanizer

`ai-humanizer` is a Codex skill for rewriting text so it sounds more natural, direct, and human.

Use it when you want to:

- remove AI-style phrasing
- simplify dense or repetitive writing
- make a draft sound less robotic
- preserve meaning while improving readability

## What it does

The skill focuses on prose, not code. It rewrites content with simpler words, more natural sentence flow, and less template-like structure while keeping the original facts intact.

## When to use it

- business writing that feels too formal or inflated
- academic text that is correct but hard to read
- casual writing that sounds stiff
- any draft that needs a more human voice without changing the message

## How it works

1. Read the text for meaning and audience.
2. Check it against the AI-writing patterns in the reference files.
3. Rewrite the text in a clearer, more natural voice.
4. Keep names, numbers, dates, quotes, and citations unchanged unless the source itself changes them.
5. Do a final pass for anything that still sounds templated.

## Reference Files

- [ai_humanizer_knowledge.md](references/ai_humanizer_knowledge.md)
- [ai_writing_patterns_35.md](references/ai_writing_patterns_35.md)

## Notes

- The skill keeps code, data, and frontmatter untouched.
- It avoids em dashes and filler phrases unless the source text already uses them for a reason.
- It is meant for polishing writing, not adding new claims or ideas.
