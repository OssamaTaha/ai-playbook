# AI Playbook

Internal control plane for advanced AI coding agent execution.

## System Layers

```
┌─────────────────────────────────────┐
│           WORKFLOWS                 │  Execution flows
├─────────────────────────────────────┤
│           PROMPTS                   │  Reasoning + task templates
├─────────────────────────────────────┤
│            RULES                    │  Hard constraints
├─────────────────────────────────────┤
│           SKILLS                    │  Capabilities
├─────────────────────────────────────┤
│           MODELS                    │  Routing + configs
├─────────────────────────────────────┤
│           TOOLS                     │  Environment awareness
└─────────────────────────────────────┘
```

## Usage

Agent loads files in this order:

1. **System prompt** (`prompts/system/base.md`) - core reasoning
2. **Persona** (`prompts/personas/*.md`) - behavioral mode
3. **Task template** (`prompts/tasks/*.md`) - specific workflow
4. **Skills** (`skills/*.md`) - capability definitions
5. **Rules** (`rules/*.md`) - constraints

## Directory Structure

| Directory | Purpose |
|-----------|---------|
| `skills/` | Capability definitions |
| `prompts/` | Reasoning + task templates |
| `rules/` | Hard constraints |
| `workflows/` | Execution flows |
| `models/` | Model routing + configs |
| `tools/` | Environment awareness |
| `memory/` | Persistent intelligence |
| `experiments/` | R&D notes |

## Core Principles

1. **Always verify** - never assume, test everything
2. **Minimize iterations** - plan before executing
3. **Fail fast** - detect errors early
4. **Stay in scope** - don't over-engineer
5. **Document decisions** - future self will thank you
