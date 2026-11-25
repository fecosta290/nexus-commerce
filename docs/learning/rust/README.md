# Rust Learning Path

## Learning objectives

Build the Rust knowledge needed for File Processing, with emphasis on ownership, borrowing, lifetimes, enums, traits, errors, modules, and safe I/O before Axum.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** ownership, borrowing, lifetimes, enums, traits, errors, modules, and safe I/O before Axum.
2. **Packages and dependencies:** Cargo; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** built-in tests, integration tests, property testing, and test doubles where appropriate. All project tests remain developer-authored.
4. **API development:** Axum; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** metadata persistence options and safe local storage; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** futures, Tokio concepts, Send/Sync, blocking boundaries, and resource control.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of File Processing. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official Rust documentation](https://doc.rust-lang.org/book/)

Progress is self-assessed and does not imply service implementation.
