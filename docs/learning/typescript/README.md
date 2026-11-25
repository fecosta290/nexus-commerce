# TypeScript Learning Path

## Learning objectives

Build the TypeScript knowledge needed for Analytics, with emphasis on JavaScript runtime fundamentals, types, narrowing, generics, modules, errors, and functional patterns.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** JavaScript runtime fundamentals, types, narrowing, generics, modules, errors, and functional patterns.
2. **Packages and dependencies:** npm-compatible tooling; package manager to be selected; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** Node test runners, assertions, test doubles, contract and integration testing. All project tests remain developer-authored.
4. **API development:** Node.js framework to be evaluated; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** MongoDB driver and document modeling; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** event loop, promises, streams, workers, backpressure, and cancellation.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of Analytics. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official TypeScript documentation](https://www.typescriptlang.org/docs/)

Progress is self-assessed and does not imply service implementation.
