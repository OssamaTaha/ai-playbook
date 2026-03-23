---
name: ai-playbook-session
description: Local session reference for ai-playbook - copy to ~/.kilocode/skills/ai-playbook/SKILL.md for local loading
version: "1.0.0"
author: OssamaTaha
license: MIT
metadata:
  {
    "type": "session-reference",
    "local_only": true,
  }
---

# AI Playbook - Session Reference

## Quick Start

To use locally:
```
cp sessions/session.md ~/.kilocode/skills/ai-playbook/SKILL.md
```

Or configure Skill URL in KiloCode settings:
```
https://raw.githubusercontent.com/OssamaTaha/ai-playbook/master/SKILL.md
```

## Core Philosophy

- **Systems > tasks** - think automation, scalability
- **Automation > repetition** - automate like you'll repeat it 1000 times
- **Speed + correctness > perfection** - ship fast, validate properly
- **Local-first thinking, cloud-aware execution** - adapt to environment
- **Build like it will scale, debug like it already broke**

## Execution Loop

```
THINK → PLAN → EXECUTE → VALIDATE → REFINE
```

## Execution Modes

- **Fast** - quick working solution when speed matters
- **Safe** - validated + tested when correctness matters
- **Deep** - optimized + scalable for production

---

## Skills

### Code Intelligence
- Read large codebases, trace dependencies, detect bugs
- Full-stack development, code review, refactoring

### Data Engineering
- ETL pipelines, data modeling, query optimization
- Data quality, stream processing

### Debugging
- Reproduce → Isolate → Hypothesize → Test → Fix → Verify

### DevOps & Cloud
- CI/CD, containers, IaC, monitoring

### Networking & API
- HTTP, REST, GraphQL, gRPC, TLS, authentication

---

## Rules

- Use meaningful names, keep functions under 50 lines
- Handle errors explicitly, validate all inputs
- Never hardcode secrets, use environment variables
- Test thoroughly, avoid blind code generation

---

## Workflows

### Feature Development
```
THINK → PLAN → EXECUTE → VALIDATE → REFINE
```

### Bug Fixing
```
REPRODUCE → INVESTIGATE → FIX → VERIFY → DOCUMENT
```

---

## Model Routing

| Task Type | Model |
|-----------|-------|
| Simple edits | Small/fast |
| Code review | Medium |
| Complex architecture | Large |

---

## File Structure

| Directory | Purpose |
|-----------|---------|
| `skills/` | Capability definitions |
| `prompts/` | Reasoning templates |
| `rules/` | Hard constraints |
| `workflows/` | Execution flows |
| `models/` | Routing configs |
| `tools/` | Environment awareness |
| `memory/` | Persistent intelligence |
| `experiments/` | R&D notes |

---

## KiloCode Loading

KiloCode loads skills from:
1. Local: `~/.kilocode/skills/`
2. Skill URL in settings

This session reference can be copied directly to the local skills directory for offline use.
