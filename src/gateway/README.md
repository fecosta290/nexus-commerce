# API Gateway

**Status: Planned — Not implemented.**

## Business purpose

Route external traffic, centralize cross-cutting edge concerns, and shield internal topology.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Business rules, service orchestration by default, identity storage, or domain data ownership.

## Planned technology stack

C# and YARP; no persistence. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Routing configuration and edge policy; no business persistence. Other services must not access this persistence directly.

## Expected integrations

Catalog, Inventory, Customers, Ordering, Payments, and Keycloak as contracts require.

## Related requirements and Epics

Related requirements: RNF-001, RNF-003, RNF-005, RNF-006, RNF-009. Related Epics: EPIC-014.

## Technical learning objectives

Advanced ASP.NET Core middleware, reverse proxies, security boundaries, routing, rate policies, and observability.

## Potential engineering challenges

Avoiding a gateway bottleneck, safe route evolution, authentication propagation, and correlated diagnostics.

## Pending architectural decisions

Route model, authorization boundaries, aggregation policy, rate limiting, health behavior, and version routing.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../docs/architecture/overview.md) and [communication strategy](../../docs/architecture/communication-strategy.md).
