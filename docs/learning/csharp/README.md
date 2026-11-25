# C# Learning Path

## Learning objectives

Build the C# knowledge needed for Catalog, Inventory, Customers, Ordering, API Gateway, and later Blazor, with emphasis on advanced language features, .NET runtime behavior, dependency inversion, modularity, diagnostics, and architecture trade-offs.

## Prerequisites

Comfort with general programming, Git, HTTP, SQL or document concepts as relevant, command-line navigation, and the Nexus Commerce [architecture overview](../../architecture/overview.md).

## Progressive topics

1. **Language fundamentals:** advanced language features, .NET runtime behavior, dependency inversion, modularity, diagnostics, and architecture trade-offs.
2. **Packages and dependencies:** NuGet and the .NET SDK; lock-file and supply-chain practices should be understood before adding dependencies.
3. **Testing ecosystem:** xUnit, NUnit, MSTest, and test doubles evaluated per project. All project tests remain developer-authored.
4. **API development:** ASP.NET Core and YARP; study validation, errors, security, documentation, and observability before framework conventions.
5. **Persistence:** relational access patterns and MongoDB drivers; include transactions, concurrency, migrations or document evolution, and data ownership.
6. **Asynchrony and concurrency:** Task-based asynchrony, cancellation, parallelism, and thread-safety.

## Service-specific objectives

Study the responsibilities, integrations, business rules, failure modes, and pending decisions of Catalog, Inventory, Customers, Ordering, API Gateway, and later Blazor. Translate learning into small developer-authored experiments before production-shaped implementation.

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

- [Official C# documentation](https://learn.microsoft.com/dotnet/csharp/)

Progress is self-assessed and does not imply service implementation.
