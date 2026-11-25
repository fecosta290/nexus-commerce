# Architecture Overview

## Current state

Nexus Commerce is in Planning / Sprint 0. The repository contains organizational and design material only; no service or infrastructure is implemented.

## Proposed style

The planned system is a monorepo of independently bounded microservices. Each service owns its persistence, is independently buildable, and communicates through explicit versioned contracts. Client traffic is expected to enter through a YARP API Gateway. Keycloak is proposed as the external identity provider.

Synchronous request/response interactions use REST where an immediate answer is required. RabbitMQ-based events are proposed for decoupled workflows and state propagation. OpenTelemetry is proposed to underpin distributed tracing, metrics, and correlated logging.

## Principles

- Independent service boundaries and builds.
- Database per Service and explicit data ownership.
- REST and event-driven communication selected by interaction needs.
- API Gateway at the external boundary.
- External identity provider.
- Distributed tracing and observable failure.
- Contract versioning and compatibility.
- No direct access to another service’s database.

Saga, Outbox, Inbox, idempotency, retry, exponential backoff, circuit breaker, dead-letter queues, optimistic concurrency, and CQRS are future study and implementation candidates. Their use is not mandated globally.

Domain-Driven Design and Clean Architecture are not enforced across every service. Internal patterns will be evaluated per service and recorded when consequential.

## Views and decisions

See the [service catalog](service-catalog.md), [communication strategy](communication-strategy.md), [diagram plan](diagrams/README.md), and [proposed ADRs](adr/README.md).
