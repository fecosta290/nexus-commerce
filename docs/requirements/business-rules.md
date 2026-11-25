# Business Rules

These rules are established product constraints. Implementation details remain open.

| ID | Rule |
|---|---|
| RN-001 | Every product must have a unique SKU. |
| RN-002 | Product prices must be greater than zero. |
| RN-003 | Inactive products cannot be included in new purchases. |
| RN-004 | Available inventory cannot become negative. |
| RN-005 | An order must contain at least one item before submission. |
| RN-006 | Order item quantities must be positive. |
| RN-007 | Orders must preserve the price applied at purchase time. |
| RN-008 | Orders can only be confirmed after payment approval and inventory confirmation. |
| RN-009 | Rejected payments must trigger inventory reservation release. |
| RN-010 | Payment operations must not produce duplicate charges. |
| RN-011 | Expired coupons cannot be used. |
| RN-012 | Discounts cannot produce negative order totals. |
| RN-013 | Inventory reservations must have an expiration mechanism. |
| RN-014 | Cancellation of paid orders must initiate a refund process. |
| RN-015 | Notification failures must not invalidate confirmed orders. |
| RN-016 | Submitted order items cannot be modified. |
| RN-017 | Monetary values must preserve decimal precision. |
| RN-018 | Catalog price changes must not affect historical orders. |

Traceability to stories and verification evidence will be maintained in GitHub Issues rather than duplicated here.
