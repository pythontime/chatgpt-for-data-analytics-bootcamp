---
name: chatgpt-for-data-analytics-bootcamp-conventions
description: Development conventions and patterns for chatgpt-for-data-analytics-bootcamp. Python project with freeform commits.
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

### Commit Style: Free-form Messages

### Prefixes Used

- `feat`

### Message Guidelines

- Average message length: ~43 characters
- Keep first line concise and descriptive
- Use imperative mood ("Add feature" not "Added feature")


*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/commands/gpt-config-md-lifecycle.md)
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

*Commit message example*

```text
feat: add chatgpt-for-data-analytics-bootcamp ECC bundle (.claude/identity.json)
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

**Frequency**: ~20 times per month

**Steps**:
1. Add feature implementation
2. Add tests for feature
3. Update documentation

**Example commit sequence**:
```
Add files via upload
Add files via upload
Create 06_data_quality_gpt.md
```

### Ecc Bundle Addition

Adds or updates ECC (Extensible Command/Config) bundle files for chatgpt-for-data-analytics-bootcamp, including commands, skills, agent configs, and tool definitions.

**Frequency**: ~10 times per month

**Steps**:
1. Add or update one or more files in .claude/commands/, .claude/homunculus/instincts/inherited/, .codex/agents/, .codex/, .claude/skills/, .agents/skills/ directories.
2. Commit with 'feat: add chatgpt-for-data-analytics-bootcamp ECC bundle ...' message.

**Files typically involved**:
- `.claude/commands/*.md`
- `.claude/homunculus/instincts/inherited/*.yaml`
- `.codex/agents/*.toml`
- `.codex/AGENTS.md`
- `.codex/config.toml`
- `.claude/identity.json`
- `.claude/skills/chatgpt-for-data-analytics-bootcamp/SKILL.md`
- `.agents/skills/chatgpt-for-data-analytics-bootcamp/SKILL.md`
- `.agents/skills/chatgpt-for-data-analytics-bootcamp/agents/openai.yaml`
- `.claude/ecc-tools.json`

**Example commit sequence**:
```
Add or update one or more files in .claude/commands/, .claude/homunculus/instincts/inherited/, .codex/agents/, .codex/, .claude/skills/, .agents/skills/ directories.
Commit with 'feat: add chatgpt-for-data-analytics-bootcamp ECC bundle ...' message.
```

### Readme Update

Updates the readme.md file for a specific day in the bootcamp, likely to reflect new content, corrections, or progress.

**Frequency**: ~6 times per month

**Steps**:
1. Edit the readme.md file in the corresponding day folder (e.g., day 1/readme.md, day 2/readme.md).
2. Commit with 'Update readme.md' message.

**Files typically involved**:
- `day 1/readme.md`
- `day 2/readme.md`

**Example commit sequence**:
```
Edit the readme.md file in the corresponding day folder (e.g., day 1/readme.md, day 2/readme.md).
Commit with 'Update readme.md' message.
```

### Gpt Config Md Lifecycle

Creates, updates, or deletes GPT configuration markdown files for various exercises or modules within the bootcamp.

**Frequency**: ~5 times per month

**Steps**:
1. Create, update, or delete a markdown file in day 1/gpt-configs/ with a name pattern like NN_description_gpt.md.
2. Commit with a message indicating the action (Create, Update, Delete) and the file.

**Files typically involved**:
- `day 1/gpt-configs/*.md`

**Example commit sequence**:
```
Create, update, or delete a markdown file in day 1/gpt-configs/ with a name pattern like NN_description_gpt.md.
Commit with a message indicating the action (Create, Update, Delete) and the file.
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
