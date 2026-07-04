# Stock Ledger To Inventory Movement Mapping

## ERPNext Areas Reviewed

- `erpnext/stock`
- `erpnext/manufacturing`
- `erpnext/buying`

## NordForge Reference Data Products

- `acda4413_inventory_movements`
- `accu1533_customer_availability`
- `mart_supply.inventory_health_daily`

## Candidate Mapping

| NordForge Concept | ERPNext Candidate |
| --- | --- |
| Warehouse | Warehouse |
| SKU / Material | Item |
| Batch lot | Batch |
| Inventory movement | Stock Ledger Entry |
| Production consumption | Work Order / Stock Entry |
| Finished goods receipt | Stock Entry |
| Stock balance snapshot | Bin / Stock Balance |
| Movement type | Stock Entry Type / Purpose |

## Open Gaps

- Movement category normalization
- SAP-style movement type compatibility
- Stock aging risk flag
- Blocked-stock reason grouping
- Warehouse-zone enrichment
