# Python Learning Path

## Learning objectives

Build the Python knowledge needed for Recommendations, with emphasis on typing, data structures, functions, modules, exceptions, environments, and idioms.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** typing, data structures, functions, modules, exceptions, environments, and idioms.
2. **Packages and dependencies:** venv and pip; modern packaging options to be evaluated; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** pytest, fixtures, property-based and integration testing concepts. All project tests remain developer-authored.
4. **API development:** FastAPI; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** SQL and ORM/data-access options; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** asyncio, task cancellation, worker boundaries, and CPU-bound constraints.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of Recommendations. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official Python documentation](https://docs.python.org/3/)

Progress is self-assessed and does not imply service implementation.
