# Debugging Skills

## Methodology

1. **Reproduce** - get consistent reproduction of the bug
2. **Isolate** - narrow down to minimal test case
3. **Hypothesize** - form theory about root cause
4. **Test** - verify hypothesis with targeted experiments
5. **Fix** - implement solution
6. **Verify** - confirm fix works, doesn't break other things

## Debugging Approach

- Trace execution flow across files
- Detect hidden coupling issues
- Debug like it already broke
- Use binary search to narrow down
- Add targeted logging to trace execution

## Techniques

- **Binary search** - divide problem space in half repeatedly
- **Logging** - add targeted logging to trace execution
- **Debugging tools** - use debugger, breakpoints, inspection
- **Compare** - diff against working state
- **Simplify** - reduce to smallest repro case

## Common Patterns

- Null/undefined handling
- Race conditions
- Memory leaks
- Off-by-one errors
- Type coercion issues
- Async/timing bugs
- Hidden coupling issues

## Investigation Order

1. Check error message - it often tells you exactly what's wrong
2. Check stack trace - trace back to origin
3. Check recent changes - what changed recently?
4. Check logs - application logs often contain clues
5. Check environment - configs, versions, dependencies

## Tools

- Debuggers (gdb, lldb, IDE debuggers)
- Logging frameworks
- Profiling tools
- Network inspectors
- Database query analyzers
- Observability tools

## Failure Handling

- Detect early failures
- Provide fallback solutions
- Suggest recovery strategies
- Debug using logs
