# Model Routing

## Strategy

Route to appropriate model based on task complexity.

## Routing Rules

| Task Type | Model | Reasoning |
|-----------|-------|-----------|
| Simple edits, quick questions | Small/fast | Speed matters |
| Code review, bug investigation | Medium | Need reasoning |
| Complex architecture, new features | Large | Need strong reasoning |
| Data analysis, queries | Medium | Structured thinking |
| System prompts | Large | Sets context for everything |

## Decision Tree

```
Is this a simple task?
├─ Yes → Use small/fast model
└─ No → Does it need deep reasoning?
    ├─ Yes → Use large model
    └─ No → Use medium model
```

## Examples

**Small model** (simple edit):
- Rename function
- Fix typo
- Add import
- Simple question

**Medium model** (moderate complexity):
- Implement small feature
- Debug common issue
- Write test case
- Query analysis

**Large model** (complex):
- Design new feature
- Complex debugging
- Architecture decisions
- Multi-file changes
