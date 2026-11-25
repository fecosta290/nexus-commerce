# Recommendations Service

**Status: Planned — Not implemented.**

## Business purpose

Generate explainable product recommendations from permitted commerce signals.

## Responsibilities

Own the capability described above, enforce its applicable rules, publish or expose reviewed contracts, and produce operational evidence for its work.

## Outside its scope

Authoritative catalog, order, customer, or analytics data; automated decisions with material customer impact.

## Planned technology stack

Python, FastAPI, and PostgreSQL. No project has been initialized and the stack remains subject to proposed ADR review.

## Data ownership

Recommendation inputs or models and generated results in PostgreSQL. Other services must not access this persistence directly.

## Expected integrations

Catalog, Ordering, Customers, and Analytics through privacy-reviewed contracts.

## Related requirements and Epics

Related requirements: RNF-002, RNF-010, RNF-011, RNF-018. Related Epics: EPIC-012.

## Technical learning objectives

Python API engineering, FastAPI, typing, persistence, asynchronous work, evaluation, and responsible data use.

## Potential engineering challenges

Sparse data, stale inputs, privacy, explainability, reproducibility, and measuring usefulness.

## Pending architectural decisions

Initial algorithm, input events, cold-start behavior, retention, evaluation metrics, and refresh cadence.

No classes, schemas, methods, or finalized endpoints are defined by this document. See the [architecture overview](../../../docs/architecture/overview.md) and [communication strategy](../../../docs/architecture/communication-strategy.md).
