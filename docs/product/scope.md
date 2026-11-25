# Product Scope

## Initial scope

Nexus Commerce is planned to include:

- Customer management.
- Product catalog.
- Inventory management and expiring reservations.
- Order processing.
- Simulated payments and refund initiation.
- Promotions and coupons.
- Notifications.
- Product recommendations.
- File and image processing.
- Business analytics.

## Explicit exclusions

The initial scope excludes real payment processing, tax integrations, shipping-carrier integrations, multi-tenancy, a multi-vendor marketplace, mobile applications, Kubernetes, mandatory cloud infrastructure, and frontend implementation before backend validation.

## Boundary principles

Each capability owns its data and exposes behavior through explicit contracts. Cross-service workflows must tolerate partial failure and eventual consistency. Detailed endpoints, schemas, and internal patterns remain pending implementation-time decisions.

## Scope control

Proposed additions should be represented in GitHub Issues, related to a Feature and Epic, and evaluated against the [vision](vision.md), [roadmap](roadmap.md), and individual-developer capacity. The complete backlog is not duplicated in Markdown.
