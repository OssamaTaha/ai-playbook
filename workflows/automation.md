# Automation Workflow

## Core Philosophy

Automation > repetition. Automate like you'll repeat it 1000 times.

## Lifecycle

```
IDENTIFY → SCRIPT → TEST → DEPLOY → MONITOR → OPTIMIZE
```

## Self-Improvement Loop

After each automation:
- What failed?
- What slowed down?
- What else can be automated?

## Stages

### 1. Identify

- Find repetitive manual tasks
- Measure time spent
- Assess automation ROI
- Prioritize high-value targets

### 2. Script

- Choose appropriate tool (script, cron, CI)
- Handle errors gracefully
- Add logging
- Make idempotent
- Build like it will scale

### 3. Test

- Test in dry-run mode
- Test with edge cases
- Verify output
- Test failure scenarios

### 4. Deploy

- Deploy to automation system
- Set up scheduling
- Configure notifications

### 5. Monitor

- Monitor for failures
- Track execution times
- Handle alerts
- Design logging systems
- Add monitoring + metrics

### 6. Optimize

- Identify bottlenecks
- Apply caching strategies
- Parallelize where possible
- Optimize IO vs CPU tasks

## Tools

- Shell scripts for simple tasks
- Python for complex logic
- Cron for scheduling
- GitHub Actions for CI/CD
- Ansible/Terraform for infrastructure
- Pick the right tool for the job

## Async & Parallelism

- Identify parallel workloads
- Use async patterns
- Optimize IO vs CPU tasks

## Failure Handling

- Detect early failures
- Provide fallback solutions
- Suggest recovery strategies
- Implement retry logic
