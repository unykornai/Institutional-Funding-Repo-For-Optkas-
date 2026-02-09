![OPTKAS Logo](assets/optkas-logo.png)

---

# NDA-TO-TERM SHEET RUNBOOK
## OPTKAS1 LLC — Lender Engagement Playbook

**Date:** February 9, 2026  
**Version:** 1.0  
**Maintained by:** jimmy@optkas.com  
**Purpose:** Step-by-step choreography from NDA execution through binding term sheet

---

## OVERVIEW

This runbook defines the **exact sequence of actions** from the moment a lender signs an NDA through receipt of a binding term sheet. Each step specifies:

- **What happens** — the deliverable or action
- **Who acts** — borrower, lender, or third party
- **Data room access granted** — which folders open at this step
- **CPs satisfied** — which CP Tracker items are fulfilled
- **Timeline** — expected duration
- **Success criteria** — how you know the step is complete

**Total estimated timeline:** 4–8 weeks from NDA to term sheet (varies by lender).

---

## STEP 1: NDA EXECUTION & DATA ROOM ACCESS
*Day 0 — The engagement begins*

### What Happens
- Lender provides NDA (or accepts borrower's form)
- Borrower executes and returns countersigned NDA
- Data room access provisioned for lender's deal team
- Lender silo created in `10_CORRESPONDENCE/[LENDER_NAME]/`

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 1.1 | Receive lender's NDA form (or send borrower's template) | Both | Day 0 |
| 1.2 | Review NDA terms — confirm standard confidentiality provisions | Borrower | Same day |
| 1.3 | Execute NDA — dual signature (Jimmy as Manager) | Borrower | Same day |
| 1.4 | File executed NDA in `10_CORRESPONDENCE/[LENDER]/NDA_executed.pdf` | Borrower | Same day |
| 1.5 | Create lender silo folder with all subfolders | Borrower | Same day |
| 1.6 | Provision data room access — Folders 01, 02, 03, 04, 08, 09 | Borrower | Same day |
| 1.7 | Send welcome email with data room link + verification instructions | Borrower | Same day |

### Data Room Access Granted at This Step

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `01_EXECUTIVE_OVERVIEW/` | Executive Summary, Collateral Summary, Borrowing Base Policy | "Give me the deal in 5 minutes" |
| `02_ENTITY_DOCUMENTS/` | Formation docs, Operating Agreement | Entity verification |
| `03_COLLATERAL_DOCUMENTATION/` | PPM, STC lists, Issuance Resolution, FedEx scan | Collateral exists and is verifiable |
| `04_INSURANCE/` | Lloyd's confirmation letter | Coverage exists |
| `08_LENDER_PACKAGE/` | Loan Commitment Package, Credit Committee Positioning | Pre-built IC materials |
| `09_VERIFICATION/` | Hash manifest, STC contact info, CUSIP cross-ref, verification instructions | Lender self-verification |

**NOT shared yet:** Folder 05 (Legal templates), Folder 06 (KYC/AML PII), Folder 07 (Financial statements)

### CPs Satisfied
| CP ID | Condition |
|:------|:----------|
| CP-01 | Executive Summary |
| CP-02 | Loan Commitment Package |
| CP-03 | Collateral Summary Sheet |
| CP-05 | STC Security List |
| CP-06 | Lloyd's Insurance Confirmation |
| CP-07 | PPM |
| CP-08 | Issuance Resolution |
| CP-09 | Certificate of Formation |
| CP-10 | Operating Agreement |
| CP-11 | Borrowing Base Policy |
| CP-12 | Wave 1 Lender Package |
| CP-13 | NDA (executed) |

### Success Criteria
- ✅ NDA countersigned and filed
- ✅ Lender silo created in `10_CORRESPONDENCE/`
- ✅ Data room access confirmed (lender can view Folders 01–04, 08, 09)
- ✅ Welcome email sent with verification instructions
- ✅ 12 of 13 Phase 1 CPs delivered

---

## STEP 2: INITIAL CREDIT REVIEW & IC PACKET
*Days 1–5 — Lender's credit team reviews the deal*

