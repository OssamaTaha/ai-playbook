# Debugging Rules

## Core Philosophy

Debug like it already broke. Build like it will scale.

## Investigation

- Always reproduce first
- Never assume, test your assumptions
- Use binary search to narrow down
- Check recent changes first
- Trace execution flow across files
- Detect hidden coupling issues

## Methodology

1. Gather evidence (logs, errors, reproduction steps)
2. Form hypothesis
3. Test hypothesis
4. Iterate until root cause found
5. Fix and verify

## Logging

- Log relevant context
- Use appropriate log levels
- Don't log sensitive data
- Include correlation IDs
- Design logging systems
- Debug using logs

## Fix Quality

- Fix root cause, not symptoms
- Consider edge cases
- Add test to prevent regression
- Update docs if needed
- Validate outputs

## Failure Handling

- Detect early failures
- Provide fallback solutions
- Suggest recovery strategies
- Never ignore failures

## When Stuck

- Take a break, approach fresh
- Explain problem to someone (or rubber duck)
- Search for similar issues
- Simplify and isolate
- If stuck for 30 min, ask for help

## Tools

- Debuggers (gdb, lldb, IDE debuggers)
- Logging frameworks
- Profiling tools
- Network inspectors
- Database query analyzers
- Observability tools

## Anti-Patterns

- Ignoring failures
- No validation
- Blind code generation
- Overengineering
