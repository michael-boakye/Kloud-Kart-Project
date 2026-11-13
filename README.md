# Kloud Kart Data Strategy and Governance

This repository contains a business-focused data strategy, risk assessment, decision records, and implementation roadmap for Kloud Kart. The materials are intended to help management improve reporting, protect live operations, and manage customer information responsibly as the business grows.

## Executive overview

Kloud Kart's current reporting and data practices create three related business risks:

- Large reporting exports run against the database that supports the live website and have coincided with website slowdowns.
- Operations and Finance produce different Monday figures, reducing confidence in management reporting.
- Marketing exports customer lists of approximately 300,000 records without a reliable record of where copies are stored or who receives them.

The recommended response is a modest, staged reporting capability rather than a large data platform. Establish a separate reporting copy using the approved second server, test it before moving suitable workloads, agree on shared management-report definitions, and introduce clear ownership and controls for customer information. Stock availability and order-processing decisions should continue to use the live operational system.

## Recommended priorities

1. **Protect live operations.** Move suitable management reporting away from the live website database only after testing the reporting environment and its refresh behaviour.
2. **Build trusted reporting.** Agree on how key figures are defined and approved across Operations and Finance. Start with orders, sales, inventory, fulfilment, and customer activity; daily refreshes are sufficient for most management information.
3. **Strengthen customer-data controls.** Assign responsibility, restrict access, record exports and recipients, track stored copies, and document how customer information requests are handled. These controls should support the company's obligations under Ghana's Data Protection Act, 2012 (Act 843).
4. **Hire in sequence.** Recruit a Data Engineer first to establish and operate the reporting foundation, followed by a Business Intelligence and Reporting Analyst to develop consistent reports and dashboards.
5. **Defer unnecessary complexity.** Revisit a warehouse, continuous management dashboards, or machine-learning forecasting only when reliable reporting and data controls are in place and there is a clear business need.

## 12-month roadmap

| Period | Focus | Expected outcome |
| --- | --- | --- |
| **Quarter 1** | Establish the reporting environment, test its impact, and introduce basic access and export controls. | Suitable reporting runs separately from the live website workload; live stock and order decisions remain on the operational system. |
| **Quarter 2** | Review Operations and Finance reports, agree on definitions, and build the first shared management reports. | Management receives consistent figures from an agreed reporting process. |
| **Quarter 3** | Improve customer-list tracking, access controls, deletion-request handling, and regular reporting. | Exports have identifiable owners and recipients, and actions can be evidenced. |
| **Quarter 4** | Review performance and controls, assess readiness for the Nigeria pilot, and identify justified next investments. | The board can review progress, outstanding risks, and evidence-based priorities for the next year. |

## Repository contents

### Decision records

| Record | Decision |
| --- | --- |
| [ADR-001: Separate management reporting from the live website database](Kloud%20Kart%20decisions/decisions/ADR-001-separate-reporting-environment.md) | Use a separate reporting copy for suitable management workloads, subject to testing. |
| [ADR-002: Protect live stock and order information](Kloud%20Kart%20decisions/decisions/ADR-002-protect-live-stock-and-order-information.md) | Keep live stock and order decisions on the operational system. |
| [ADR-003: Build a modest reporting capability first](Kloud%20Kart%20decisions/decisions/ADR-003-build-a-modest-reporting-capability-first.md) | Address immediate reporting needs without premature platform complexity. |
| [ADR-004: Control customer data exports](Kloud%20Kart%20decisions/decisions/ADR-004-control-customer-data-exports.md) | Establish accountability and controls for exported customer information. |
| [ADR-005: Hire the Data Engineer first](Kloud%20Kart%20decisions/decisions/ADR-005-hire-data-engineer-first.md) | Build and secure the reporting foundation before expanding reporting capability. |

### Analysis and recommendations

| Document | Purpose |
| --- | --- |
| [Data findings and risk assessment](Data%20Findings%20And%20Risk%20Assessment.md) | Summarises the identified business risks, evidence, and areas requiring further validation. |
| [Data strategy recommendation and roadmap](Data%20Strategy%20Recommendation.md) | Sets out the recommended operating approach, hiring sequence, and 12-month plan. |
| [Centralised data governance recommendation](One%20Improvement%20beyond%20the%20brief.md) | Proposes clear data ownership, shared reporting practices, and regular control reviews. |
| [Kloud Kart board presentation](Kloud_Kart_Board_Presentation.pptx) | Presentation version of the recommendations for board discussion. |

## Suggested reading order

1. [Data findings and risk assessment](Data%20Findings%20And%20Risk%20Assessment.md)
2. [Data strategy recommendation and roadmap](Data%20Strategy%20Recommendation.md)
3. The decision records above, for the rationale and consequences of each key choice
4. [Centralised data governance recommendation](One%20Improvement%20beyond%20the%20brief.md)
5. [Kloud Kart board presentation](Kloud_Kart_Board_Presentation.pptx)

## Scope and assumptions

These recommendations are based on the operational information provided for the project. The exact cause and impact of the reported website slowdowns, the reasons for differences between departmental reports, and the full extent of customer-data copies still need to be verified. The assessment distinguishes reported facts from those follow-up checks; implementation should confirm them before finalising controls or investment decisions.

This repository contains strategy and planning documents, not an executable software application. No installation or build step is required.
