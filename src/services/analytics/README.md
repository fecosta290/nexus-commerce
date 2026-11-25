# Analytics Service

**Status: Planned — Not implemented.**

## Business purpose

Build derived business views and metrics without becoming a source of transactional truth.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Transactional decisions, operational service ownership, or direct cross-service database queries.

## Planned technology stack

TypeScript, Node.js, and MongoDB. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Derived analytics models in MongoDB. Other services must not access this persistence directly.

## Expected integrations

Catalog, Inventory, Customers, Ordering, Payments, Promotions, and event infrastructure.

## Related requirements and Epics

Related requirements: RNF-006, RNF-010, RNF-011, RNF-012, RNF-015, RNF-018. Related Epics: EPIC-013.

## Technical learning objectives

Advanced TypeScript, Node.js concurrency, event consumers, document models, aggregation, and data quality.

## Potential engineering challenges

Late and duplicate events, rebuilds, schema evolution, privacy, metric definitions, and data lineage.

## Pending architectural decisions

Initial metrics, event inputs, replay strategy, retention, freshness expectations, and query interface.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
