# Java Learning Path

## Learning objectives

Build the Java knowledge needed for simulated Payments, with emphasis on syntax, types, object design, exceptions, collections, generics, streams, and JVM fundamentals before Spring Boot.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** syntax, types, object design, exceptions, collections, generics, streams, and JVM fundamentals before Spring Boot.
2. **Packages and dependencies:** Maven and Gradle; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** JUnit, assertions, mocking, integration, and Spring testing concepts. All project tests remain developer-authored.
4. **API development:** Spring Boot; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** relational persistence and transaction concepts; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** threads, executors, futures, virtual threads as applicable, and message consumption.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of simulated Payments. Translate learning into small developer-authored experiments before production-shaped implementation.

## Suggested practical exercises

- Model a small domain-neutral validation problem without copying project business logic.
- Build a local throwaway HTTP exercise with structured errors and cancellation.
- Compare persistence consistency and concurrency approaches using disposable sample data.
- Explore one duplicate-message or retry scenario without implementing Nexus Commerce source code.
- Write developer-authored tests and explain what each test proves.

No solutions or source code are provided here.

## Progress checklist

- [ ] Fundamentals reviewed and explained in personal notes
- [ ] Package and dependency workflow understood
- [ ] Testing tools compared
- [ ] API lifecycle and error behavior explored
- [ ] Persistence trade-offs documented
- [ ] Concurrency and cancellation exercise completed
- [ ] Service-specific risks reviewed
- [ ] Official documentation consulted

## Official documentation

- [Official Java documentation](https://docs.oracle.com/en/java/)

Progress is self-assessed and does not imply service implementation.
