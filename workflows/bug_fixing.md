# Bug Fixing Workflow

## Core Philosophy

Debug like it already broke, automate like you'll repeat it 1000 times.

## Loop

```
REPRODUCE → INVESTIGATE → FIX → VERIFY → DOCUMENT → REFINE
```

## Self-Improvement

After each fix:
- What failed?
- What can be automated?

## Stages

### 1. Reproduce

- Get exact reproduction steps
- Verify bug exists
- Confirm environment
- Isolate conditions

### 2. Investigate

- Read error message carefully
- Check stack trace
- Search codebase for clues
- Add targeted logging
- Narrow down to root cause
- Trace execution flow across files
- Detect hidden coupling issues

### 3. Fix

- Implement solution
- Handle edge cases
- Ensure no new bugs
- Keep fix focused

### 4. Verify

- Confirm fix resolves issue
- Run existing tests
- Test edge cases
- Check for regressions
- Validate outputs

### 5. Document

- Explain root cause (for future reference)
- Add test to prevent regression
- Update error messages if helpful

## Time Limits

- If stuck for 30 min, ask for help
- If fix takes too long, consider rollback/flag
- Prioritize getting unblocked

## Techniques

- Binary search to narrow down
- Add targeted logging
- Use debugging tools
- Compare with working state
- Simplify to minimal repro

## Failure Handling

- Detect early failures
- Provide fallback solutions
- Suggest recovery strategies
