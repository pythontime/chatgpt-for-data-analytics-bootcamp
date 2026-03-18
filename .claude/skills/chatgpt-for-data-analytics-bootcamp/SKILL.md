---
name: chatgpt-for-data-analytics-bootcamp-conventions
description: Development conventions and patterns for chatgpt-for-data-analytics-bootcamp. Python project with mixed commits.
---

# Chatgpt For Data Analytics Bootcamp Conventions

> Generated from [pythontime/chatgpt-for-data-analytics-bootcamp](https://github.com/pythontime/chatgpt-for-data-analytics-bootcamp) on 2026-03-18

## Overview

This skill teaches Claude the development patterns and conventions used in chatgpt-for-data-analytics-bootcamp.

## Tech Stack

- **Primary Language**: Python
- **Architecture**: hybrid module organization
- **Test Location**: separate

## When to Use This Skill

Activate this skill when:
- Making changes to this repository
- Adding new features following established patterns
- Writing tests that match project conventions
- Creating commits with proper message format

## Commit Conventions

Follow these commit message conventions based on 8 analyzed commits.

### Commit Style: Mixed Style

### Prefixes Used

- `feat`

### Message Guidelines

- Average message length: ~50 characters
- Keep first line concise and descriptive
- Use imperative mood ("Add feature" not "Added feature")


*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/commands/readme-update.md)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/commands/ecc-bundle-addition.md)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/commands/feature-development.md)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.codex/agents/docs-researcher.toml)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.codex/agents/reviewer.toml)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.codex/agents/explorer.toml)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.codex/AGENTS.md)
```

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.codex/config.toml)
```

## Architecture

### Project Structure: Single Package

This project uses **hybrid** module organization.

### Guidelines

- This project uses a hybrid organization
- Follow existing patterns when adding new code

## Code Style

### Language: Python

### Naming Conventions

| Element | Convention |
|---------|------------|
| Files | snake_case |
| Functions | camelCase |
| Classes | PascalCase |
| Constants | SCREAMING_SNAKE_CASE |

### Import Style: Mixed Style

### Export Style: Mixed Style


## Common Workflows

These workflows were detected from analyzing commit patterns.

### Feature Development

Standard feature implementation workflow

**Frequency**: ~25 times per month

**Steps**:
1. Add feature implementation
2. Add tests for feature
3. Update documentation

**Example commit sequence**:
```
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/ecc-tools.json)
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/skills/chatgpt-for-data-analytics-bootcamp/SKILL.md)
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.agents/skills/chatgpt-for-data-analytics-bootcamp/SKILL.md)
```

### Add Ecc Bundle

Adds a new ECC (Extensible Command Collection) bundle for chatgpt-for-data-analytics-bootcamp, including commands, skills, agent configs, and documentation.

**Frequency**: ~3 times per month

**Steps**:
1. Add or update .claude/commands/*.md files for command documentation.
2. Add or update .claude/homunculus/instincts/inherited/*.yaml for instincts configuration.
3. Add or update .codex/agents/*.toml for agent configuration.
4. Add or update .codex/AGENTS.md and .codex/config.toml for agent documentation and config.
5. Add or update .claude/identity.json for identity information.
6. Add or update .agents/skills/*/agents/*.yaml for agent skill configuration.
7. Add or update .agents/skills/*/SKILL.md and .claude/skills/*/SKILL.md for skill documentation.
8. Add or update .claude/ecc-tools.json for ECC tool registry.

**Files typically involved**:
- `.claude/commands/*.md`
- `.claude/homunculus/instincts/inherited/*.yaml`
- `.codex/agents/*.toml`
- `.codex/AGENTS.md`
- `.codex/config.toml`
- `.claude/identity.json`
- `.agents/skills/*/agents/*.yaml`
- `.agents/skills/*/SKILL.md`
- `.claude/skills/*/SKILL.md`
- `.claude/ecc-tools.json`

**Example commit sequence**:
```
Add or update .claude/commands/*.md files for command documentation.
Add or update .claude/homunculus/instincts/inherited/*.yaml for instincts configuration.
Add or update .codex/agents/*.toml for agent configuration.
Add or update .codex/AGENTS.md and .codex/config.toml for agent documentation and config.
Add or update .claude/identity.json for identity information.
Add or update .agents/skills/*/agents/*.yaml for agent skill configuration.
Add or update .agents/skills/*/SKILL.md and .claude/skills/*/SKILL.md for skill documentation.
Add or update .claude/ecc-tools.json for ECC tool registry.
```

### Update Readme Per Day

Updates the readme.md file for a specific day in the bootcamp, likely to reflect new content, corrections, or progress.

**Frequency**: ~5 times per month

**Steps**:
1. Edit day N/readme.md with new content or corrections.
2. Commit the change with a message like 'Update readme.md'.

**Files typically involved**:
- `day 1/readme.md`
- `day 2/readme.md`

**Example commit sequence**:
```
Edit day N/readme.md with new content or corrections.
Commit the change with a message like 'Update readme.md'.
```

### Update Gpt Config Or Delete

Updates or deletes a GPT configuration markdown file for a specific lesson or module.

**Frequency**: ~2 times per month

**Steps**:
1. Edit or delete the relevant markdown file in day N/gpt-configs/.
2. Commit the change with a descriptive message.

**Files typically involved**:
- `day 1/gpt-configs/*.md`

**Example commit sequence**:
```
Edit or delete the relevant markdown file in day N/gpt-configs/.
Commit the change with a descriptive message.
```


## Best Practices

Based on analysis of the codebase, follow these practices:

### Do

- Use snake_case for file names
- Prefer mixed exports

### Don't

- Don't deviate from established patterns without discussion

---

*This skill was auto-generated by [ECC Tools](https://ecc.tools). Review and customize as needed for your team.*
