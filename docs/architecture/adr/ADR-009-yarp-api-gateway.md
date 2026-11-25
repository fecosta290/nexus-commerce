# ADR-009: YARP API Gateway

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

External clients need a stable entry boundary over evolving internal services.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

Direct client-to-service access; alternative gateway; backend-for-frontend; YARP.

## Decision

Use YARP in a C# API Gateway.

## Rationale

Integrates with the planned .NET ecosystem and supports explicit proxy customization.

## Positive consequences

- Can become a bottleneck or accumulate business orchestration.

## Negative consequences

- Validate routing, identity propagation, observability, failure isolation, and configuration changes.

## Validation strategy

undefined
