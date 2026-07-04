# Order-To-Cash Fit-Gap

## ERPNext Areas Reviewed

- `erpnext/selling`
- `erpnext/stock`
- `erpnext/accounts`
- `erpnext/support`

## NordForge Reference Data Products

- `accu1932_order_fulfillment`
- `accu1533_customer_availability`
- `accu7392_customer_service`

## Initial Findings

| Area | Fit Assessment | Notes |
| --- | --- | --- |
| Customer master | Fit | ERPNext Customer can support basic master-data review |
| Sales order | Fit | Sales Order maps naturally to order intake |
| Delivery note | Partial fit | Needs validation against NordForge shipping-point logic |
| ATP and allocation | Gap | NordForge has more detailed ATP and allocation-segment logic |
| Blocked stock | Partial fit | Needs reason-code and customer promise mapping |
| Credit block | Needs pilot | Requires finance workflow review |

## Recommendation

ERPNext may be suitable for a smaller business-unit pilot, but NordForge should not assume parity with current SAP-style ATP and fulfillment logic without a sandbox process review.
