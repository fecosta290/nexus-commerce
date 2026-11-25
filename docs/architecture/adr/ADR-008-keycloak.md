# ADR-008: Keycloak

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Identity should remain outside commerce service data ownership.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

Custom identity service; managed cloud identity; alternative local provider; Keycloak.

## Decision

Use Keycloak as the proposed external identity provider.

## Rationale

Provides standards-based local identity capabilities without making identity implementation the main project.

## Positive consequences

- Configuration, role modeling, upgrades, and local resource usage add complexity.

## Negative consequences

- Run a timeboxed authentication and authorization Spike before protected business endpoints are implemented.

## Validation strategy

undefined
