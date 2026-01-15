# Second Brain

A personal knowledge system powered by Claude Code.

## What This Is

A starter template for building a second brain where the AI maintains the system, not you. Capture ideas, organize knowledge, track goals — all through natural conversation.

## Requirements

- Claude Code ([claude.ai/code](https://claude.ai/code))
- A markdown editor (VS Code, Zed, Obsidian)

## Quick Start

1. Clone this repo
2. Open the folder in Claude Code
3. Say "what's new?" or run `/gather`

## Structure

```
00-Inbox/           # Quick captures, unsorted items
01-Goals/           # Active goals with artifacts
02-Knowledge/       # Organized by topic
03-Engines/         # Workflow templates
04-Outputs/         # Generated briefs, drafts, summaries
05-System/          # Configuration
```

## Commands

| Command | What it does |
|---------|--------------|
| `/gather` | Pull news from your sources |
| `/process` | Route inbox items |
| `/summary` | Brief on goals + activity |
| `/goal` | Manage goals |
| `/run` | Execute workflows |

## Customize

- Edit `CLAUDE.md` to change system behavior
- Add sources to `05-System/sources.md`
- Create commands in `.claude/commands/`

## Learn More

Full guide: [How to Create a Second Brain with Claude Code](https://loopcraft.io/second-brain)

## License

MIT
