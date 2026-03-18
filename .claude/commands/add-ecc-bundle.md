---
name: add-ecc-bundle
description: Workflow command scaffold for add-ecc-bundle in chatgpt-for-data-analytics-bootcamp.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-ecc-bundle

Use this workflow when working on **add-ecc-bundle** in `chatgpt-for-data-analytics-bootcamp`.

## Goal

Adds a new ECC (Extensible Command Collection) bundle for chatgpt-for-data-analytics-bootcamp, including commands, skills, agent configs, and documentation.

## Common Files

- `.claude/commands/*.md`
- `.claude/homunculus/instincts/inherited/*.yaml`
- `.codex/agents/*.toml`
- `.codex/AGENTS.md`
- `.codex/config.toml`
- `.claude/identity.json`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Add or update .claude/commands/*.md files for command documentation.
- Add or update .claude/homunculus/instincts/inherited/*.yaml for instincts configuration.
- Add or update .codex/agents/*.toml for agent configuration.
- Add or update .codex/AGENTS.md and .codex/config.toml for agent documentation and config.
- Add or update .claude/identity.json for identity information.

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.