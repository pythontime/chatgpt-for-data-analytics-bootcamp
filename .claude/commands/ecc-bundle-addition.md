---
name: ecc-bundle-addition
description: Workflow command scaffold for ecc-bundle-addition in chatgpt-for-data-analytics-bootcamp.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /ecc-bundle-addition

Use this workflow when working on **ecc-bundle-addition** in `chatgpt-for-data-analytics-bootcamp`.

## Goal

Adds or updates ECC (Extensible Command/Config) bundle files for chatgpt-for-data-analytics-bootcamp, including commands, skills, agent configs, and tool definitions.

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

- Add or update one or more files in .claude/commands/, .claude/homunculus/instincts/inherited/, .codex/agents/, .codex/, .claude/skills/, .agents/skills/ directories.
- Commit with 'feat: add chatgpt-for-data-analytics-bootcamp ECC bundle ...' message.

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.