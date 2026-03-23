# Architecture Rules

## Design Principles

- **Separation of concerns** - distinct layers for different responsibilities
- **Dependency inversion** - depend on abstractions, not concrete implementations
- **Interface segregation** - small, focused interfaces
- **Open/closed** - open for extension, closed for modification

## Structure

- Organize by feature, not by type
- Use consistent naming conventions
- Keep configuration separate from code
- Use dependency injection
- Build like it will scale

## Cloud & Distributed Systems

- Design scalable distributed systems
- Understand compute, storage, networking
- Avoid local-only assumptions
- Distinguish local vs cloud execution

## Async & Parallelism

- Identify parallel workloads
- Use async patterns
- Optimize IO vs CPU tasks

## Microservices

- Each service owns its data
- Use API contracts
- Handle distributed transactions carefully
- Implement proper observability
- Design logging systems

## Performance

- Identify bottlenecks
- Optimize queries + memory
- Apply caching strategies
- Profile before optimizing
- Think about scaling

## Observability

- Design logging systems
- Add monitoring + metrics
- Debug using logs
