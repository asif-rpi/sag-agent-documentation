# DATA-CONN-ORDIA: ORDIA Order Data Connector

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | DATA-CONN-ORDIA |
| Feature Name | ORDIA Order Data Connector |
| Category | Data Ingestion & Integration |
| Priority | Critical |
| Implementation Phase | Phase 2 |

---

## Purpose

ORDIA AI-powered order automation system theke data extract korbe. ORDIA fax, email, Excel theke AI/NLP use kore orders digitize kore.

---

## Data Fields

| Field | How Extracted |
|-------|---------------|
| Product Code (BRP-Code) | Auto-mapped via NLP |
| Order Quantity | Parsed from order document |
| Supplier ID | Matched from DOG database |
| Delivery Address | Parsed from order document |
| Order Date/Time | Auto-captured |
| Order Channel | Auto-detected (fax/email/Excel) |

---

## Collection Phases

| Phase | Method | Description |
|-------|--------|-------------|
| Phase 1 | CSV export | From ORDIA processed orders |
| Phase 2 | REST API | Real-time JSON |
| Phase 3 | Webhooks | Event-based streaming |

---

## NLP Capabilities

| Capability | Description |
|------------|-------------|
| Fax Parsing | Extract order details from fax |
| Email Parsing | Parse shipping confirmations |
| Excel Processing | Handle structured data |
| OCR | Scanned document processing |

---

## Implementation Notes

- AI-powered data extraction
- Reduces manual data entry
- Multi-channel order support

---

## Related Features

- DATA-CONN-DOG (DOG Platform Data Connector)
- INPUT-CSV (CSV Upload)
- BONUS-ML (ML Auto Classification)