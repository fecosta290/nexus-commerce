# ADR-001: Microservices Architecture

- **Status:** Proposed
- **Date:** 2026-11-25

## Context

Separate deployable service boundaries are proposed to support distributed-systems learning and capability ownership.

## Decision drivers

- Educational value and fit with the documented product scope.
- Clear ownership, interoperability, and local-development feasibility.
- An individual developer’s learning capacity and operational overhead.

## Alternatives

A modular monolith; a small number of larger services; independently bounded microservices.

## Decision

Use independently bounded microservices.

## Rationale

Aligns with the educational objective and planned polyglot service catalog.

## Positive consequences

- Clear ownership and focused technology learning.

## Negative consequences

- Substantial operational, consistency, testing, and observability complexity.

## Validation strategy

Validate boundaries with context/container reviews and one thin end-to-end backend slice before broad expansion.
