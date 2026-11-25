# Non-Functional Requirements

These requirements describe intended qualities. Quantitative targets are provisional until measured and validated.

| ID | Area | Requirement |
|---|---|---|
| RNF-001 | Security | Authenticate protected operations through the planned external identity provider and enforce least privilege. |
| RNF-002 | Security | Validate untrusted input and avoid exposing sensitive information in logs or errors. |
| RNF-003 | Performance | Define service-level latency and throughput targets from measured local baselines; any interim numbers are provisional. |
| RNF-004 | Scalability | Keep services independently buildable and capable of independent scaling where state and dependencies permit. |
| RNF-005 | Resilience | Define timeouts and evaluate retry, backoff, circuit-breaker, and recovery policies per interaction. |
| RNF-006 | Observability | Correlate logs, metrics, and distributed traces using the planned OpenTelemetry foundation. |
| RNF-007 | Maintainability | Keep boundaries explicit, documentation current, and changes reviewable. |
| RNF-008 | Testability | Design contracts and components so developer-authored unit, integration, contract, and end-to-end tests are feasible. |
| RNF-009 | Interoperability | Use documented, versioned HTTP and event contracts across languages. |
| RNF-010 | Data ownership | Each service is the sole authority for its owned data; direct cross-service database access is prohibited. |
| RNF-011 | Consistency | Cross-service workflows must explicitly account for eventual consistency and observable intermediate states. |
| RNF-012 | Delivery | Message consumers must tolerate at-least-once delivery unless a different guarantee is evidenced and documented. |
| RNF-013 | Idempotency | Operations susceptible to retries or duplicate messages must define idempotent behavior. |
| RNF-014 | API documentation | Public service APIs must have maintained, version-aligned OpenAPI documentation. |
| RNF-015 | Event versioning | Events must carry identifiable versions and evolve compatibly or through an explicit migration plan. |
| RNF-016 | Local execution | The integrated backend must be reproducible in a documented local environment. |
| RNF-017 | Secrets | Secrets must not be committed; local values must use ignored files or an approved secret store. |
| RNF-018 | Privacy | Collect and expose only data required for the documented business purpose. |
