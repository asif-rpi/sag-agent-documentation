# DATA-CONN-RIFLEX: Riflex/Odoo ERP Integration

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | DATA-CONN-RIFLEX |
| Feature Name | Riflex/Odoo ERP Integration |
| Category | Data Ingestion & Integration |
| Priority | High |
| Implementation Phase | Phase 2-3 |

---

## Purpose

Riflex ERP (Odoo-based SaaS) theke inventory, purchase orders, supplier history extract korbe using Odoo's built-in REST API.

---

## Data Fields & Odoo API Endpoints

| Data | Odoo API Endpoint |
|------|-------------------|
| Inventory Levels | stock.quant |
| Purchase Orders | purchase.order |
| Supplier Directory | res.partner |
| Warehouse Data | stock.warehouse |
| Invoice Data | account.move |
| Product Master | product.product |
| Manufacturing Orders | mrp.production |

---

## Connection Methods

| Method | Protocol | Sync Frequency |
|--------|----------|----------------|
| XML-RPC | HTTP | Configurable |
| JSON-RPC | HTTP | Real-time/Hourly/Daily |

---

## Sync Features

| Feature | Description |
|---------|-------------|
| Bidirectional Sync | ERP ↔ SAGGreen |
| Field Mapping | Custom field mapping |
| Conflict Resolution | Priority-based |
| Error Handling | Retry logic |

---

## Implementation Notes

- Odoo-based SaaS integration
- Real-time inventory sync
- Purchase order import

---

## Related Features

- DATA-CONN-DOG (DOG Platform Data Connector)
- INPUT-API (API Integration)
- BONUS-ERP (ERP Integration)