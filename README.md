# Learn to code with AI: without losing the fundamentals

**One file. Five words. Zero installation.**

Makes any AI act like a tutor: it makes you predict before it helps, gives hints one level at a time, never writes your code, and quizzes you afterwards.

## Which word do I use?

| Situation | Type |
|---|---|
| About to build something | `PLAN` + what you're building |
| Stuck on an error or problem | `STUCK` + the error |
| Code you don't understand | `READ` + the code |
| It works, want it reviewed | `CHECK` + your code |
| Think you understand a concept | `TEACH` + the concept |
| Truly out of ideas | `just show me` (you'll have to explain it back) |
| Need to actually ship today | `ship mode` (and `learn mode` to come back) |

## Setup: pick your tool, 30 seconds

| Tool | What to do |
|---|---|
| **ChatGPT / Claude / Gemini in the browser (free tiers work)** | Paste `TUTOR.md` as your first message. To make it permanent, put it in a Claude Project or Custom GPT instructions. Keep `LEARNING-LOG.md` open in a text editor and paste the log lines it gives you. |
| **Claude Code** | Copy `CLAUDE.md`, `LEARNING-LOG.md` into your project. Loads automatically. |
| **Cursor** | Copy `.cursor/rules/tutor.mdc` and `LEARNING-LOG.md` into your project. Applies to every chat. |
| **GitHub Copilot** | Copy `.github/copilot-instructions.md` and `LEARNING-LOG.md` into your project. Copilot Chat reads it automatically. |
| **Codex CLI / Gemini CLI / Aider / any other tool that reads `AGENTS.md`** | Copy `AGENTS.md` and `LEARNING-LOG.md` into your project. Loads automatically. |

No slash commands, no repo to clone, no paid plan needed, no per-editor branches. Each tool loads its own instruction file natively, so there is nothing to install and nothing to break. If your tool isn't listed, it likely still reads plain text, so fall back to the browser-chat row: paste `TUTOR.md` (or `AGENTS.md`, they're identical) as your first message.

## Two things the AI can't do for you

1. **Try for 5 minutes before typing `STUCK`.** The prompt can't enforce this. The learning happens in those 5 minutes.
2. **Turn off inline code completions** in your editor while learning. Autocomplete is the biggest source of "I didn't actually write this".

## Honest limitations

- Any model drifts back toward "helpful assistant" in long chats. Typing one of the five words re-anchors it.
- In browser chat, the log is manual (paste the line). In Claude Code / Cursor / Copilot it's automatic.
- This is a learning tool. When you need to ship, use `ship mode` rather than deleting the file.
