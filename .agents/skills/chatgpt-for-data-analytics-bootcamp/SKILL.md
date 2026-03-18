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

- Average message length: ~35 characters
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

**Frequency**: ~13 times per month

**Steps**:
1. Add feature implementation
2. Add tests for feature
3. Update documentation

**Example commit sequence**:
```
Add files via upload
Delete data/customer_quarterly_tidy (2).csv
Add files via upload
```

### Update Readme Workflow

Routine updates to the readme.md file for a specific day, likely to document progress, instructions, or results.

**Frequency**: ~6 times per month

**Steps**:
1. Edit the relevant day X/readme.md file with new information.
2. Commit the changes with a message like 'Update readme.md'.

**Files typically involved**:
- `day 1/readme.md`
- `day 2/readme.md`

**Example commit sequence**:
```
Edit the relevant day X/readme.md file with new information.
Commit the changes with a message like 'Update readme.md'.
```

### Gpt Config Md Lifecycle

Creation, update, and deletion of GPT configuration markdown files for various data analytics tasks.

**Frequency**: ~10 times per month

**Steps**:
1. Create, update, or delete a markdown file in day X/gpt-configs/.
2. Commit the change with a descriptive message (e.g., 'Create', 'Update', or 'Delete' <file>).

**Files typically involved**:
- `day 1/gpt-configs/*.md`

**Example commit sequence**:
```
Create, update, or delete a markdown file in day X/gpt-configs/.
Commit the change with a descriptive message (e.g., 'Create', 'Update', or 'Delete' <file>).
```

### Artifact Data File Lifecycle

Adding, updating, or deleting data artifact files (CSVs, scripts) used for bootcamp exercises.

**Frequency**: ~8 times per month

**Steps**:
1. Add, update, or delete files in data/ or day X/artifacts/.
2. Commit the change with a message indicating the action (e.g., 'Add files via upload', 'Delete <file>').

**Files typically involved**:
- `data/*.csv`
- `data/*.xlsx`
- `day 1/artifacts/*.csv`
- `day 1/artifacts/*.py`

**Example commit sequence**:
```
Add, update, or delete files in data/ or day X/artifacts/.
Commit the change with a message indicating the action (e.g., 'Add files via upload', 'Delete <file>').
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
