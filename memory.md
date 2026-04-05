# Memory

This file is updated by Claude Code after each session.
Use it to track key decisions, context, and continuations across conversations.

---

<!-- Claude Code appends session summaries below this line -->

## 2026-04-05 — TaskForge + ClaudeClaw Integration Session

### Who
Christopher Bole (youdidwhat-towho). Building **Honeybird AIOS** — a personal AI operating system.

### Ecosystem (as understood so far)
- **Second Brain** (`youdidwhat-towho/second-brain`) — vault template repo
- **Vault** (`youdidwhat-towho/vault`) — actual personal vault + Honeybird AIOS Obsidian vault (private)
- **ClaudeClaw** — forked from `earlyaidopters/claudeclaw`. Telegram bot running Claude Code from phone. B-rad is the AI CEO agent.
- **TaskForge** — iPad app, reads `- [ ]` checkboxes from vault. Configured: "Use Both" mode, default Inline Tasks.
- **Claude Office Visualizer** — pixel art agent visualization
- **Airtable** — AIOS roadmap lives here (not yet reviewed)
- **Coaching Callouts** — Claude Code skill for non-developer coaching
- **Sanity/Next.js personal website** — in progress

### What was done this session
1. Updated `CLAUDE.md` with TaskForge conventions (inline tasks + task files)
2. Updated `/daily` skill to surface carry-over `- [ ]` tasks from recent notes
3. Updated `/tldr` skill to capture incomplete tasks in session summaries
4. Added ClaudeClaw integration section to `CLAUDE.md`
5. Created `vault-template/projects/roadmap.md` placeholder for B-rad's roadmap
6. All pushed to branch `claude/setup-recommendations-CSE0h`

### NOT done — pickup on Mac
- [ ] Review actual pickup files (they're on Mac, not in this sandboxed session)
- [ ] Connect ClaudeClaw's `[PATH TO OBSIDIAN]` to the actual vault
- [ ] Review Airtable AIOS roadmap and figure out how it syncs to vault
- [ ] Clarify relationship between `second-brain` (template) and `vault` (actual)
- [ ] Set up multi-device workflow so git repos stay clean across Mac/iPad/web

### Multi-device setup needed
Christopher works across Mac terminal, iPad (TaskForge), and phone (ClaudeClaw/Telegram).
Needs a clear workflow for which device does what, and how git stays in sync without conflicts.
Key concern: "don't want to mess up my git repos just because I'm on a different device."

### Key decisions
- TaskForge: "Use Both" mode, Inline Tasks as default
- ClaudeClaw: forked from earlyaidopters/claudeclaw
- B-rad = ClaudeClaw AI CEO agent (not a real person)
- Vault is the single source of truth — ClaudeClaw and TaskForge both read/write to it
