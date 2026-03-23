# CLI Tools

## Essential Commands

```bash
# File operations
ls -la           # List with details
find . -name     # Find files
grep -r          # Search content
xargs            # Execute on matches

# Git
git status       # Check state
git diff         # See changes
git add -p       # Interactive staging
git commit       # Commit changes

# Process
ps aux           # List processes
kill -9          # Force kill
top/htop         # Monitor

# Network
curl             # HTTP requests
ssh              # Remote access
scp              # File transfer

# Async & Parallel
&                # Background
wait             # Wait for jobs
xargs -P         # Parallel execution
```

## Shell Patterns

```bash
# Chain commands
cmd1 && cmd2     # Run if first succeeds
cmd1 || cmd2     # Run if first fails
cmd1 | cmd2      # Pipe

# Loops
for f in *.ext; do echo $f; done

# Conditionals
if [ -f file ]; then ... fi
```

## Efficiency

- Use tab completion
- Use aliases for frequent commands
- Use history expansion (!$, !!, !-1)
- Use Ctrl+R for reverse search

## Tool Intelligence

- Pick the right tool for the job
- Avoid unnecessary complexity
- Combine tools efficiently
- Think like senior engineer + hacker
