# CLAUDE.md — My Second Brain

## Who I Am
[Run /vault-setup to personalize this file. Claude Code will interview you
and fill this in based on your role, projects, and goals.]

## Vault Structure
```
inbox/      ← Drop any file here. Claude Code will sort it.
daily/      ← Daily notes (YYYY-MM-DD.md)
projects/   ← Active projects and briefs
research/   ← Notes, synthesis, saved ideas
archive/    ← Completed work. Never delete, just archive.
```

## Context Loading Rules
When starting the day:
→ Read daily/[today's date].md if it exists
→ Check inbox/ for any unprocessed files

When working on a project:
→ Read projects/[name]/ before starting

When writing anything:
→ Read recent notes first to calibrate voice and context

## How to Maintain This Vault
- New files from outside → inbox/ first, sort later
- Daily notes → daily/YYYY-MM-DD.md
- Completed work → archive/ (never delete)
- Update this file whenever your conventions change

## Task Management (TaskForge)
TaskForge is installed and watches this vault for tasks.

- **Inline tasks** (`- [ ]` / `- [x]`) → use in daily notes and project files
- **Task files** (standalone `.md` with YAML frontmatter) → use in `projects/` for complex, multi-step work
- When creating tasks, always use standard markdown checkboxes so TaskForge picks them up
- Never delete completed tasks — mark them `- [x]` so TaskForge tracks completion history
- Do not put tasks in `inbox/` — that folder is for unsorted files only

## Available Slash Commands
- /vault-setup  — Personalize this vault for your role
- /daily        — Start the day with vault context
- /tldr         — Save a summary of this session to the vault
- /file-intel   — Process any folder of files through Gemini, get Obsidian-ready summaries
