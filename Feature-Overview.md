# Feature Overview

## Summary

This document provides a complete list of all features implemented in the SAG Green Agent project.
Each feature has a unique ID assigned, and detailed specifications can be found in the `feature-detail/` folder.

**Related Documents:**
- [SAGGreen_Agent_Complete_Workflow.md](../backend-files/docs/SAGGreen_Agent_Complete_Workflow.md) - Complete workflow documentation
- [SAGGreen_Agent_Complete_Features_List.md](../backend-files/docs/SAGGreen_Agent_Complete_Features_List.md) - Detailed features list

---

## Complete Feature List

| No | Unique ID | Feature Name | Category | Details |
|----|-----------|--------------|----------|---------|
| 1 | CALC-MASS | Mass-based Calculation | Core Carbon Calculation Engine | [Details](./docs/feature-detail/001-CALC-MASS-Mass-based-Calculation.md) |
| 2 | CALC-SPEND | Spend-based Calculation | Core Carbon Calculation Engine | [Details](./docs/feature-detail/002-CALC-SPEND-Spend-based-Calculation.md) |
| 3 | CALC-DUAL | Dual Mode Calculation | Core Carbon Calculation Engine | [Details](./docs/feature-detail/003-CALC-DUAL-Dual-Mode-Calculation.md) |
| 4 | CALC-UNIT | Unit Conversion | Core Carbon Calculation Engine | [Details](./docs/feature-detail/004-CALC-UNIT-Unit-Conversion.md) |
| 5 | INPUT-CSV | CSV Upload | Data Ingestion & Integration | [Details](./docs/feature-detail/005-INPUT-CSV-CSV-Upload.md) |
| 6 | INPUT-EXCEL | Excel Upload | Data Ingestion & Integration | [Details](./docs/feature-detail/006-INPUT-EXCEL-Excel-Upload.md) |
| 7 | INPUT-MANUAL | Manual Form Entry | Data Ingestion & Integration | [Details](./docs/feature-detail/007-INPUT-MANUAL-Manual-Form-Entry.md) |
| 8 | INPUT-BULK | Bulk Data Import | Data Ingestion & Integration | [Details](./docs/feature-detail/008-INPUT-BULK-Bulk-Data-Import.md) |
| 9 | INPUT-API | API Integration | Data Ingestion & Integration | [Details](./docs/feature-detail/009-INPUT-API-API-Integration.md) |
| 10 | PROD-TAXONOMY | Product Taxonomy Mapping | AI Agentic Intelligence | [Details](./docs/feature-detail/010-PROD-TAXONOMY-Product-Taxonomy-Mapping.md) |
| 11 | PROD-AUTO-CAT | Auto Category Detection | AI Agentic Intelligence | [Details](./docs/feature-detail/011-PROD-AUTO-CAT-Auto-Category-Detection.md) |
| 12 | PROD-SIMILAR | Similar Item Suggestion | AI Agentic Intelligence | [Details](./docs/feature-detail/012-PROD-SIMILAR-Similar-Item-Suggestion.md) |
| 13 | EF-DEFAULT | Default EF Database | Emission Factor Management | [Details](./docs/feature-detail/013-EF-DEFAULT-Default-EF-Database.md) |
| 14 | EF-CUSTOM | Custom EF Management | Emission Factor Management | [Details](./docs/feature-detail/014-EF-CUSTOM-Custom-EF-Management.md) |
| 15 | EF-REGION | Region-based EF | Emission Factor Management | [Details](./docs/feature-detail/015-EF-REGION-Region-based-EF.md) |
| 16 | EF-VERSION | EF Version Control | Emission Factor Management | [Details](./docs/feature-detail/016-EF-VERSION-EF-Version-Control.md) |
| 17 | DATA-CLEAN | Auto Data Cleaning | Audit & Data Quality | [Details](./docs/feature-detail/017-DATA-CLEAN-Auto-Data-Cleaning.md) |
| 18 | DATA-MISSING | Missing Data Handling | Audit & Data Quality | [Details](./docs/feature-detail/018-DATA-MISSING-Missing-Data-Handling.md) |
| 19 | DATA-DUPLICATE | Duplicate Detection | Audit & Data Quality | [Details](./docs/feature-detail/019-DATA-DUPLICATE-Duplicate-Detection.md) |
| 20 | DATA-VALIDATE | Data Validation | Audit & Data Quality | [Details](./docs/feature-detail/020-DATA-VALIDATE-Data-Validation.md) |
| 21 | REPORT-TOTAL | Total CO₂ Emission Report | Dashboard & Visualization | [Details](./docs/feature-detail/021-REPORT-TOTAL-Total-CO₂-Emission-Report.md) |
| 22 | REPORT-SCOPE | Scope 1/2/3 Reports | Dashboard & Visualization | [Details](./docs/feature-detail/022-REPORT-SCOPE-Scope-1-2-3-Reports.md) |
| 23 | REPORT-CATEGORY | Category-wise Breakdown | Dashboard & Visualization | [Details](./docs/feature-detail/023-REPORT-CATEGORY-Category-wise-Breakdown.md) |
| 24 | REPORT-CHARTS | Charts and Trends | Dashboard & Visualization | [Details](./docs/feature-detail/024-REPORT-CHARTS-Charts-and-Trends.md) |
| 25 | REPORT-EXPORT | PDF/Excel Export | Dashboard & Visualization | [Details](./docs/feature-detail/025-REPORT-EXPORT-PDF-Excel-Export.md) |
| 26 | SCENARIO-WHATIF | What-if Simulation | Reporting & Analytics | [Details](./docs/feature-detail/026-SCENARIO-WHATIF-What-if-Simulation.md) |
| 27 | USER-MULTI | Multi-user System | User Management & Security | [Details](./docs/feature-detail/027-USER-MULTI-Multi-user-System.md) |
| 28 | USER-PROFILE | Company Profile | User Management & Security | [Details](./docs/feature-detail/028-USER-PROFILE-Company-Profile.md) |
| 29 | USER-ROLE | Role-based Access | User Management & Security | [Details](./docs/feature-detail/029-USER-ROLE-Role-based-Access.md) |
| 30 | AUDIT-TRAIL | Data Audit Trail | Compliance & Regulatory | [Details](./docs/feature-detail/030-AUDIT-TRAIL-Data-Audit-Trail.md) |
| 31 | AUDIT-HISTORY | Report History | Compliance & Regulatory | [Details](./docs/feature-detail/031-AUDIT-HISTORY-Report-History.md) |
| 32 | AUDIT-COMPLIANCE | Compliance Export | Compliance & Regulatory | [Details](./docs/feature-detail/032-AUDIT-COMPLIANCE-Compliance-Export.md) |
| 33 | PERF-ENGINE | Fast Calculation Engine | Performance & Tech | [Details](./docs/feature-detail/033-PERF-ENGINE-Fast-Calculation-Engine.md) |
| 34 | PERF-BACKGROUND | Background Job Processing | Performance & Tech | [Details](./docs/feature-detail/034-PERF-BACKGROUND-Background-Job-Processing.md) |
| 35 | PERF-DOCKER | Docker Support | Performance & Tech | [Details](./docs/feature-detail/035-PERF-DOCKER-Docker-Support.md) |
| 36 | PERF-API | API-first Architecture | Performance & Tech | [Details](./docs/feature-detail/036-PERF-API-API-first-Architecture.md) |
| 37 | BONUS-ML | ML Auto Classification | Future / Advanced Features | [Details](./docs/feature-detail/037-BONUS-ML-ML-Auto-Classification.md) |
| 38 | BONUS-BARCODE | Barcode/QR Scan | Future / Advanced Features | [Details](./docs/feature-detail/038-BONUS-BARCODE-Barcode-QR-Scan.md) |
| 39 | BONUS-REALTIME | Real-time Tracking | Future / Advanced Features | [Details](./docs/feature-detail/039-BONUS-REALTIME-Real-time-Tracking.md) |
| 40 | BONUS-ERP | ERP Integration | Future / Advanced Features | [Details](./docs/feature-detail/040-BONUS-ERP-ERP-Integration.md) |
| 41 | DATA-CONN-DOG | DOG Platform Data Connector | Data Ingestion & Integration | [Details](./docs/feature-detail/041-DATA-CONN-DOG-DOG-Platform-Data-Connector.md) |
| 42 | DATA-CONN-ORDIA | ORDIA Order Data Connector | Data Ingestion & Integration | [Details](./docs/feature-detail/042-DATA-CONN-ORDIA-ORDIA-Order-Data-Connector.md) |
| 43 | DATA-CONN-RIFLEX | Riflex/Odoo ERP Integration | Data Ingestion & Integration | [Details](./docs/feature-detail/043-DATA-CONN-RIFLEX-Riflex-Odoo-ERP-Integration.md) |
| 44 | DATA-CONN-CARRIER | Carrier API Integration | Data Ingestion & Integration | [Details](./docs/feature-detail/044-DATA-CONN-CARRIER-Carrier-API-Integration.md) |
| 45 | DATA-CONN-EF-SYNC | Emission Factor Database Sync | Data Ingestion & Integration | [Details](./docs/feature-detail/045-DATA-CONN-EF-SYNC-Emission-Factor-Database-Sync.md) |
| 46 | DATA-CONN-OCR | OCR Document Processing | Data Ingestion & Integration | [Details](./docs/feature-detail/046-DATA-CONN-OCR-OCR-Document-Processing.md) |
| 47 | DATA-CONN-IOT | IoT Sensor Data Ingestion | Data Ingestion & Integration | [Details](./docs/feature-detail/047-DATA-CONN-IOT-IoT-Sensor-Data-Ingestion.md) |
| 48 | DATA-CONN-PORTAL | Supplier Portal / Manual Entry | Data Ingestion & Integration | [Details](./docs/feature-detail/048-DATA-CONN-PORTAL-Supplier-Portal-Manual-Entry.md) |
| 49 | DATA-CONN-EMAIL | Email Parsing Engine | Data Ingestion & Integration | [Details](./docs/feature-detail/049-DATA-CONN-EMAIL-Email-Parsing-Engine.md) |
| 50 | REPORT-PASSPORT | Carbon Passport PDF Generator | Carbon Passport & Document Generation | [Details](./docs/feature-detail/050-REPORT-PASSPORT-Carbon-Passport-PDF-Generator.md) |
| 51 | REPORT-MULTI-FRAMEWORK | Multi-Framework Report Templates | Carbon Passport & Document Generation | [Details](./docs/feature-detail/051-REPORT-MULTI-FRAMEWORK-Multi-Framework-Report-Templates.md) |
| 52 | REPORT-AUDIT-PKG | Audit Data Package Generator | Carbon Passport & Document Generation | [Details](./docs/feature-detail/052-REPORT-AUDIT-PKG-Audit-Data-Package-Generator.md) |
| 53 | REPORT-SCHEDULE | Configurable Report Scheduling | Carbon Passport & Document Generation | [Details](./docs/feature-detail/053-REPORT-SCHEDULE-Configurable-Report-Scheduling.md) |
| 54 | REPORT-DPP | Digital Product Passport (DPP) | Carbon Passport & Document Generation | [Details](./docs/feature-detail/054-REPORT-DPP-Digital-Product-Passport-DPP-Data-Service.md) |
| 55 | DASH-REALTIME | Real-Time Carbon Dashboard | Dashboard & Visualization | [Details](./docs/feature-detail/055-DASH-REALTIME-Real-Time-Carbon-Dashboard.md) |
| 56 | DASH-PRODUCT | Product-Level Emission View | Dashboard & Visualization | [Details](./docs/feature-detail/056-DASH-PRODUCT-Product-Level-Emission-View.md) |
| 57 | DASH-SHIPMENT | Shipment-Level Emission View | Dashboard & Visualization | [Details](./docs/feature-detail/057-DASH-SHIPMENT-Shipment-Level-Emission-View.md) |
| 58 | DASH-SUPPLIER | Supplier-Level Emission View | Dashboard & Visualization | [Details](./docs/feature-detail/058-DASH-SUPPLIER-Supplier-Level-Emission-View.md) |
| 59 | DASH-ROUTE | Route-Level Emission View | Dashboard & Visualization | [Details](./docs/feature-detail/059-DASH-ROUTE-Route-Level-Emission-View.md) |
| 60 | DASH-SCOPE-CHART | Scope 3 Category Breakdown Chart | Dashboard & Visualization | [Details](./docs/feature-detail/060-DASH-SCOPE-CHART-Scope-3-Category-Breakdown-Chart.md) |
| 61 | DASH-TREND | Year-over-Year Trend Analysis | Dashboard & Visualization | [Details](./docs/feature-detail/061-DASH-TREND-Year-over-Year-Trend-Analysis.md) |
| 62 | DASH-COST-MATRIX | Cost vs. Carbon Matrix | Dashboard & Visualization | [Details](./docs/feature-detail/062-DASH-COST-MATRIX-Cost-vs-Carbon-Matrix.md) |
| 63 | DASH-MAP | Supply Chain Geographic Map | Dashboard & Visualization | [Details](./docs/feature-detail/063-DASH-MAP-Supply-Chain-Geographic-Map.md) |
| 64 | DASH-ALERT | Anomaly Detection Alerts | Dashboard & Visualization | [Details](./docs/feature-detail/064-DASH-ALERT-Anomaly-Detection-Alerts-on-Dashboard.md) |
| 65 | DASH-READY | Regulatory Readiness Status | Dashboard & Visualization | [Details](./docs/feature-detail/065-DASH-READY-Regulatory-Readiness-Status-Indicator.md) |
| 66 | DASH-DRILL | Drill-Down Analytics | Dashboard & Visualization | [Details](./docs/feature-detail/066-DASH-DRILL-Drill-Down-Analytics.md) |
| 67 | AI-PRA | Perceive-Reason-Act Intelligence | AI Agentic Intelligence | [Details](./docs/feature-detail/067-AI-PRA-Perceive-Reason-Act-Intelligence-Loop.md) |
| 68 | AI-DISRUPT | Supply Chain Disruption Detection | AI Agentic Intelligence | [Details](./docs/feature-detail/068-AI-DISRUPT-Supply-Chain-Disruption-Detection.md) |
| 69 | AI-SWITCH | Autonomous Supplier Switching | AI Agentic Intelligence | [Details](./docs/feature-detail/069-AI-SWITCH-Autonomous-Supplier-Switching.md) |
| 70 | AI-MODE | Advisory vs Autonomous Mode | AI Agentic Intelligence | [Details](./docs/feature-detail/070-AI-MODE-Advisory-Mode-vs-Autonomous-Mode.md) |
| 71 | AI-LLM | LLM-Powered Analysis & NLP | AI Agentic Intelligence | [Details](./docs/feature-detail/071-AI-LLM-LLM-Powered-Analysis-NLP.md) |
| 72 | AI-PREDICT | Predictive Analytics | AI Agentic Intelligence | [Details](./docs/feature-detail/072-AI-PREDICT-Predictive-Analytics.md) |
| 73 | AI-NOTIFY | Smart Notification Engine | AI Agentic Intelligence | [Details](./docs/feature-detail/073-AI-NOTIFY-Smart-Notification-Engine.md) |
| 74 | AI-CONFIDENCE | Confidence Scoring | AI Agentic Intelligence | [Details](./docs/feature-detail/074-AI-CONFIDENCE-Confidence-Scoring.md) |
| 75 | COMP-CBAM | EU CBAM Compliance Module | Compliance & Regulatory | [Details](./docs/feature-detail/075-COMP-CBAM-EU-CBAM-Compliance-Module.md) |
| 76 | COMP-SSBJ | Japan SSBJ Compliance Module | Compliance & Regulatory | [Details](./docs/feature-detail/076-COMP-SSBJ-Japan-SSBJ-Compliance-Module.md) |
| 77 | COMP-ISO14064 | ISO 14064 Compliance | Compliance & Regulatory | [Details](./docs/feature-detail/077-COMP-ISO14064-ISO-14064-Compliance.md) |
| 78 | COMP-ISO14067 | ISO 14067 Product Carbon Footprint | Compliance & Regulatory | [Details](./docs/feature-detail/078-COMP-ISO14067-ISO-14067-Product-Carbon-Footprint.md) |
| 79 | COMP-GHG | GHG Protocol Compliance | Compliance & Regulatory | [Details](./docs/feature-detail/079-COMP-GHG-GHG-Protocol-Compliance.md) |
| 80 | COMP-CSRD | CSRD Compliance Module | Compliance & Regulatory | [Details](./docs/feature-detail/080-COMP-CSRD-CSRD-Compliance-Module.md) |
| 81 | ROUTE-OPTIMIZE | Route Optimization Engine | Route & Supply Chain Optimization | [Details](./docs/feature-detail/081-ROUTE-OPTIMIZE-Route-Optimization-Engine.md) |
| 82 | ROUTE-CONSOLIDATE | Shipment Consolidation | Route & Supply Chain Optimization | [Details](./docs/feature-detail/082-ROUTE-CONSOLIDATE-Shipment-Consolidation.md) |
| 83 | ROUTE-COLDCHAIN | Cold-Chain Emission Calculator | Route & Supply Chain Optimization | [Details](./docs/feature-detail/083-ROUTE-COLDCHAIN-Cold-Chain-Emission-Calculator.md) |
| 84 | ROUTE-INTERMODAL | Intermodal Transport Optimization | Route & Supply Chain Optimization | [Details](./docs/feature-detail/084-ROUTE-INTERMODAL-Intermodal-Transport-Optimization.md) |
| 85 | ROUTE-DISTANCE | Distance & Transit Calculation | Route & Supply Chain Optimization | [Details](./docs/feature-detail/085-ROUTE-DISTANCE-Distance-Transit-Calculation.md) |
| 86 | JP-INTERFACE | Japan-Native Interface | Japan-Native Design | [Details](./docs/feature-detail/086-JP-INTERFACE-Japan-Native-Interface.md) |
| 87 | JP-REGULATORY | Japan Regulatory Framework | Japan-Native Design | [Details](./docs/feature-detail/087-JP-REGULATORY-Japan-Regulatory-Framework.md) |
| 88 | JP-ENERGY | Japan Grid Emission Factors | Japan-Native Design | [Details](./docs/feature-detail/088-JP-ENERGY-Japan-Grid-Emission-Factors.md) |
| 89 | JP-TRANSPORT | Japan Domestic Transport | Japan-Native Design | [Details](./docs/feature-detail/089-JP-TRANSPORT-Japan-Domestic-Transport.md) |
| 90 | JP-BRP | BRP-Code Product Taxonomy | Japan-Native Design | [Details](./docs/feature-detail/090-JP-BRP-BRP-Code-Product-Taxonomy.md) |
| 91 | JP-PARTNER | Japan Partner Ecosystem | Japan-Native Design | [Details](./docs/feature-detail/091-JP-PARTNER-Japan-Partner-Ecosystem.md) |
| 92 | AUTH-LOGIN | User Login | Authentication & Authorization | [Details](./docs/feature-detail/092-AUTH-LOGIN-User-Login.md) |
| 93 | AUTH-REGISTER | User Registration | Authentication & Authorization | [Details](./docs/feature-detail/093-AUTH-REGISTER-User-Registration.md) |
| 94 | IAM-COMP-GET | Company Get | Identity & Access Management | [Details](./docs/feature-detail/094-IAM-COMP-GET-Company-Get.md) |
| 95 | IAM-USER-LIST | User List | Identity & Access Management | [Details](./docs/feature-detail/095-IAM-USER-LIST-User-List.md) |
| 96 | IAM-USER-ROLE | User Role Management | Identity & Access Management | [Details](./docs/feature-detail/096-IAM-USER-ROLE-User-Role-Management.md) |
| 97 | AUTH-LOGOUT | User Logout | Authentication & Authorization | [Details](./docs/feature-detail/097-AUTH-LOGOUT-User-Logout.md) |
| 98 | AUTH-FORGOT-PASSWORD | Forgot Password | Authentication & Authorization | [Details](./docs/feature-detail/098-AUTH-FORGOT-PASSWORD-Forgot-Password.md) |
| 99 | AUTH-RESET-PASSWORD | Reset Password | Authentication & Authorization | [Details](./docs/feature-detail/099-AUTH-RESET-PASSWORD-Reset-Password.md) |
| 100 | AUTH-MFA | Multi-Factor Authentication | Authentication & Authorization | [Details](./docs/feature-detail/100-AUTH-MFA-Multi-Factor-Authentication.md) |
| 101 | IAM-COMP-LIST | Company List | Identity & Access Management | [Details](./docs/feature-detail/101-IAM-COMP-LIST-Company-List.md) |
| 102 | IAM-COMP-UPDATE | Company Update | Identity & Access Management | [Details](./docs/feature-detail/102-IAM-COMP-UPDATE-Company-Update.md) |
| 103 | IAM-USER-GET | User Get | Identity & Access Management | [Details](./docs/feature-detail/103-IAM-USER-GET-User-Get.md) |
| 104 | IAM-USER-UPDATE | User Update | Identity & Access Management | [Details](./docs/feature-detail/104-IAM-USER-UPDATE-User-Update.md) |
| 105 | IAM-USER-CREATE | User Create | Identity & Access Management | [Details](./docs/feature-detail/105-IAM-USER-CREATE-User-Create.md) |
| 106 | IAM-USER-DELETE | User Delete | Identity & Access Management | [Details](./docs/feature-detail/106-IAM-USER-DELETE-User-Delete.md) |

---

## Feature Categories

### Core Calculation Features
- Mass-based, spend-based, and dual mode calculations
- Automatic unit conversions

### Smart Input System
- Multiple input methods: CSV, Excel, manual, bulk import
- API integration for external systems

### Product Intelligence
- Taxonomy mapping and auto-categorization
- AI-like similar item suggestions

### Emission Factor Management
- Default and custom EF databases
- Regional and version-controlled EFs

### Data Processing Engine
- Data cleaning, validation, and duplicate handling

### Reporting & Dashboard
- Comprehensive emission reports and visualizations
- Export capabilities

### Scenario Analysis
- What-if simulations for emission reduction strategies

### User & Company Management
- Multi-user support with role-based access

### Audit & Compliance
- Full audit trails and compliance-ready exports

### Performance & Tech Features
- High-performance processing and deployment options

### Bonus Features (Future)
- Advanced ML features and integrations</content>
<parameter name="filePath">c:\ASAD\sag-green-agent\Feature-Overview.md