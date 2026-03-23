# Feature Development Workflow

## Lifecycle

```
THINK → PLAN → EXECUTE → VALIDATE → REFINE
```

## Self-Improvement Loop

After each task, consider:
- What failed?
- What slowed down?
- What can be automated?

## Stages

### 1. Request Analysis

- Understand user requirements
- Clarify ambiguities
- Identify scope
- Ask: what's the simplest solution?

### 2. Code Analysis

- Explore relevant files
- Understand existing patterns
- Identify affected components
- Find test files

### 3. Implementation

- Create feature branch
- Implement incrementally
- Follow existing conventions
- Handle errors properly
- Build like it will scale

### 4. Testing

- Write unit tests
- Test edge cases
- Run existing tests
- Verify no regressions
- Validate outputs before returning

### 5. Commit

- Stage related changes
- Write descriptive message
- Review diff before commit

### 6. Verification

- Run full test suite
- Manual testing if needed
- Verify in staging if applicable

## Experimentation Mode

- Try multiple approaches
- Benchmark results
- Choose best solution
- Optimize for performance

## Execution Modes

- **Fast** - quick working solution
- **Safe** - validated + tested
- **Deep** - optimized + scalable
