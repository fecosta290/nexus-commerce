# Ordering Service

**Status: Planned — Not implemented.**

## Business purpose

Own the order lifecycle and preserve immutable purchase-time item and price snapshots.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Current catalog truth, stock ownership, payment execution, coupon ownership, and notification delivery.

## Planned technology stack

C#, ASP.NET Core, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Orders and order history in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Catalog, Inventory, Customers, Payments, Promotions, Notifications, and Analytics.

## Related requirements and Epics

Related requirements: RN-005, RN-006, RN-007, RN-008, RN-014, RN-015, RN-016, RN-017, RN-018. Related Epics: EPIC-006.

## Technical learning objectives

Advanced C#, aggregate consistency, workflow modeling, relational persistence, and distributed coordination.

## Potential engineering challenges

Multi-service confirmation, partial failure, immutable history, compensation, and idempotency.

## Pending architectural decisions

Order state model, Saga coordination style, price source, cancellation policy, and event contracts.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
