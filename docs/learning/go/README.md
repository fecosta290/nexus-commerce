# Go Learning Path

## Learning objectives

Build the Go knowledge needed for Notifications, with emphasis on syntax, values, interfaces, errors, modules, tooling, and composition before selecting a web framework.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** syntax, values, interfaces, errors, modules, tooling, and composition before selecting a web framework.
2. **Packages and dependencies:** Go modules; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** the standard testing package, table-driven tests, fakes, and integration tests. All project tests remain developer-authored.
4. **API development:** standard net/http first; framework choice remains open; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** database/sql and migration concepts; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** goroutines, channels, contexts, cancellation, and race detection.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of Notifications. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official Go documentation](https://go.dev/doc/)

Progress is self-assessed and does not imply service implementation.
