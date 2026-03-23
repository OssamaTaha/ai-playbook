# Data Pipeline Workflow

## Core Philosophy

Systems > tasks, Automation > repetition

## Lifecycle

```
DESIGN → BUILD → TEST → DEPLOY → MONITOR → OPTIMIZE
```

## Self-Improvement

After each pipeline run:
- What slowed down?
- What can be automated?
- Can we optimize?

## Stages

### 1. Design

- Understand source data structure
- Define transformations
- Plan error handling
- Consider idempotency
- Design for scalability

### 2. Build

- Implement extraction
- Implement transformations
- Implement loading
- Add logging
- Context compression for large data

### 3. Test

- Test with sample data
- Test error handling
- Verify output schema
- Check data quality
- Validate outputs

### 4. Deploy

- Deploy to staging
- Run end-to-end
- Verify in production-like environment

### 5. Monitor

- Set up alerting
- Monitor logs
- Track data quality metrics
- Plan for failures
- Design observability

### 6. Optimize

- Identify bottlenecks
- Apply caching strategies
- Batch operations
- Optimize queries

## Common Issues

- Missing/null values
- Schema changes
- Performance at scale
- Duplicate data
- Timezone handling
- Async/timing bugs

## Best Practices

- Idempotent operations
- Retry logic for transient failures
- Dead letter queue for failures
- Proper logging
- Monitoring and alerting
- Build like it will scale

## Execution Modes

- **Fast** - quick working pipeline
- **Safe** - validated + tested
- **Deep** - optimized + scalable
