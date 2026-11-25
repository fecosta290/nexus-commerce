# Nexus Commerce

**Status: Planning / Sprint 0 — application implementation has not started.**

Nexus Commerce is an educational distributed commerce platform for small and medium-sized businesses. It is intended to demonstrate practical software engineering through a locally operated, polyglot microservices system.

## Objectives

The product is planned to manage products, inventory, customers, orders, simulated payments, promotions, notifications, recommendations, files, and business analytics. Its educational goal is to build practical knowledge of distributed systems, service boundaries, integration, observability, resilience, and multiple programming languages.

## Planned architecture

The proposed architecture uses independently built microservices in a monorepo, synchronous REST communication, asynchronous event-driven communication, database-per-service data ownership, an API Gateway, and an external identity provider. These choices are proposals subject to validation through [Architecture Decision Records](docs/architecture/adr/README.md).

Planned infrastructure includes Docker, Docker Compose, RabbitMQ, PostgreSQL, MongoDB, Redis, Keycloak, OpenTelemetry, Prometheus, Grafana, Jaeger, and GitHub Actions. None is currently operational.

## Planned services

| Component | Language / framework | Persistence |
|---|---|---|
| API Gateway | C# / YARP | None |
| Catalog | C# / ASP.NET Core | MongoDB |
| Inventory | C# / ASP.NET Core | PostgreSQL |
| Customers | C# / ASP.NET Core | PostgreSQL |
| Ordering | C# / ASP.NET Core | PostgreSQL |
| Payments | Java / Spring Boot | PostgreSQL |
| Notifications | Go / framework to be evaluated | PostgreSQL |
| Promotions | Ruby / Rails API | PostgreSQL |
| Recommendations | Python / FastAPI | PostgreSQL |
| File Processing | Rust / Axum | Local storage |
| Analytics | TypeScript / Node.js | MongoDB |
| Frontend | C# / Blazor | None |

See the [service catalog](docs/architecture/service-catalog.md) for boundaries and learning goals.

## Repository structure

- `docs/`: product, requirements, architecture, Scrum, and learning guidance.
- `src/`: reserved locations for developer-authored application code.
- `contracts/`: future API and event contracts.
- `infrastructure/`: future local infrastructure assets.
- `tests/`: future developer-authored contract, end-to-end, and performance tests.
- `scripts/`: future non-application development utilities.
- `.github/`: issue and pull request templates.

## Development methodology

Scrum is adapted for one developer with two-week sprints, subject to adjustment. GitHub Projects and GitHub Issues are the operational source of truth. See the [working agreement](docs/scrum/working-agreement.md), [backlog structure](docs/scrum/backlog-structure.md), and [Sprint 0 plan](docs/scrum/sprint-0.md).

## Learning philosophy

The developer manually writes all application source code. AI use is restricted to documentation, organization, technical guidance, and learning assistance. Learning notes provide objectives and exercises without source-code solutions.

## Roadmap

The sequence progresses from project foundation through individual backend capabilities, integration, observability, and resilience. An integrated backend is targeted for v1.0; the Blazor web application follows backend validation in v2.0. See the [full roadmap](docs/product/roadmap.md).

## Documentation

- [Documentation index](docs/README.md)
- [Product vision](docs/product/vision.md)
- [Product scope](docs/product/scope.md)
- [Requirements](docs/requirements/non-functional.md)
- [Architecture overview](docs/architecture/overview.md)
- [Communication strategy](docs/architecture/communication-strategy.md)
- [Learning paths](docs/learning/README.md)

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing changes. Application code must be authored manually by the developer and reviewed against the project’s learning goals.

## License

Licensed under the [MIT License](LICENSE).
