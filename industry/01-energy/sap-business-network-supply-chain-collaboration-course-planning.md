# Energy — SAP Business Network Supply Chain Collaboration course planning

**Status:** Recorded for future SCM planning; course placements are provisional.  
**Recorded:** 22 October 2026  
**Sector:** GICS01 Energy only  
**Reference case:** OmniVerse Energy Ltd. — fictional educational enterprise  
**Parent journey:** [Configuring SAP Business Network Supply Chain Collaboration](https://learning.sap.com/learning-journeys/configuring-sap-business-network-supply-chain-collaboration)

[Energy planning home](README.md)

## Decision recorded

Keep supply-chain-focused courses separate from the SAP Ariba Sourcing procurement sprint. Revisit this table when planning the Energy SCM learning pathways. This note records candidate placements; it does not finalize the wider procurement taxonomy, move existing sprints, or publish a completed course.

Use **ACM8 — Supplier Management & Collaboration** as the proposed journey-level home. Assign each course one primary capability home and cross-link other relevant pathways. Retain the complete 14-course journey here for context so dependencies are not lost when individual courses are selected.

All four configuration courses and their functional counterparts are candidates for SCM learning. Procurement can reference transaction-related courses where their objectives overlap; a reference does not require a second maintained course copy.

## Official course inventory and proposed primary homes

SAP's current titles retain both SAP Ariba and SAP Business Network naming. Preserve the official title, SAP code and URL in course records. Suggested homes below are SuccessLabs planning decisions, not SAP classifications.

| # | SAP code | Official course | SAP listed time | Proposed SCM home | Reason for placement |
|---|---|---|---|---|---|
| 1 | ARC130 | [Introducing SAP Business Network Supply Chain Collaboration Core Features and Functions](https://learning.sap.com/courses/introducing-sap-business-network-supply-chain-collaboration-core-features-and-functions) | 21m | ACM8 | Network roles, modules and collaboration architecture |
| 2 | ARC131 | [SAP Business Network Supply Chain Collaboration: Purchase Order Collaboration Features and Functions](https://learning.sap.com/courses/sap-business-network-supply-chain-collaboration-purchase-order-collaboration-features-and-functions) | 2h 40m | ACM8 | PO confirmation, shipping, receiving and invoice collaboration |
| 3 | ARC132 | [SAP Ariba Supply Chain Collaboration: Returns Collaboration Features and Functions](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-returns-collaboration-features-and-functions) | 2h | ACM8 | Buyer-to-supplier returns collaboration |
| 4 | ARC133 | [SAP Ariba Supply Chain Collaboration: Scheduling Agreement Collaboration Features and Functions](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-scheduling-agreement-collaboration-features-and-functions) | 1h 59m | ACM8 | Scheduling agreements and delivery schedules |
| 5 | ARC134 | [SAP Business Network Supply Chain Collaboration: Consignment Collaboration Features and Functions](https://learning.sap.com/courses/sap-business-network-supply-chain-collaboration-consignment-collaboration-features-and-functions) | 1h 24m | AIN6 | Inventory ownership, consumption and settlement |
| 6 | ARC135 | [SAP Business Network Supply Chain Collaboration: Subcontracting & Multi-tier Collaboration](https://learning.sap.com/courses/sap-business-network-supply-chain-collaboration-subcontracting-multi-tier-collaboration) | 1h 49m | ACM8 | Component and manufacturing-partner collaboration |
| 7 | ARC136 | [SAP Business Network Supply Chain Collaboration: Stock Transport Order Collaboration](https://learning.sap.com/courses/sap-business-network-supply-chain-collaboration-stock-transport-order-collaboration) | 4h 21m | ACM8 | OEM and contract manufacturer stock-movement collaboration |
| 8 | ARC141 | [SAP Ariba Supply Chain Collaboration: Planning Features and Functions](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-planning-features-and-functions) | 48m | APN3 | Supplier planning collaboration |
| 9 | ARC142 | [SAP Ariba Supply Chain Collaboration: Quality Features and Functions](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-quality-features-and-functions) | 2h 55m | AQC7 | Quality notifications, inspections and reviews |
| 10 | ARC143 | [SAP Ariba Supply Chain Collaboration: Inventory Features and Functions](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-inventory-features-and-functions) | 1h 44m | AIN6 | Supplier-managed inventory and replenishment |
| 11 | ARC240 | [SAP Ariba Supply Chain Collaboration: Core Configuration and Administration](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-core-configuration-and-administration) | 4h 24m | ACM8 | Common and core-module configuration |
| 12 | ARC241 | [SAP Ariba Supply Chain Collaboration: Planning Configuration and Administration](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-planning-configuration-and-administration) | 1h 10m | APN3 | Planning configuration, rules, BAdIs and reporting |
| 13 | ARC242 | [SAP Ariba Supply Chain Collaboration: Quality Configuration and Administration](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-quality-configuration-and-administration) | 1h 57m | AQC7 | Quality collaboration configuration |
| 14 | ARC243 | [SAP Ariba Supply Chain Collaboration: Inventory Configuration and Administration](https://learning.sap.com/courses/sap-ariba-supply-chain-collaboration-inventory-configuration-and-administration) | 1h 22m | AIN6 | SMI configuration and supplier-specific rules |

The listed course durations sum to **28h 54m**: functional courses **20h 01m** and configuration courses **8h 53m**. These are content estimates, not implementation effort or demonstrated proficiency. Do not compress the full journey into a claimed 20-hour completion.

## Capability homes and cross-references

| SCM stream | Courses proposed here | Cross-references to revisit |
|---|---|---|
| [ACM8 — Supplier Management & Collaboration](../../streams/ACM8-supplier-collaboration-excellence.md) | ARC130–133, ARC135–136, ARC240; journey overview | Procurement execution and Business Network navigation; AMP4 manufacturing for subcontracting; ADL5 logistics for movement and returns |
| [APN3 — Supply Planning & S&OP](../../streams/APN3-integrated-supply-planning.md) | ARC141, ARC241 | ACM8 supplier collaboration and relevant planning prerequisites |
| [AIN6 — Inventory Management & Optimization](../../streams/AIN6-resilient-inventory-management.md) | ARC134, ARC143, ARC243 | ACM8 and procurement; distinguish consignment ownership from SMI replenishment responsibility |
| [AQC7 — Quality Management & Compliance](../../streams/AQC7-quality-compliance-excellence.md) | ARC142, ARC242 | ACM8 and procurement supplier-quality requirements |
| AIG2 — Supply Chain Integration & Enterprise Architecture | Shared integration evidence arising from the selected courses; no duplicate ownership of all 14 courses | Managed gateway prerequisites, document routing, identifiers, reconciliation and failure recovery |

**Placement refinement:** ARC134 is provisionally assigned to AIN6 because inventory ownership and consumption/settlement are central; cross-link it from ACM8 and retain its place in the ARC240 prerequisite sequence. This is a refinement of the earlier broad core-course grouping, pending SCM planning review.

## Prerequisites and sequencing

| Configuration course | SAP stated prerequisites |
|---|---|
| ARC240 | ARC130, ARC131, ARC132, ARC133, ARC134, ARC135, ARC136 |
| ARC241 | ARC141 |
| ARC242 | ARC142 |
| ARC243 | ARC143 |

The functional course pages list no prerequisites. Our recommendation is to understand the business process before configuring it. ARC240 is not listed as a prerequisite on ARC241–243; a recommendation to study shared setup first must not be presented as an SAP requirement.

## Proposed Energy experiments — revisit before building

These are new illustrative exercises, not canonical OmniVerse incidents or confirmed deployed solutions.

| SAP code | Candidate Energy exercise |
|---|---|
| ARC130 | Define buyer/supplier responsibilities and the Energy collaboration scope. |
| ARC131 | Trace one critical-spares order and its exceptions. |
| ARC132 | Return damaged or incorrectly specified equipment and reconcile credit. |
| ARC133 | Explore recurring material deliveries against an agreed horizon. |
| ARC134 | Explore supplier-owned maintenance stock and consumption-based settlement. |
| ARC135 | Explore components supplied to an external equipment manufacturer; not contractor staffing. |
| ARC136 | Validate whether an OEM/CM equipment-supply scenario fits before adopting it. |
| ARC141 | Share future material requirements and review supplier responses. |
| ARC142 | Explore inspection evidence and supplier resolution of nonconforming equipment. |
| ARC143 | Explore min/max replenishment of suitable operating materials. |
| ARC240 | Prepare a configuration decision log and an end-to-end verification scenario. |
| ARC241 | Configure and verify a planning exchange in an authorized practice environment. |
| ARC242 | Design configuration and test evidence for inspection/notification/review flows. |
| ARC243 | Design replenishment rules and exception tests for selected materials. |

## Review when Energy SCM planning resumes

- Confirm each course's current title, URL, duration and prerequisites against SAP Learning.
- Confirm the business capability, process scope, target learner and single primary home.
- Review procurement/SCM boundaries without moving the existing Ariba Sourcing files as part of this note.
- Map selected courses to SuccessLabs levels based on evidence; SAP Beginner/Intermediate labels do not directly establish the six-level progression.
- Define prerequisites, practice-system access, configuration scope and integration dependencies.
- Select Energy materials and scenarios with operations, engineering and safety input; a commercial award or network transaction does not authorize hazardous work.
- Define evidence: requirements, data ownership, application responsibilities, configuration decisions, access controls, end-to-end tests and reconciliation.
- Preserve canonical enterprise facts from the [OmniVerse case](https://github.com/nbnayak88/successlabs-case-studies/tree/main/01-energy/omniverse-energy-ltd); label new assumptions and outcomes explicitly.
- Apply TOGAF, BIZBOK, BABOK, DAMA-DMBOK, relevant ISO/IEC standards and COBIT as useful reference frameworks, without asserting formal compliance.
- Agree the final learning homes before any later migration or consolidation.

## Source and publication boundaries

Source: the official SAP journey and its 14 linked course records, reviewed 22 October 2026. Official material remains on SAP Learning; this file stores links, metadata and original planning analysis. No full SAP course content is reproduced.

This is an Energy-only planning note. It does not establish a working integration, a completed implementation, certification readiness, or a scheduled reminder.

## Explore together

Curious how supplier collaboration supports reliable energy operations? [Join a SuccessLabs Academy webinar](https://hub.successlabsacademy.com/web/checkout/694af8798dd872a219700dd3).