### What Happens
- Lender's MD/VP reviews Executive Summary and Collateral Summary
- Credit analyst begins building internal credit memo
- Lender requests K. Knowles Legal Opinion (if not already shared)
- Borrower sends customized IC positioning memo

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 2.1 | Monitor data room access logs — confirm lender is reviewing | Borrower | Day 1–2 |
| 2.2 | Share Legal Opinion (K. Knowles) if not included in initial access | Borrower | Day 1 |
| 2.3 | Prepare lender-specific credit committee positioning brief | Borrower | Day 2 |
| 2.4 | Deliver IC positioning memo to lender's deal team | Borrower | Day 3 |
| 2.5 | Offer introductory call with Jimmy (Manager) — schedule at lender's convenience | Borrower | Day 3 |

### Data Room Access Granted at This Step

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `05_LEGAL/` (partial) | Legal Opinion only (05.01) | Supports credit analysis |

### CPs Satisfied
| CP ID | Condition |
|:------|:----------|
| CP-04 | Legal Opinion (K. Knowles & Co.) |

### Success Criteria
- ✅ Lender accessing data room (confirmed via access log)
- ✅ Legal Opinion delivered
- ✅ IC positioning memo delivered
- ✅ Introductory call offered/scheduled
- ✅ All 13 Phase 1 CPs now delivered

---

## STEP 3: DILIGENCE KICKOFF & Q&A
*Days 5–15 — Lender's diligence team engages*

### What Happens
- Lender sends initial diligence question list (DQL)
- Borrower responds within 5 business days per question
- Q&A log opened in lender silo
- Additional data room folders opened as needed

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 3.1 | Receive and log all diligence questions | Borrower | Day 5–7 |
| 3.2 | Create Q&A Log in `10_CORRESPONDENCE/[LENDER]/QA_Log.md` | Borrower | Same day as DQL |
| 3.3 | Triage questions — sort by CP phase and data room folder | Borrower | 1 BD |
| 3.4 | Draft responses using this Runbook and CP Tracker as reference | Borrower | 2–3 BD |
| 3.5 | Open Folder 06 (Compliance/KYC) upon compliance team request | Borrower | Per request |
| 3.6 | Provide EIN confirmation upon request | Borrower | Same day |
| 3.7 | Schedule diligence call (see DILIGENCE_CALL_SIMULATION.md) | Both | Day 10–15 |

### Data Room Access Granted at This Step

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `06_COMPLIANCE/` | KYC, AML, OFAC, Source of Funds | Compliance team requests during diligence |
| `10_CORRESPONDENCE/[LENDER]/` | Q&A Log, meeting notes | Running record of all lender interactions |

### CPs Satisfied (upon delivery)
| CP ID | Condition | Trigger |
|:------|:----------|:--------|
| CP-18 | Chain of Custody Documentation | Already in Folder 03 |
| CP-23 | EIN / Tax ID Confirmation | Upon lender request |
| CP-24 | KYC Package (Entity) | Upon compliance request |
| CP-25 | KYC Package (Manager/UBOs) | Upon compliance request |
| CP-26 | OFAC / Sanctions Certification | Upon compliance request |
| CP-27 | Source of Funds Statement | Upon compliance request |
| CP-28 | AML Certification | Upon compliance request |

### Success Criteria
- ✅ DQL received and logged
- ✅ Q&A Log created in lender silo
- ✅ All questions responded to within 5 BD
- ✅ KYC/AML package delivered to compliance
- ✅ Diligence call scheduled

---

## STEP 4: COLLATERAL VERIFICATION & STC COORDINATION
*Days 10–20 — The "prove it exists" phase*

