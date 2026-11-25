# ADR-002: Monorepo Strategy

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

The project needs coordinated documentation and discoverable contracts across multiple languages.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

Multiple repositories; monorepo.

## Decision

Keep services and shared planning material in one repository while preserving independent builds.

## Rationale

Reduces administrative overhead for an individual developer and makes cross-service changes visible.

## Positive consequences

- Repository tooling and ownership boundaries require discipline as it grows.

## Negative consequences

- Confirm independent build isolation and review cross-service change ergonomics during early releases.

## Validation strategy

undefined
