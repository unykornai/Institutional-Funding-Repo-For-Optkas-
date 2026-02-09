# DATA_ROOM_v1 INDEX
## OPTKAS1 LLC Institutional Funding Package

**Version:** 1.0  
**Generated:** February 2, 2026  
**Status:** FROZEN — Do not modify without version increment  
**Contact:** jimmy@optkas.com

---

## Overview

This data room contains the complete institutional-grade documentation package for the OPTKAS1 secured credit facility backed by TC Advantage 5% Secured Medium Term Notes (CUSIP 87225HAB4).

**Total Documents:** 39  
**Categories:** 7

---

## Folder Structure

### 00_EXEC_SUMMARY (6 files)
Executive-level overviews for credit committee and senior decision-makers.

| File | Description |
|:-----|:------------|
| README.md | Repository overview and navigation |
| EXECUTIVE_SUMMARY.md | 2-page lender overview with deal structure |
| LENDER_EVIDENCE_SUMMARY.md | **NEW** — One-page collateral chain: PPM → Notes → Facility → Custody → Hashes |
| CREDIT_COMMITTEE_POSITIONING.md | Credit committee brief with risk assessment and recommended terms |

---

### 01_TRANSACTION_STRUCTURE (6 files)
Core deal documents defining the credit facility structure.

| File | Description |
|:-----|:------------|
| LOAN_COMMITMENT_PACKAGE-v2.md | **PRIMARY** - Complete lender submission with pre-formatted responses |
| LOAN_COMMITMENT_PACKAGE.md | Original version of lender package |
| STRATEGIC_INFRASTRUCTURE_EXECUTION_AGREEMENT.md | Unykorn 7777 partnership agreement |
| SPONSOR_CONSIDERATION_NOTE.md | **NEW** - Financeable debt instrument for platform delivery consideration |
| ANNEX_A_Tranche_Details.md | Asset identification, CUSIP, valuation methodology |
| ANNEX_B_System_Architecture.md | Technical infrastructure and data flows |

---

### 02_COLLATERAL_AND_CREDIT (7 files)
Collateral documentation and credit analysis.

| File | Description |
|:-----|:------------|
| STC_Statement.pdf | **CRITICAL** - Securities Transfer Corporation position statement |
| TC_Advantage_PPM_Series_B.pdf | **CRITICAL** - TC Advantage Traders Confidential Private Placement Memorandum (Series B) |
| PPM_ANALYSIS.md | **NEW** - PPM cross-reference analysis and verification (11/11 identifiers match) |
| BORROWING_BASE_POLICY.md | Haircut methodology and valuation policy |

---

### 03_BOND_AND_NOTE_ISSUANCE (3 files)
Bond structure and issuance documentation.

| File | Description |
|:-----|:------------|
| optkas1-bond-issuance-guide.md | **CORE** - Bond issuance specifications |
| Bedford_Bond_Workflow_Packet.pdf | Bond workflow reference |
| CAT Bond Rail Blueprint.pdf | CAT bond structure reference |

---

### 04_COMPLIANCE_AND_RISK (3 files)
Regulatory compliance and risk management.

| File | Description |
|:-----|:------------|
| LEGAL_OPINION_TEMPLATE.md | Counsel opinion template |

---

### 05_CHAIN_OF_CUSTODY (4 files)
Verification, audit trails, and custody documentation.

| File | Description |
|:-----|:------------|
| FedEx_Scan_2026-01-22.pdf | Physical delivery chain of custody |
| cryptographic_ATTESTATION_SPEC.md | cryptographic evidence layer technical specification |
| AUDIT_RUNBOOK.md | Daily/monthly/quarterly audit procedures |
| ipfs-config.json | IPFS document storage configuration |

---

### 99_APPENDIX (8 files)
Templates, execution plans, and supplementary materials.

| File | Description |
|:-----|:------------|
| FACILITY_AGREEMENT_TEMPLATE.md | Master credit agreement template |
| SECURITY_AGREEMENT_TEMPLATE.md | Pledge agreement template |
| STC_CONTROL_AGREEMENT_TEMPLATE.md | Transfer agent control agreement template |
| BORROWING_BASE_CERTIFICATE_TEMPLATE.md | Monthly collateral report template |
| day0_snapshot_template.json | Initial snapshot JSON structure |
| OTC-OUTREACH-TEMPLATES.md | Investor/lender outreach templates |
| funding-execution-plan.md | Execution strategy and timeline |
| FUNDING-PLAN-TOMORROW.txt | Short-term funding action items |

