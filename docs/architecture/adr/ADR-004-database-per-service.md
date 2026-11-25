# ADR-004: Database per Service

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Independent boundaries require unambiguous authority and prevention of hidden coupling.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

Shared database; shared schemas; database per service.

## Decision

Give each service exclusive access to its owned persistence.

## Rationale

Supports autonomy, explicit contracts, and independent evolution.

## Positive consequences

- Cross-service queries and transactions become distributed concerns.

## Negative consequences

- Review ownership maps and prove reporting and order workflows without cross-database access.

## Validation strategy

undefined
