# Notifications Service

**Status: Planned — Not implemented.**

## Business purpose

Process notification requests without coupling delivery failure to confirmed commerce outcomes.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Order confirmation, customer profile ownership, identity, and business transaction rollback.

## Planned technology stack

Go, framework to be evaluated, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Notification requests, attempts, and outcomes in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Ordering, Payments, Customers, and the planned message broker.

## Related requirements and Epics

Related requirements: RN-015; RNF-005, RNF-006, RNF-012, RNF-013, RNF-015. Related Epics: EPIC-009 (and EPIC-008).

## Technical learning objectives

Progressive Go, HTTP APIs, concurrency, cancellation, persistence, message consumption, and graceful shutdown.

## Potential engineering challenges

At-least-once delivery, retries, duplicate suppression, provider abstraction, and poison messages.

## Pending architectural decisions

Go framework, channels, templates, retry policy, retention, user preferences, and DLQ handling.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
