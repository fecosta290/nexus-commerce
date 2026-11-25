# ADR-005: RabbitMQ

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Planned asynchronous workflows need a local message broker suitable for learning delivery semantics.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

In-process messaging; another broker; brokerless HTTP callbacks; RabbitMQ.

## Decision

Use RabbitMQ for proposed asynchronous event communication.

## Rationale

Fits local learning goals and supports routing, acknowledgements, and dead-letter patterns.

## Positive consequences

- Adds broker operations and requires disciplined idempotency and schema evolution.

## Negative consequences

- Prototype a versioned event with duplicate delivery, retry, and dead-letter scenarios.

## Validation strategy

undefined
