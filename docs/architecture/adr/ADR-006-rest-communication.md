# ADR-006: REST Communication

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Services need interoperable synchronous request/response contracts across languages.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

gRPC; GraphQL; asynchronous-only integration; REST.

## Decision

Use HTTP REST for synchronous service communication where an immediate response is necessary.

## Rationale

Broad tooling support and approachable cross-language documentation.

## Positive consequences

- Runtime coupling, cascading failures, and versioning discipline remain concerns.

## Negative consequences

- Validate OpenAPI compatibility, timeout behavior, tracing, and failure handling in an early integration.

## Validation strategy

undefined
