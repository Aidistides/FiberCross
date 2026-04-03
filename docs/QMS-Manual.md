# BigBattery ISO 9001:2015 Quality Management System Manual

**Repository:** `bigbattery/qms` (or internal private repo)  
**File:** `docs/QMS-Manual.md`  
**Version:** Rev 0  
**Issued:** 31 August 2023  
**Approved by:** Marshall Neipert  
**Document Number:** BBI-ES-230801  
**Pages:** 50  
**Status:** Controlled Document – Rev 0 (Initial Release)  

---

## 📋 Document Control

- **Location:** [GitHub Repo](https://github.com/bigbattery/qms/blob/main/docs/QMS-Manual.md)  
- **Original PDF:** `BBI-ISO9001_2015 QMS Manual.pdf` (50 pages)  
- **Scope:** Design, manufacturing, packaging, testing, storage, and distribution of lithium battery systems (LiFePO4 & NMC), chargers, inverters, BMS, solar panels, and TitanGreen forklifts.  
- **Compliance:** ISO 9001:2015 + MIL-PRF-32565  
- **Exclusions:** None taken.  
- **Distribution:** This Markdown version is the live, version-controlled source of truth. Printed copies are uncontrolled.  
- **Proprietary Notice:** © 2023 BigBattery Inc. All Rights Reserved. Unauthorized reproduction prohibited.

**Revision History**

| Rev | Date          | Description          | Author / Approver     |
|-----|---------------|----------------------|-----------------------|
| 0   | 31 Aug 2023   | Initial Release      | Marshall Neipert      |

---

## 📑 Table of Contents

- [Section 00 – QM Index, QMS Forms & Revision Status](#section-00)
- [Section 1 – Scope](#section-1)
- [Section 2 – Normative References](#section-2)
- [Section 3 – Terms & Definitions](#section-3)
- [Section 4 – Context of the Organization](#section-4)
- [Section 5 – Leadership](#section-5)
- [Section 6 – Planning](#section-6)
- [Section 7 – Support](#section-7)
- [Section 8 – Operations](#section-8)
- [Section 9 – Performance Evaluation](#section-9)
- [Section 10 – Improvement](#section-10)

---

## Section 00 – QM Index, QMS Forms, and Revision Status

### Quality System Forms (Complete List)

| Control Number     | Title                                              |
|--------------------|----------------------------------------------------|
| 1-900-0017        | Design Specification Sheet                        |
| 1-900-0018        | Cell Balance Sheet                                |
| 1-900-0019        | Supplier Quality Control Inspection               |
| 1-900-0021        | Testing Data Sheet                                |
| 1-900-0023        | Post Test QC Form                                 |
| 1-900-0027        | RMA Case Inspection Sheet                         |
| 1-901-0001        | Maintenance Work Order                            |
| 1-901-0002        | R&D Work Order                                    |
| 1-901-0003        | Destroy-Do Not Salvage                            |
| 1-901-0007        | Supplier Certification                            |
| 1-901-0008        | HAZMAT Transport Certification                    |
| 1-904-0004        | Customer Property Inventory                       |
| 1-911-0003        | Change Notification                               |
| 1-911-0004        | Product/Component Rejection Report (PCRR)         |
| 1-911-0005        | Supplier Corrective Action Request (SCAR)         |
| 1-911-0006        | Engineering Change Request (ECR)                  |
| 1-911-0008        | Calibration Record Card                           |
| 1-911-0009        | Employee Qualifications                           |
| 1-911-0011        | Supplier Quality Manual                           |
| 1-911-0012        | Production Condition Change Notice                |
| 1-911-0013        | Production Condition Change Check Sheet           |
| 1-911-0028        | Engineering Change Order (ECO)                    |
| 1-911-0032        | Audit Nonconformity Report (QF-86-03-2)           |
| 1-911-0033        | Supplier Quality System Survey                    |
| 1-911-0034        | Corrective Action Request (QF-81-03-1)            |
| 1-911-0039        | Internal Audit Checklist                          |
| 1-911-0040        | Internal Audit Plan (QF-82-02-1)                  |
| 1-911-0064        | Quality Audit of BBI Suppliers                    |
| 1-911-0067        | Responsible Person for Quality Assurance Notice   |
| 1-911-0084        | In-House Calibration Certificate                  |
| 1-913-0004        | Customer Return Disposition Log                   |
| 1-914-0004        | Assembly Output Log                               |
| 1-915-0013        | Training Record                                   |
| 1-511-0069        | Initial Electrical Test Card                      |
| 1-511-0062        | NCP Tag                                           |
| 1-511-0075        | Rework Tag                                        |
| QF-85-02-1        | Customer Complaint                                |

---

## Section 1 – Scope

**1.1 About the BBI Quality Manual**  
Top-tier document covering policies and procedures for manufacturing, packaging, testing, storage, and distribution of products and services.

**1.2 BBI Introduction**  
- Established 2019 as Original Design Manufacturer (ODM).  
- Prismatic LiFePO4 and NMC batteries.  
- China manufacturing partners + Chatsworth, CA HQ/R&D/Distribution.  
- Modular, hot-swapable battery packs.

**1.3 Products & Services**  
12V–72V LiFePO4 batteries, chargers (110/220/480V), inverters, BMS, SPV Solar Panels, TitanGreen lithium forklifts.  
Applications: solar, golf carts, trailers, scissor lifts, food trucks, military, portable power.

**1.4 Exclusions**  
None taken.

---

## Section 2 – Normative References

- ISO 9000:2015, ISO 9001:2015  
- UN3480 / ICAO / IATA Dangerous Goods Regulations  
- ANSI/ISO/ASQ Q9000-2015, ISO 10002:2014, ISO 19011:2018  

---

## Section 3 – Terms & Definitions

Full ISO 9001:2015 glossary (Audit, Nonconformity, Risk, Competence, etc.) plus BBI-specific usage.

### 3.4 List of Abbreviations (37 entries)

| #  | Abbreviation | Expansion                          |
|----|--------------|------------------------------------|
| 1  | AMPS         | Amperage                           |
| 2  | BBI          | BigBattery Inc                     |
| 3  | BIN          | Bin location                       |
| 4  | BMS          | Battery Management System          |
| 5  | CA           | Corrective Action                  |
| ...| ...          | ...                                |
| 19 | NS           | Netsuite                           |
| 20 | NSC          | Netscore                           |
| 28 | RMA          | Return to Manufacturer Authorization |
| 31 | SKU          | Stock keeping unit                 |
| 37 | WMS          | Warehouse Management System        |

*(Full table available in original PDF pages 13–14)*

---

## Section 4 – Context of the Organization

**4.1 Understanding the Organization and Its Context**  
Process identification, sequence, interactions, risk-based thinking (ref: QOP 60-01, QOP 56-01, 1-911-0095 Risk Analysis).

**4.2 Understanding Needs & Expectations of Interested Parties**  
Monitored during Management Review (ref: 1-911-0001).

**4.3 Determining the Scope of the QMS**  
- Level 1: Quality Manual  
- Level 2: QOPs  
- Level 3: Work instructions, drawings, etc.  
- Level 4: Records  
Applies **all** elements of ISO 9001:2015.

---

## Sections 5–10 (Summary – Full Detail in Original PDF)

- **Section 5 – Leadership** (Quality Policy, Org Chart, Roles)  
- **Section 6 – Planning** (Risks, Opportunities, Objectives)  
- **Section 7 – Support** (Resources, Competence, Awareness, Communication)  
- **Section 8 – Operations** (Design, Production, Release, Nonconforming Outputs)  
- **Section 9 – Performance Evaluation** (Monitoring, Internal Audit, Management Review)  
- **Section 10 – Improvement** (Nonconformity, Corrective Action, Continual Improvement)

---

## How to Use This File in GitHub

1. Clone the repo: `git clone https://github.com/bigbattery/qms.git`  
2. All QMS forms are in `/forms/` folder (linked from Section 00).  
3. Update process: Create PR → QA Manager review → Merge → New Rev.  
4. Related files:  
   - `Kits Q.xlsx` → BOM & SKU management  
   - `NetScore WMS Mobile BRD.pdf` → WMS integration  
   - `Repair items needed_.xlsx` → Maintenance tracking  

**Last Updated:** April 03, 2026  
**GitHub Commit Message Example:** `docs: update QMS manual mapping to Rev 0`
