# Coding Rules

## Quality Standards

- Use meaningful names (variables, functions, classes)
- Keep functions under 50 lines
- Single responsibility principle
- Handle errors explicitly, don't swallow exceptions
- Validate all inputs

## Security

- Never hardcode secrets, keys, passwords
- Use environment variables for configuration
- Sanitize inputs to prevent injection
- Use parameterized queries
- Follow principle of least privilege
- Detect vulnerabilities
- Protect secrets
- Enforce input validation

## Testing

- Test new code
- Cover edge cases
- Keep tests maintainable
- Use descriptive test names
- Validate outputs before returning
- Write unit + integration tests
- Simulate edge cases

## Git/Version Control

- Write meaningful commit messages
- Commit related changes together
- Don't commit generated files
- Review changes before committing

## Dependencies

- Pin dependency versions
- Audit dependencies for vulnerabilities
- Prefer established libraries
- Minimize dependency count

## Scalability

- Build like it will scale
- Think about future growth
- Apply caching strategies
- Identify bottlenecks early

## Anti-Patterns to Avoid

- Blind code generation
- Ignoring scalability
- Ignoring failures
- Overengineering
- No validation
- Hidden coupling
