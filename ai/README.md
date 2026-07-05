# AI Folder

This directory holds AI-related resources for **test-project** — prompts, agent instructions, and other files that help Cursor and other AI tools work effectively in this codebase.

## Purpose

Use this folder to keep AI context separate from application code. That makes it easier to update instructions without touching source files.

## Suggested Structure

```
ai/
├── README.md          # This file
├── prompts/           # Reusable prompt templates
├── rules/             # Project-specific AI rules and conventions
└── examples/          # Sample inputs/outputs for common tasks
```

## Related Files

| File | Location | Description |
|------|----------|-------------|
| Project guide | [`../cursor.md`](../cursor.md) | Main AI context: tech stack, structure, and coding conventions |
| Package config | [`../package.json`](../package.json) | Dependencies and npm scripts |

## Guidelines

- Keep prompts and rules **focused** — one concern per file when possible.
- Prefer **clear, actionable** language over vague instructions.
- Update this folder when project conventions change so AI assistants stay aligned.
- Do not store secrets (API keys, tokens, credentials) here.

## Notes for AI Assistants

When working in this project:

1. Read [`cursor.md`](../cursor.md) first for project-wide context.
2. Check this folder for task-specific prompts or rules before making changes.
3. Follow existing Next.js App Router and TypeScript conventions.
4. Keep diffs minimal and do not commit unless explicitly asked.
