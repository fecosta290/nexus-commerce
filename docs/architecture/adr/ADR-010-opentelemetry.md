# ADR-010: OpenTelemetry

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Distributed workflows require vendor-neutral correlation across languages.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

Vendor-specific agents; logs only; custom instrumentation; OpenTelemetry.

## Decision

Use OpenTelemetry as the proposed telemetry foundation.

## Rationale

Supports traces, metrics, and logs across the polyglot stack and planned observability tools.

## Positive consequences

- Instrumentation consistency, sampling, storage, and cost need governance.

## Negative consequences

- Prove correlation across an early REST call and event flow, then document semantic conventions.

## Validation strategy

undefined