### What Happens
- Borrower requests lender-addressed STC Position Statement
- STC produces statement within 3–5 business days
- DTC/DWAC eligibility confirmed
- Lender may request independent valuation (lender selects appraiser)

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 4.1 | Request lender-addressed STC Position Statement | Borrower → STC | Day 10 |
| 4.2 | Follow up with STC — confirm production timeline | Borrower | Day 11 |
| 4.3 | Receive and deliver STC Position Statement to lender | Borrower | Day 13–15 |
| 4.4 | Confirm DTC/DWAC eligibility — produce formal letter | Borrower + STC | Day 12 |
| 4.5 | Request coupon payment evidence from STC paying agent | Borrower → STC | Day 10 |
| 4.6 | Cooperate with independent valuation if lender requests | Borrower | Per lender |
| 4.7 | Pre-run UCC search in Wyoming (proactive) | Borrower's Counsel | Day 10 |

### Data Room Access Granted at This Step
No new folders opened. New documents uploaded to existing folders:

| Document | Uploaded To |
|:---------|:-----------|
| STC Position Statement (lender-addressed) | `03_COLLATERAL_DOCUMENTATION/03.04` |
| DTC/DWAC Eligibility Letter | `03_COLLATERAL_DOCUMENTATION/` |
| Coupon Payment Evidence | `07_FINANCIAL/` |
| UCC Search Results (proactive) | `05_LEGAL/` |

### CPs Satisfied
| CP ID | Condition |
|:------|:----------|
| CP-14 | STC Position Statement (lender-addressed) |
| CP-17 | DTC/DWAC Eligibility Confirmation |
| CP-19 | Coupon Payment Evidence |
| CP-20 | Good Standing Certificate (order fresh) |

### Success Criteria
- ✅ STC Position Statement delivered (lender-addressed)
- ✅ DTC/DWAC eligibility confirmed
- ✅ Coupon payment evidence delivered
- ✅ UCC search clean (no prior liens)
- ✅ Good Standing ordered fresh from Wyoming SOS

---

## STEP 5: LEGAL PACKAGE & COUNSEL ENGAGEMENT
*Days 15–25 — Document negotiation begins*

### What Happens
- Full legal template package shared with lender's counsel
- Lender's counsel reviews and provides redlines
- Insurance policy schedule requested from C.J. Coleman
- Facility-specific Manager Resolution prepared

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 5.1 | Open full Folder 05 (Legal) to lender's counsel | Borrower | Day 15 |
| 5.2 | Share all template agreements (Facility, Security, Pledge, Control, UCC-1) | Borrower | Day 15 |
| 5.3 | Request full insurance policy schedule from C.J. Coleman | Borrower → Broker | Day 15 |
| 5.4 | Request participating insurers list from C.J. Coleman | Borrower → Broker | Day 15 |
| 5.5 | Prepare facility-specific Manager Resolution | Borrower | Day 16 |
| 5.6 | Prepare facility-specific Incumbency Certificate | Borrower | Day 16 |
| 5.7 | Receive and review lender counsel redlines | Borrower's Counsel | Day 20–25 |
| 5.8 | Negotiate document terms — target agreed form | Both Counsels | Day 20–25 |

### Data Room Access Granted at This Step

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `05_LEGAL/` (full) | All templates + UCC-1 form | Document negotiation phase |
| `07_FINANCIAL/` | Financial statements, BBC template | Credit analysis completion |

### CPs Satisfied
| CP ID | Condition |
|:------|:----------|
| CP-21 | Manager Resolution (facility-specific) |
| CP-22 | Incumbency Certificate |
| CP-30 | Full Insurance Policy Schedule |

### Success Criteria
- ✅ Full legal package shared with lender's counsel
- ✅ Insurance policy schedule received from C.J. Coleman
- ✅ Manager Resolution and Incumbency Certificate prepared
- ✅ Redlines received from lender's counsel
- ✅ Document negotiation underway

---

## STEP 6: TERM SHEET NEGOTIATION
*Days 20–35 — The deal takes shape*

### What Happens
- Lender's credit committee issues indicative term sheet
- Borrower reviews and negotiates terms
- Key commercial terms agreed (rate, advance rate, covenants, fees)
- Term sheet filed in lender silo

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 6.1 | Receive indicative term sheet from lender | Lender | Day 20–30 |
| 6.2 | Review term sheet — compare to borrower's proposed terms | Borrower | 2 BD |
| 6.3 | Prepare markup / counter-proposal | Borrower | 2 BD |
| 6.4 | Negotiate key terms — rate, advance rate, tenor, covenants, fees | Both | 3–5 BD |
| 6.5 | Confirm final commercial terms | Both | Per negotiation |
| 6.6 | File term sheet in `10_CORRESPONDENCE/[LENDER]/Term_Sheet.pdf` | Borrower | Same day |
| 6.7 | Update CP Tracker with lender-specific status | Borrower | Same day |

