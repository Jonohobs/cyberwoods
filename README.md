# Cyberwoods

Security workflow skill for safely reviewing and adopting untrusted external code, skills, packages, and MCP/tool integrations.

## What This Is

A Claude Code skill (SKILL.md) that provides a structured protocol for reviewing external content before it enters your development environment. Apply it whenever you're working with:

- Unknown repos or packages
- Install scripts from the internet
- MCP server descriptions or tool definitions  
- Prompt templates from external sources
- Any content that could contain prompt injection

## Installation

Copy `SKILL.md` to your Claude Code skills directory:

```bash
cp SKILL.md ~/.claude/skills/cyberwoods/SKILL.md
```

Or include in your project's `.claude/skills/` directory.

## Contents

- `SKILL.md` — The skill definition (trigger rules + protocol)
- `agents/openai.yaml` — OpenAI agent format for cross-platform use
- `references/threat-model.md` — Threat model reference
- `references/adoption-checklist.md` — Checklist for safe adoption

## License

MIT
