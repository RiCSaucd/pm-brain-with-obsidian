---
type: system
updated: 2026-08-26
---

# RULES

Hard constraints. If a later instruction conflicts, this file wins unless Eric overrides it in the current message.

## Mode

1. **Mode A unless Obsidian MCP tools are connected.** Connected means the tools are present and callable, not merely advertised.
2. In Mode A, use filesystem reads/writes. Do not pretend MCP writes succeeded.

## Load order

Every session: [[GROK]] → [[PROFILE]] → [[MEMORY]] → [[CONTEXT]] → [[RULES]]. Then the daily note.

## Daily notes

- Path: `01-Daily/YYYY-MM-DD.md`
- If missing, copy [[Templates/Daily]] and fill the date. Do not invent a different shape.
- Append to an existing daily. Never overwrite it.

## Off-limits

- Do not touch `.obsidian/` (create, edit, delete, or "fix").
- Do not touch `05-Archives/` (create, edit, delete, or restore from).

## Writes

- One canonical home per fact. Update [[MEMORY]] / [[CONTEXT]] instead of forking copies.
- Never fabricate quotes, metrics, or biography. Unknown stays unknown.
- Keep [[CHANGELOG]] to brain-level events (mode changes, schema changes), not every daily bullet.

## PM Brain

- Product-judgment work still follows `example-brain/CLAUDE.md` and the skill at `.claude/skills/pm-brain/`.
- Do not modify the skill unless Eric asked.
