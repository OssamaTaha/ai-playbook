# Model Configs

## Temperature

| Use Case | Setting |
|----------|---------|
| Code generation | 0.0-0.2 |
| Bug fixes | 0.0-0.1 |
| Refactoring | 0.0-0.2 |
| Creative/generative | 0.7-0.9 |
| Exploration | 0.5-0.7 |

## Context Management

- Use full context for understanding code
- Summarize when context exceeds limits
- Preserve critical context (recent changes, current task)
- Don't truncate error messages

## Token Budget

- Reserve 20% for output
- Prioritize recent changes
- Keep project structure context
- Include relevant imports

## Best Practices

- Temperature 0 for code tasks
- Be concise in prompts
- Use streaming for long outputs
- Handle context limits gracefully
