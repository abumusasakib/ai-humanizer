# ai-humanizer

`ai-humanizer` is a Claude Code / Codex skill for rewriting or reviewing text to sound more natural, direct, and human. It removes AI-style phrasing, clichés, and formulaic structure while preserving meaning, facts, and structure.

It is checked against the [35 AI writing patterns](references/ai_writing_patterns_35.md) (content, language/grammar, style, chatbot, and filler/hedging), adapted from Wikipedia's WikiProject AI Cleanup list via [blader/humanizer](https://github.com/blader/humanizer).

## When to use it

Use it when you want to:

- Remove AI-style phrasing
- Simplify dense or repetitive writing
- Make a draft sound less robotic
- Preserve meaning while improving readability
- Polish business writing that feels too formal or inflated
- Clean up academic text that is correct but hard to read
- Unstiffen casual writing that sounds too formal
- Apply a more human voice to any draft without changing the core message

## Install

```bash
git clone https://github.com/abumusasakib/ai-humanizer.git ~/.claude/skills/ai-humanizer
```

*(or `cp -r` the repo contents into a folder under `~/.claude/skills/`) — no dependencies, no build step, pure Markdown.*

## What's here

- `SKILL.md` — the skill definition Claude Code/Codex loads (frontmatter, workflow, core rules).
- `references/ai_humanizer_knowledge.md` — transformation checklist and before/after examples.
- `references/ai_writing_patterns_35.md` — the full 35-pattern checklist.

## How it works

1. **Analyze:** Read the text to understand its meaning and target audience.
2. **Scan:** Check it against the 35 AI writing patterns in the reference files.
3. **Rewrite:** Rewrite the text in a clearer, more natural, and direct voice.
4. **Preserve:** Keep names, numbers, dates, quotes, and citations unchanged unless the source itself requires modification.
5. **Polishing:** Perform a final pass to eliminate any remaining templated or robotic phrasing.

## Notes

- The skill keeps code, data, and frontmatter untouched.
- It avoids em dashes and filler phrases unless the source text already uses them for a specific reason.
- It is meant for polishing writing, not adding new claims or ideas.

## License

MIT — see [LICENSE](LICENSE).
