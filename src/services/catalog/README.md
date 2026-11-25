# Catalog Service

**Status: Planned — Not implemented.**

## Business purpose

Manage product identity, descriptive information, lifecycle state, SKU uniqueness, and current pricing.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Inventory quantities, order history, discount calculation, recommendation models, and binary file processing.

## Planned technology stack

C#, ASP.NET Core, and MongoDB. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Catalog documents in MongoDB. Other services must not access this persistence directly.

## Expected integrations

Gateway, Inventory, Ordering, Promotions, Recommendations, File Processing, and Analytics through reviewed contracts.

## Related requirements and Epics

Related requirements: RN-001, RN-002, RN-003, RN-018; RNF-009, RNF-010, RNF-015. Related Epics: EPIC-002.

## Technical learning objectives

Advanced C#, ASP.NET Core API design, document persistence, validation, concurrency, and contract evolution.

## Potential engineering challenges

SKU uniqueness under concurrency, price-change propagation, document evolution, and event consistency.

## Pending architectural decisions

Product lifecycle model, indexing, event boundaries, image references, and internal architecture.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