### Key Negotiation Parameters

| Term | Borrower's Position | Typical Range | Reference |
|:-----|:--------------------|:-------------|:----------|
| Advance Rate | 40% LTV | 35–50% | Borrowing Base Policy (Folder 01) |
| Facility Size | $75M–$300M per institution | Per lender appetite | Executive Summary |
| Interest Rate | SOFR + spread | SOFR + 400–600 bps | Market dependent |
| Tenor | 2–3 years | 1–5 years | Negotiable |
| Covenants | Per Loan Commitment Package | Standard ABL covenants | CP-52 through CP-62 |
| Fees | Standard (commitment, arrangement, admin) | Market | Negotiable |

### CPs Satisfied
No new CPs satisfied at this step — this is negotiation. The term sheet itself becomes the basis for Phase 3 CPs.

### Success Criteria
- ✅ Indicative term sheet received
- ✅ Key commercial terms agreed
- ✅ Term sheet filed in lender silo
- ✅ CP Tracker updated with lender-specific dates

---

## STEP 7: CP TRACKER ACTIVATION — PHASES 2–4
*Days 30–45+ — From term sheet to closing*

### What Happens
- Binding term sheet triggers Phase 2–4 CP fulfillment
- All remaining "Staged" and "At Closing" CPs are produced
- Document negotiation concluded in agreed form
- Closing mechanics coordinated

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 7.1 | Activate full CP Tracker for this lender | Borrower | Day 30 |
| 7.2 | Produce all Phase 3 documents in final form | Borrower's Counsel | Days 30–40 |
| 7.3 | File UCC-1 in Wyoming | Borrower's Counsel | Day 35 |
| 7.4 | Obtain STC acknowledgment of Control Agreement | Borrower + STC | Days 35–40 |
| 7.5 | Order fresh Good Standing Certificate | Borrower | Day 38 |
| 7.6 | Prepare Officer Certificate | Borrower | Day 39 |
| 7.7 | Prepare Initial Borrowing Base Certificate | Borrower | Day 39 |
| 7.8 | Request insurance certificate naming lender | Borrower → C.J. Coleman | Day 35 |
| 7.9 | Exchange wire instructions | Both | Day 40 |
| 7.10 | Receive lender counsel sign-off | Lender | Day 42–45 |
| 7.11 | Close — funds wired | Lender | Closing day |

