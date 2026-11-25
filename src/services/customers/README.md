# Customers Service

**Status: Planned — Not implemented.**

## Business purpose

Manage commerce customer profiles independently from authentication credentials.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Credential storage, identity-provider administration by default, orders, payments, and notification delivery.

## Planned technology stack

C#, ASP.NET Core, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Customer profiles in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Gateway, Keycloak, Ordering, Notifications, and Analytics through reviewed contracts.

## Related requirements and Epics

Related requirements: RNF-001, RNF-002, RNF-010, RNF-018. Related Epics: EPIC-005 (with identity concerns in EPIC-004).

## Technical learning objectives

Advanced C#, privacy-aware API design, relational persistence, identity mapping, and authorization.

## Potential engineering challenges

Identity/profile synchronization, personal-data minimization, deletion obligations, and auditability.

## Pending architectural decisions

Profile fields, identity linkage, consent needs, retention, authorization rules, and event boundaries.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
