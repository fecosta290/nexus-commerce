# Communication Strategy

## Synchronous communication

REST is proposed when a caller needs an immediate response, such as queries or validation needed to continue a user-facing operation. Contracts should be documented with OpenAPI, versioned deliberately, protected by timeouts, and observed end to end. Synchronous dependency chains should remain short.

## Asynchronous communication

RabbitMQ is proposed for business events, decoupled reactions, and workflows that tolerate eventual consistency. Events should state facts, identify their schema version, include correlation metadata, and avoid leaking private service internals.

At-least-once delivery is the working assumption, so consumers must be idempotent. Outbox, Inbox, retry with exponential backoff, dead-letter queues, and replay policies remain candidates requiring ADR-level or implementation-level validation.

## Workflow consistency

Order confirmation spans inventory and simulated payment decisions. Saga-style coordination and compensating actions are candidates; choreography versus orchestration is unresolved. Intermediate states must be explicit and observable. Notification failure must not reverse a confirmed order.

## Contract governance

Proposed OpenAPI material belongs in [`contracts/openapi/`](../../contracts/openapi/), and event definitions in [`contracts/events/`](../../contracts/events/). Compatibility rules, ownership, retention, security, and failure semantics must be reviewed before implementation.
