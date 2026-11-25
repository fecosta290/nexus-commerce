# Service Catalog

All components have **Status: Planned — Not implemented.**

| Component | Primary purpose | Data ownership | Related Epics |
|---|---|---|---|
| API Gateway | Route and govern external API traffic | None | EPIC-014 |
| Catalog | Product information, lifecycle, and current pricing | Product catalog in MongoDB | EPIC-002 |
| Inventory | Stock and expiring reservations | Inventory in PostgreSQL | EPIC-003 |
| Customers | Customer profiles | Customer data in PostgreSQL | EPIC-005 |
| Ordering | Order lifecycle and purchase-time snapshots | Orders in PostgreSQL | EPIC-006 |
| Payments | Simulated payment and refund processing | Payment records in PostgreSQL | EPIC-007 |
| Notifications | Delivery requests and outcomes | Notification records in PostgreSQL | EPIC-009 |
| Promotions | Coupons and discount qualification | Promotion data in PostgreSQL | EPIC-010 |
| Recommendations | Recommendation generation | Recommendation data in PostgreSQL | EPIC-012 |
| File Processing | File and image processing | Local file storage and metadata boundary to be decided | EPIC-011 |
| Analytics | Derived business insights | Analytics models in MongoDB | EPIC-013 |
| Frontend | Browser-based user experience after backend validation | None | EPIC-018 |

Detailed boundaries and learning objectives are maintained in each component README under [`src/`](../../src/README.md).