---

## Core Document Verification

| Required Document | Status | Location |
|:------------------|:-------|:---------|
| LOAN_COMMITMENT_PACKAGE-v2.md | ✅ Present | 01_TRANSACTION_STRUCTURE/ |
| STRATEGIC_INFRASTRUCTURE_EXECUTION_AGREEMENT.md | ✅ Present | 01_TRANSACTION_STRUCTURE/ |
| STC Statement.pdf | ✅ Present | 02_COLLATERAL_AND_CREDIT/ |
| TC_Advantage_PPM_Series_B.pdf | ✅ Present | 02_COLLATERAL_AND_CREDIT/ |
| optkas1-bond-issuance-guide.md | ✅ Present | 03_BOND_AND_NOTE_ISSUANCE/ |

---

## ⚠️ Missing / Action Required

| Document | Category | Action |
|:---------|:---------|:-------|
| Certificate of Formation | Entity | Obtain from applicable jurisdiction |
| Operating Agreement | Entity | Execute and upload |
| Insurance Policy Document | Compliance | Request from per PPM |
| Executed Legal Opinion | Compliance | Obtain at closing |

---

## Audit Information

- **Hash File:** [HASHES.txt](HASHES.txt) — SHA-256 hashes for all documents
- **Manifest:** [data-room.json](data-room.json) — Machine-readable inventory
- **Attestation Account:** rEYYpZJ7KNqj5dqHExM9VCQWNG6j7j1GLV (cryptographic)

---

## Reading Order by Role

### Credit Fund Analyst
1. 00_EXEC_SUMMARY/EXECUTIVE_SUMMARY.md
2. 01_TRANSACTION_STRUCTURE/LOAN_COMMITMENT_PACKAGE-v2.md
3. 02_COLLATERAL_AND_CREDIT/STC_Statement.pdf
4. 02_COLLATERAL_AND_CREDIT/TC_Advantage_PPM_Series_B.pdf
5. 02_COLLATERAL_AND_CREDIT/BORROWING_BASE_POLICY.md
6. 01_TRANSACTION_STRUCTURE/ANNEX_A_Tranche_Details.md

### Bank Credit Officer
1. 00_EXEC_SUMMARY/EXECUTIVE_SUMMARY.md
2. 01_TRANSACTION_STRUCTURE/LOAN_COMMITMENT_PACKAGE-v2.md
3. 02_COLLATERAL_AND_CREDIT/STC_Statement.pdf
5. 02_COLLATERAL_AND_CREDIT/BORROWING_BASE_POLICY.md
6. 99_APPENDIX/FACILITY_AGREEMENT_TEMPLATE.md

### External Legal Counsel
1. 01_TRANSACTION_STRUCTURE/LOAN_COMMITMENT_PACKAGE-v2.md
2. 01_TRANSACTION_STRUCTURE/ANNEX_A_Tranche_Details.md
3. 99_APPENDIX/SECURITY_AGREEMENT_TEMPLATE.md
4. 99_APPENDIX/STC_CONTROL_AGREEMENT_TEMPLATE.md

### Technical Due Diligence
1. 01_TRANSACTION_STRUCTURE/ANNEX_B_System_Architecture.md
2. 05_CHAIN_OF_CUSTODY/cryptographic_ATTESTATION_SPEC.md
3. 05_CHAIN_OF_CUSTODY/AUDIT_RUNBOOK.md
4. 99_APPENDIX/day0_snapshot_template.json

---

## Version Control

| Version | Date | Changes |
|:--------|:-----|:--------|
| 1.2 | 2026-02-08 | Added TC Advantage PPM (Series B) and PPM_ANALYSIS.md to 02_COLLATERAL_AND_CREDIT |
| 1.1 | 2026-02-07 | Added CREDIT_COMMITTEE_POSITIONING, funding wave attestation infrastructure |
| 1.0 | 2026-02-02 | Initial freeze — 33 documents classified |

**Next Version:** DATA_ROOM_v2 (lender-specific tailoring)

---

*This data room is maintained by OPTKAS1 LLC. For access or questions: jimmy@optkas.com*
