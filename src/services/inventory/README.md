# Inventory Service

**Status: Planned — Not implemented.**

## Business purpose

Track stock availability and manage time-bounded inventory reservations.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Product descriptions, customer data, order lifecycle, payment decisions, and shipping.

## Planned technology stack

C#, ASP.NET Core, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Inventory balances and reservations in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Catalog, Ordering, Payments, and Analytics through reviewed REST or event contracts.

## Related requirements and Epics

Related requirements: RN-004, RN-009, RN-013; RNF-005, RNF-011, RNF-013. Related Epics: EPIC-003.

## Technical learning objectives

Advanced C#, transactional consistency, relational persistence, concurrency control, and expiring work.

## Potential engineering challenges

Preventing overselling, releasing expired reservations, duplicate messages, contention, and recovery.

## Pending architectural decisions

Reservation lifecycle, locking strategy, expiration scheduler, allocation policy, and event publication.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
