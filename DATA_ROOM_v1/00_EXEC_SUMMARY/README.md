# OPTKAS1 Funding System
## Institutional Credit Facility Documentation Package

**Entity:** OPTKAS1-MAIN SPV (Wyoming Series LLC)  
**Contact:** jimmy@optkas.com  
**Last Updated:** February 2, 2026

---

## Overview

This repository contains the complete lender-ready documentation package for the OPTKAS1 secured credit facility backed by TC Advantage 5% Secured Medium Term Notes.

### Collateral Summary

| Parameter | Value |
|:----------|:------|
| **Instrument** | TC Advantage 5% Secured Medium Term Notes |
| **CUSIP (144A)** | 87225HAB4 |
| **ISIN (144A)** | US87225HAB42 |
| **Face Value** | $10,000,000 per bond |
| **Maturity** | May 31, 2030 |
| **Coupon** | 5.00% per annum |
| **Transfer Agent** | Securities Transfer Corporation (STC), Plano TX |
| **Insurance** | C.J. Coleman & Co., $25.75M (2024-2029) |

### Facility Parameters

| Metric | Value |
|:-------|:------|
| **Facility Range** | $2.4M – $15M |
| **Haircut** | 40% (conservative) |
| **Advance Rate** | 20-40% LTV |
| **Coverage Ratio** | 250%+ |
| **Perfection** | UCC-1 + STC Control Agreement |

---

## Repository Structure

```
OPTKAS1-Funding-System/
├── README.md                                    # This file
├── LOAN_COMMITMENT_PACKAGE.md                   # Primary lender submission
├── LOAN_COMMITMENT_PACKAGE-v2.md                # Enhanced version
├── STRATEGIC_INFRASTRUCTURE_EXECUTION_AGREEMENT.md  # Unykorn partnership
│
├── data_room/
│   ├── 01_Entity/                               # Corporate documents
│   ├── 02_Asset/                                # Collateral documents
│   │   ├── STC_Statement.pdf                    # Position verification
│   │   └── FedEx_Scan_2026-01-22.pdf           # Chain of custody
│   ├── 03_Facility/                             # Loan documents
│   ├── 04_Offering/                             # Legal opinions & annexes
│   ├── 05_Compliance/                           # KYC/AML package
│   └── 06_Technical/                            # cryptographic attestation specs
│
├── data_room/templates/                         # Document templates
│   ├── FACILITY_AGREEMENT_TEMPLATE.md
│   ├── SECURITY_AGREEMENT_TEMPLATE.md
│   ├── BORROWING_BASE_CERTIFICATE_TEMPLATE.md
│   ├── STC_CONTROL_AGREEMENT_TEMPLATE.md
│   └── day0_snapshot_template.json
│
└── bond-smart-contracts/                        # Settlement infrastructure
```

---

## Quick Links

### For Lenders
1. [Loan Commitment Package](LOAN_COMMITMENT_PACKAGE-v2.md) - Complete submission
2. [Executive Summary](data_room/04_Offering/EXECUTIVE_SUMMARY.md) - 2-page overview
3. [Borrowing Base Policy](data_room/03_Facility/BORROWING_BASE_POLICY.md) - Haircut methodology

### For Legal Review
1. [Legal Opinion](data_room/04_Offering/LEGAL_OPINION.md) - Ownership & enforceability
2. [Annex A: Tranche Details](data_room/04_Offering/ANNEX_A_Tranche_Details.md)
3. [Annex B: System Architecture](data_room/04_Offering/ANNEX_B_System_Architecture.md)

### For Technical Due Diligence
1. [XRPL Attestation Spec](data_room/06_Technical/XRPL_ATTESTATION_SPEC.md)
2. [Audit Runbook](data_room/06_Technical/AUDIT_RUNBOOK.md)
3. [Day-0 Snapshot Template](data_room/templates/day0_snapshot_template.json)

---

## Verification

All documents in this package can be independently verified:

1. **STC Position** - Contact Securities Transfer Corporation directly
2. **XRPL Attestations** - Query public XRPL ledger (no login required)
3. **Document Hashes** - SHA-256 hashes anchored on-chain

---

## Contact

**OPTKAS1 Management**  
📧 jimmy@optkas.com  
⏱️ Response Time: Same business day

**Data Room Access:** Request via email

---

© 2026 OPTKAS1-MAIN SPV. Confidential — For Institutional Use Only.
