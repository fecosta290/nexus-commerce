# Ruby Learning Path

## Learning objectives

Build the Ruby knowledge needed for Promotions, with emphasis on objects, blocks, enumerables, modules, exceptions, gems, and idioms before Rails.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** objects, blocks, enumerables, modules, exceptions, gems, and idioms before Rails.
2. **Packages and dependencies:** RubyGems and Bundler; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** Minitest, RSpec, request tests, and integration testing concepts. All project tests remain developer-authored.
4. **API development:** Rails API; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** Active Record, transactions, locking, and decimal handling; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** threads, fibers, background work concepts, and runtime constraints.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of Promotions. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official Ruby documentation](https://www.ruby-lang.org/en/documentation/)

Progress is self-assessed and does not imply service implementation.
