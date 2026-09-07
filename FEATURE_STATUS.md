# Feature status — Procurement & supplier management

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 282 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 8 | 0 | Native records/view |
| Activity & audit trail | audit | 11 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Marketplace offer library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer reseller registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product entitlement tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage metering ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commitment drawdown | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discount tier validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketplace fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reseller margin calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seller payout reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund credit control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency tax validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal expiration monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketplace dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offer channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MSA and order-form library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site cage and rack registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Power meter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PUE and power-charge recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-connect inventory reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remote-hands charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recurring service reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Install and decommission billing control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Uptime SLA monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident and maintenance evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SLA credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capacity commitment tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice exception workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider claim and response tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery and unit-cost analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Packaging agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SKU specification registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commodity index ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index publication validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Formula lag calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conversion cost validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Freight component audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume tier calculation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lightweighting adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scrap factor control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price effective-date check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Material supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SKU and service catalog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase-order ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract-price reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume discount validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index escalation verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Most-favored-pricing control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Freight-term validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Surcharge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate and split-order detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate accrual calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier exception workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debit memo generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier and category leakage analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Release schedule control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Goods receipt matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service entry validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return-to-vendor linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice line ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unit-of-measure conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quantity tolerance control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate receipt detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Short shipment analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Three-way match calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment overage detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier claim workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technology Vendor Registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract & Order-Form Intelligence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice & Purchase-Order Reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Identity & Account Normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unused & Orphaned Seat Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License-Tier Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entitlement Reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shadow SaaS Discovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal Calendar & Notice Control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal Negotiation Workbench | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AWS Commitment Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Azure Reservation & Savings-Plan Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Google Cloud CUD Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commitment Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cloud Waste & Rightsizing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Showback & Chargeback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Savings Approval Workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Realized-Savings Ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Software procurement negotiator work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible product registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Net purchase calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return exclusion control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth baseline calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product mix incentive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer project exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate accrual ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor contract risk monitor work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tenant | records | 1 | 0 | Native records/view |
| Vendor | records | 1 | 0 | Native records/view |
| Vendor document | records | 1 | 0 | Native records/view |
| Bid | records | 1 | 0 | Native records/view |
| Bid document | records | 1 | 0 | Native records/view |
| Bid evaluation | records | 1 | 0 | Native records/view |
| Vendor evaluation | records | 1 | 0 | Native records/view |
| Compliance check | records | 1 | 0 | Native records/view |
| Notification | records | 1 | 0 | Native records/view |
| Result | records | 1 | 0 | Native records/view |
| AI Risk Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Synergy Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Valuation Modeler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Red Flag Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Integration Planner | integration | 1 | 0 | AI question-and-answer workspace; records available as context |
| Companies | records | 1 | 0 | Native records/view |
| Financials | records | 1 | 0 | Native records/view |
| News | records | 1 | 0 | Native records/view |
| Risks | records | 1 | 0 | Native records/view |
| Redflags | records | 1 | 0 | Native records/view |
| Market | records | 1 | 0 | Native records/view |
| Competitors | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Legal | records | 1 | 0 | Native records/view |
| Management | records | 1 | 0 | Native records/view |
| Deals | records | 2 | 0 | Native records/view |
| Watchlist | records | 1 | 0 | Native records/view |
| Key person risk map | records | 1 | 0 | Native records/view |
| Acquisition modernization | records | 1 | 0 | Native records/view |
| Targets | records | 1 | 0 | Native records/view |
| Advisors | records | 1 | 0 | Native records/view |
| VDR Documents | records | 1 | 0 | Native records/view |
| Q&A | records | 1 | 0 | Native records/view |
| Working Groups | records | 1 | 0 | Native records/view |
| Term Sheets | records | 1 | 0 | Native records/view |
| LOIs | records | 1 | 0 | Native records/view |
| Due Diligence | records | 1 | 0 | Native records/view |
| Financial Models | records | 1 | 0 | Native records/view |
| Comp Transactions | records | 1 | 0 | Native records/view |
| Working Capital Adj | records | 1 | 0 | Native records/view |
| Integration Plans | integration | 1 | 0 | Provider request records only |
| Regulatory Filings | records | 1 | 0 | Native records/view |
| Escrow Terms | records | 1 | 0 | Native records/view |
| Closing Checklist | records | 1 | 0 | Native records/view |
| Post-Close Reports | records | 1 | 0 | Native records/view |
| AI · Synergy Model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Comp Transaction Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · QofE Memo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Redline Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Integration Plan Draft | integration | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Working Capital True-Up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · VDR Question Router | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Regulatory Approval Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Term Sheet Compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Closing Checklist Gen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · DD Prioritize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Financial Model Sanity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anti-Trust Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Escrow Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Post-Close Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer pipeline | records | 1 | 0 | Native records/view |
| Data requests | records | 1 | 0 | Native records/view |
| Document comparisons | records | 1 | 0 | Native records/view |
| Permission groups | records | 1 | 0 | Native records/view |
| Document comments | records | 1 | 0 | Native records/view |
| Bid rounds | records | 1 | 0 | Native records/view |
| Marketing materials | records | 1 | 0 | Native records/view |
| Approval workflows | records | 1 | 0 | Native records/view |
| Deal milestones | records | 1 | 0 | Native records/view |
| Closing binders | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Buyer engagement score | records | 1 | 0 | Native records/view |
| Document classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Qa copilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Redaction recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deal summary generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk flag extractor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nda matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dcf copilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Term sheet diff explainer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vdr permissions | records | 1 | 0 | Native records/view |
| Vdr viewer | records | 1 | 0 | Native records/view |
| Vdr analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proposals | records | 1 | 0 | Native records/view |
| SOWs | records | 1 | 0 | Native records/view |
| Services | records | 1 | 0 | Native records/view |
| Proposal Templates | records | 1 | 0 | Native records/view |
| Team | records | 1 | 0 | Native records/view |
| AI Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Win/Loss Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timeline Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| multisection sow generation | records | 1 | 0 | Native records/view |
| proposal template library | records | 1 | 0 | Native records/view |
| pricing intelligence | records | 1 | 0 | Native records/view |
| risk allocation | records | 1 | 0 | Native records/view |
| contract clause recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| postsignature tracking | records | 1 | 0 | Native records/view |
| ai sow generation endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai proposalfrombrief generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai clauseterm recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai pricing intelligence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai risk allocation generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| client project or proposal crud | records | 1 | 0 | Native records/view |
| template library or section snippets | records | 1 | 0 | Native records/view |
| pricingratecard management | records | 1 | 0 | Native records/view |
| pdf export route codebase imports pdf lib | records | 1 | 0 | Native records/view |
| esignature workflow | integration | 1 | 0 | Provider request records only |
| changeorder tracking | records | 1 | 0 | Native records/view |
| notifications audit log or rbac | records | 1 | 0 | Native records/view |
| RFP Generation | records | 1 | 0 | Native records/view |
| Bid Comparison Matrix | records | 1 | 0 | Native records/view |
| Should-Cost Modeling | records | 1 | 0 | Native records/view |
| Contract Drafting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Management | records | 1 | 0 | Native records/view |
| Spend Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Savings Tracker | records | 1 | 0 | Native records/view |
| Compliance Tracking | records | 1 | 0 | Native records/view |
| Auction Management | records | 1 | 0 | Native records/view |
| Market Intelligence | records | 1 | 0 | Native records/view |
| Performance Scorecards | records | 1 | 0 | Native records/view |
| Approval Workflow | records | 1 | 0 | Native records/view |
| Category Strategy | records | 1 | 0 | Native records/view |
| Supplier Diversity | records | 1 | 0 | Native records/view |
| Delivery & Quality Risk | records | 1 | 0 | Native records/view |
| Export Data | records | 1 | 0 | Native records/view |
| supplier diversity optimization identifying minority women small suppliers | records | 1 | 0 | Native records/view |
| supply chain resilience mapping identifying single sourced categories | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| invoice anomaly detection for manual review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| marketplace integration for direct sourcing with auto price monitoring | integration | 1 | 0 | Provider request records only |
| contract obligation tracker with alerts for renewals sla | records | 1 | 0 | Native records/view |
| ai driven supplier diversity optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive delivery quality risk model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| invoice anomaly detection ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited integrations only an export module no erp | integration | 1 | 0 | Provider request records only |
| supplier portal for collaborative bidding | records | 1 | 0 | Native records/view |
| invoice matching three way match automation | records | 1 | 0 | Native records/view |
| contract obligation tracking with calendar alerts | records | 1 | 0 | Native records/view |
| webhooks for external system events | integration | 1 | 0 | Provider request records only |
| e signature workflow for contracts | integration | 1 | 0 | Provider request records only |
| Vendor risk performance scorer work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Simulator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tax Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Contract Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skills Matcher | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Financial Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HR Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sales Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| contract clause analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fraud anomaly detector | records | 1 | 0 | Native records/view |
| invoice ocr | records | 1 | 0 | Native records/view |
| multi entity consolidation | records | 1 | 0 | Native records/view |
| approval engine | records | 1 | 0 | Native records/view |
| external accounting sync | records | 1 | 0 | Native records/view |
| mobile self service | records | 1 | 0 | Native records/view |
| field ops app | records | 1 | 0 | Native records/view |
| api gateway | records | 1 | 0 | Native records/view |
| Procurement | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 282 feature pages were visited in the browser; 280 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 169 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

169 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
