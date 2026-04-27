# DATA-CONN-DOG: DOG Platform Data Connector

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | DATA-CONN-DOG |
| Feature Name | DOG Platform Data Connector |
| Category | Data Ingestion & Integration |
| Priority | Critical |
| Implementation Phase | Phase 1 → Phase 2 |

---

## Purpose

DOG B2B marketplace (2012 theke operational, 100+ retailers, 50+ manufacturers) theke order data extract korbe.

---

## Data Fields Extracted

| Field | Description |
|-------|-------------|
| Transaction Records | Complete order history |
| Supplier-Retailer Mappings | Who buys from whom |
| Product Categories | BRP-Code classification |
| Shipping Routes | Origin-to-destination paths |
| Order Volumes | Historical and current |
| Delivery Timelines | Transit times by route |
| Pricing Data | Cost per unit (for cost-carbon tradeoff) |

---

## Collection Phases

| Phase | Method | Description |
|-------|--------|-------------|
| Phase 1 | CSV export | Manual data export |
| Phase 2 | API connector | Scheduled pulls (hourly/daily) |
| Phase 3 | Webhooks | Real-time updates |

---

## API Integration

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/connectors/dog/orders | GET | Fetch orders |
| /api/connectors/dog/products | GET | Fetch products |
| /api/connectors/dog/shipments | GET | Fetch shipments |

---

## Implementation Notes

- Primary data source for order data
- Automatic BRP-Code mapping
- Historical data import supported

---

## Related Features

- DATA-CONN-ORDIA (ORDIA Order Data Connector)
- INPUT-CSV (CSV Upload)
- PROD-TAXONOMY (Product Taxonomy Mapping)