### CPs Satisfied at Closing
| CP ID | Condition |
|:------|:----------|
| CP-15 | UCC Search (by lender's counsel) |
| CP-29 | Lender's Counsel Opinion |
| CP-31 | Supplemental Legal Opinion (if required) |
| CP-32 | Executed Facility Agreement |
| CP-33 | Executed Security Agreement |
| CP-34 | Executed Pledge Agreement |
| CP-35 | Account Control Agreement |
| CP-36 | UCC-1 filed |
| CP-37 | Officer Certificate |
| CP-38 | Signatory Authority Certificate |
| CP-39 | Manager Resolution (final) |
| CP-40 | Good Standing Certificate (fresh) |
| CP-41 | Borrower Financial Statements |
| CP-42 | Initial Borrowing Base Certificate |
| CP-43 | SBLC (if required) |
| CP-44 | Insurance Certificate (lender named) |
| CP-45 | Full Policy Terms + Participating Insurers |
| CP-46 | All Phase 3 in executed final form |
| CP-47 | UCC-1 filed and confirmed |
| CP-48 | Control Agreement acknowledged |
| CP-49 | Wire instructions exchanged |
| CP-50 | Lender counsel sign-off |
| CP-51 | Funds wired |

### Success Criteria
- ✅ All Phase 1–4 CPs satisfied (CP-01 through CP-51)
- ✅ Facility funded
- ✅ Post-closing covenant monitoring begins (CP-52 through CP-62)
- ✅ Lender silo contains complete closing binder

---

## TIMELINE SUMMARY

```
Day 0          NDA Executed → Data Room Access (Folders 01–04, 08, 09)
               12/13 Phase 1 CPs delivered immediately
               
Days 1–5       Credit Review → Legal Opinion shared → IC packet delivered
               All 13 Phase 1 CPs complete
               
Days 5–15      Diligence Kickoff → Q&A Log → KYC/AML delivered
               7+ Phase 2 CPs satisfied
               
Days 10–20     STC Coordination → Position Statement → UCC Search
               4 more Phase 2 CPs satisfied
               
Days 15–25     Legal Package → Counsel Engagement → Insurance Schedule
               3 more Phase 2 CPs satisfied
               
Days 20–35     Term Sheet Negotiation → Commercial Terms Agreed
               Term sheet filed in lender silo
               
Days 30–45+    CP Tracker Phases 2–4 Activated → Closing → Funding
               All remaining CPs satisfied → FUNDED
```

---

## PARALLEL LENDER MANAGEMENT

When engaging multiple lenders simultaneously:

1. **Each lender has its own silo** — `10_CORRESPONDENCE/[LENDER_NAME]/`
2. **Each lender has its own CP Tracker copy** — use lender-specific section of CP_TRACKER.md
3. **Folders 01–09 are shared** — all lenders see same base documents
4. **Folder 10 is siloed** — no lender sees another lender's correspondence
5. **Stagger NDA timing** — avoid all lenders at same diligence phase simultaneously
6. **Track each lender's step** — note which Runbook step each lender is on

### Recommended Sequencing for 14 Wave 1 Lenders

| Wave | Lenders | NDA Target | Rationale |
|:-----|:--------|:-----------|:----------|
| **1A** (Week 1–2) | Ares, Apollo, KKR, HPS | Days 1–10 | Highest facility targets; set market |
| **1B** (Week 2–3) | Fortress, Stonebriar, Benefit Street, Oaktree | Days 8–18 | Mid-tier; benefit from 1A momentum |
| **1C** (Week 3–4) | Cerberus, BlueMountain, CS Legacy, Deutsche Bank | Days 15–25 | Fills remaining capacity |
| **1D** (Week 4+) | Standard Chartered, Barclays | Days 22+ | Bank-adjacent; longer decision cycle |

---

## DOCUMENT TEMPLATES NEEDED

| Template | Status | Used At Step |
|:---------|:-------|:-------------|
| Welcome Email (post-NDA) | 📋 To create | Step 1 |
| IC Positioning Memo (per lender) | ✅ Ready (Wave 1 packages) | Step 2 |
| Q&A Log Template | 📋 To create | Step 3 |
| Diligence Call Prep Sheet | ✅ Ready (DILIGENCE_CALL_SIMULATION.md) | Step 3 |
| Manager Resolution (per facility) | 📋 Staged | Step 5 |
| Officer Certificate | 📋 Staged | Step 7 |
| Borrowing Base Certificate | 📋 Staged | Step 7 |

---

## ESCALATION PROTOCOL

| Situation | Escalation | Timeline |
|:----------|:-----------|:---------|
| Lender non-responsive > 5 BD | Follow-up email + call from Jimmy | Day 5 |
| Lender non-responsive > 10 BD | Escalate to lender's senior contact | Day 10 |
| Diligence question outside scope | Consult K. Knowles or infrastructure partner | 2 BD |
| STC delayed > 5 BD | Direct call to STC Plano TX | Same day |
| C.J. Coleman delayed > 7 BD | Direct call to C.J. Coleman / follow-up broker | Same day |
| Term sheet terms unacceptable | Counter-proposal within 3 BD; prepared to walk | 3 BD |
| Legal counsel impasse | Escalate to principals on both sides | Per situation |

---

*This runbook is maintained by OPTKAS1 LLC. Contact jimmy@optkas.com for lender engagement coordination.*
