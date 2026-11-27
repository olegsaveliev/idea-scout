# Idea Scout

Finds three fresh YouTube Short ideas for a beginner AI channel. No app — just plain-English instruction files that Claude Code follows.

## How to use
Open this folder in Claude Code and type:

    /scout

It sends three helpers out at the same time (Claude news, other AI labs' news, what people are asking about AI), then a checker throws out anything older than a week or already made. You get three ideas in chat, saved in `ideas/` with today's date. Tell it which one you'll make and it adds it to `made-shorts.md`.

## The files
- `CLAUDE.md` — who you are, who your viewers are, what a good idea looks like. Edit this to change taste.
- `made-shorts.md` — every Short you've made. Add lines any time.
- `.claude/commands/scout.md` — the /scout steps.
- `.claude/agents/` — the three helpers and the checker, one file each.
- `ideas/` — each morning's results.
