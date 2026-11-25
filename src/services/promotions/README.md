# Promotions Service

**Status: Planned — Not implemented.**

## Business purpose

Manage coupons, promotion eligibility, and bounded discount calculation.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Catalog pricing ownership, final order lifecycle, payment execution, and customer identity.

## Planned technology stack

Ruby, Rails API, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Promotions, coupons, and redemption facts in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Catalog, Ordering, Customers, and Analytics through reviewed contracts.

## Related requirements and Epics

Related requirements: RN-011, RN-012, RN-017; RNF-009, RNF-010, RNF-013. Related Epics: EPIC-010.

## Technical learning objectives

Progressive Ruby, Rails API conventions, relational persistence, validation, concurrency, and testing ecosystem.

## Potential engineering challenges

Concurrent coupon use, deterministic calculations, decimal precision, eligibility changes, and auditability.

## Pending architectural decisions

Promotion composition, redemption model, usage limits, time semantics, conflict policy, and event boundaries.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
