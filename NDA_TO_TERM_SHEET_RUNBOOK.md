![OPTKAS Logo](assets/optkas-logo.png)

---

# NDA-TO-TERM SHEET RUNBOOK
## OPTKAS1 LLC — 7-Step Lender Engagement Playbook

**Date:** February 9, 2026  
**Version:** v2.0 | **Owner:** OPTKAS1 PMO  
**Contact:** jimmy@optkas.com  
**Total Estimated Timeline:** 4–8 weeks NDA → Term Sheet (varies by lender)

---

## OVERVIEW

This runbook defines the **exact sequence of actions** from pre-NDA prep through binding term sheet. Each step specifies what happens, who acts, which data room folders open, which CPs are satisfied, and how you know the step is complete.

**Rule:** Nothing lender-specific goes outside that lender's `10_CORRESPONDENCE/[LENDER]/` folder. This prevents "you told Apollo X but told KKR Y" disasters.

---

## PERMISSION LEVELS

| Level | Name | Folders Visible | When Granted |
|:------|:-----|:---------------|:-------------|
| **A** | NDA Baseline | 01, 02 (limited), 03 (limited), 08, 09 | Step 1 — NDA executed |
| **B** | Diligence | +04, +05, +07 | Step 3 — Diligence kickoff |
| **C** | PII Gated | 06/PII tier only | On specific compliance request |

**Watermark everything** in Folders 04, 06, and 07 (lender name + date stamp).

---

## STEP 0 — PRE-NDA PREP (Internal Only)

*Before any lender contact. No access granted yet.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 0.1 | Create lender silo: `10_CORRESPONDENCE/[LENDER_NAME]/` | Borrower | Before outreach |
| 0.2 | Pre-load silo with empty templates: | Borrower | Same day |
| | — `NDA/` (empty, awaiting lender's form) | | |
| | — `QA_Log/QA_Log.md` | | |
| | — `Meeting_Notes/` | | |
| | — `Email_Summaries/` | | |
| | — `REQUESTS_INTAKE.md` | | |
| 0.3 | Prepare lender-specific cover letter (from Wave 1 package) | Borrower | Before outreach |
| 0.4 | Confirm data room platform ready (Intralinks / Google Drive / OneDrive) | Borrower | Before outreach |

### CPs Addressed: None (internal prep)
### Access Granted: None

---

## STEP 1 — NDA EXECUTED (Limited Release)

*Day 0 — The engagement officially begins.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 1.1 | Receive lender's NDA form (or send borrower template) | Both | Day 0 |
| 1.2 | Review NDA — confirm standard confidentiality provisions | Borrower | Same day |
| 1.3 | Execute NDA — dual signature (Jimmy as Manager) | Borrower | Same day |
| 1.4 | File executed NDA in `10_CORRESPONDENCE/[LENDER]/NDA/NDA_executed.pdf` | Borrower | Same day |
| 1.5 | Grant **Level A** data room access | Borrower | Same day |
| 1.6 | Send welcome email with data room link + verification instructions | Borrower | Same day |
| 1.7 | Start Q&A log: `10_CORRESPONDENCE/[LENDER]/QA_Log/QA_Log.md` | Borrower | Same day |

### Level A Access Granted

| Folder | Contents | Lender Goal |
|:-------|:---------|:------------|
| `01_EXECUTIVE_OVERVIEW/` | Executive Summary, Collateral Summary, Borrowing Base Policy | "Give me the deal in 5 minutes" |
| `02_ENTITY_DOCUMENTS/` (non-PII) | Formation, Operating Agreement, Resolutions | "Is this entity real?" |
| `03_COLLATERAL_DOCUMENTATION/` (limited) | PPM, STC Security List, Issuance Resolution, FedEx scan | "Does the collateral exist?" |
| `08_LENDER_PACKAGE/` | Loan Commitment Package, Credit Committee Brief | "Pre-built IC materials" |
| `09_VERIFICATION/` | Hash manifest, STC contact, CUSIP cross-ref, verification instructions | "Let me verify without asking the borrower" |

**NOT shared yet:** 04 (Insurance details), 05 (Legal templates), 06 (KYC/AML PII), 07 (Financials)

### CPs Satisfied

| CP ID | Item |
|:------|:-----|
| CP-01 | Executive Summary |
| CP-02 | Collateral Summary Sheet |
| CP-03 | Loan Commitment Package |
| CP-05 | Corporate authority (resolutions/attestations) |
| CP-06 | Collateral existence (PPM + Issuance Resolution) |
| CP-09 | Legal Opinion (shared at this stage for credit analysis) |
| CP-11 | Borrowing Base Policy |
| CP-12 | Wave 1 Lender Package |
| CP-13 | NDA (executed) |

### Success Criteria
- ✅ NDA countersigned and filed in lender silo
- ✅ Level A access confirmed (lender viewing data room)
- ✅ Welcome email sent with verification instructions
- ✅ 9 of 13 Phase 1 CPs delivered
- ✅ **Goal achieved: lender understands the deal**

---

## STEP 2 — INITIAL IC PACKET DELIVERED (Lender-Specific)

*Days 1–5 — Empower the analyst to write the memo cleanly.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 2.1 | Monitor data room access logs — confirm lender is reviewing | Borrower | Day 1–2 |
| 2.2 | Share Legal Opinion if not included in Step 1 access | Borrower | Day 1 |
| 2.3 | Deliver lender-specific IC positioning memo | Borrower | Day 2–3 |
| 2.4 | Share insurance confirmation letter (Folder 04, confirmation only) | Borrower | Day 2 |
| 2.5 | Offer introductory call with Jimmy (Manager) | Borrower | Day 3 |

### Additional Access Granted

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `04_INSURANCE/` (confirmation letter only) | Lloyd's Confirmation Letter | Supports IC packet — shows coverage exists |

### CPs Satisfied

| CP ID | Item |
|:------|:-----|
| CP-04 | Entity formation (shared with Good Standing when available) |
| CP-07 | Custody evidence (STC issuer-level list) |
| CP-08 | Insurance evidence (confirmation letter) |

### Success Criteria
- ✅ Lender accessing data room (confirmed via log)
- ✅ IC positioning memo delivered
- ✅ All 13 Phase 1 CPs now delivered or in motion
- ✅ Introductory call offered/scheduled
- ✅ **Goal achieved: analyst can write the credit memo**

---

## STEP 3 — DILIGENCE KICKOFF CALL (45 Minutes)

*Days 5–15 — Structured call with their full team.*

### Call Agenda (you drive)

| Block | Duration | Their Side | Topic |
|:------|:---------|:-----------|:------|
| A | 10 min | Credit MD | Deal ask — size, terms, structure |
| B | 10 min | Outside Counsel | Collateral + custody + legal enforceability |
| C | 10 min | Ops | Custody, settlement, account control |
| D | 10 min | Compliance | KYC, AML, source of funds |
| E | 5 min | All | CP timeline, next steps, doc requests |

*Reference: DILIGENCE_CALL_SIMULATION.md for the top 25 questions and pre-written answers.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 3.1 | Receive and log all diligence questions in Q&A Log | Borrower | Same day as call |
| 3.2 | Triage questions by CP phase and data room folder | Borrower | 1 BD |
| 3.3 | Draft responses using CP Tracker as reference | Borrower | 2–3 BD |
| 3.4 | Grant **Level B** access (diligence phase) | Borrower | Per request |
| 3.5 | Grant **Level C** access (PII) only upon specific compliance request | Borrower | Per request |
| 3.6 | Update meeting notes: `10_CORRESPONDENCE/[LENDER]/Meeting_Notes/` | Borrower | Same day |

### Level B Access Granted

| Folder | Contents | Rationale |
|:-------|:---------|:----------|
| `04_INSURANCE/` (full) | Full policy details, participating insurers | Risk officer review |
| `05_LEGAL/` (templates) | Facility Agreement, Security Agreement, Control Agreement, UCC-1 | Counsel redline prep |
| `07_FINANCIAL/` | BBC template, financial statements, valuation memo | Credit analysis completion |

### Level C Access (PII-Gated, on request only)

| Folder | Contents | Trigger |
|:-------|:---------|:--------|
| `06_COMPLIANCE/` | KYC entity, KYC manager/UBOs, OFAC, SoF, AML, UBO disclosure | Compliance team specific request |

### CPs Satisfied (upon delivery)

| CP ID | Item | Trigger |
|:------|:-----|:--------|
| CP-10 | Compliance pack summary | Upon NDA (Level C request) |
| CP-14 | UBO disclosure | Upon compliance request |
| CP-15 | Full KYC (tiered) | Upon compliance request |
| CP-20 | Q&A log started | Automatic |
| CP-24 | OFAC certification | Upon compliance request |
| CP-25 | AML certification | Upon compliance request |

### Success Criteria
- ✅ Diligence call completed — all blocks covered
- ✅ Q&A Log and Meeting Notes updated in lender silo
- ✅ Level B/C access granted as appropriate
- ✅ All questions responded to within 5 BD
- ✅ **Goal achieved: lender's full team has engaged**

---

## STEP 4 — COLLATERAL VERIFICATION PHASE

*Days 10–20 — "Prove it exists and lender can control it."*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 4.1 | Request holder-specific STC Position Statement (addressed to lender) | Borrower → STC | Day 10 |
| 4.2 | Follow up with STC — confirm production timeline | Borrower | Day 11 |
| 4.3 | Deliver STC Position Statement to lender | Borrower | Day 13–15 |
| 4.4 | Confirm DTC/DWAC eligibility — produce formal letter | Borrower + STC | Day 12 |
| 4.5 | Request coupon payment evidence from STC paying agent | Borrower → STC | Day 10 |
| 4.6 | Produce negative lien officer certificate | Borrower | Day 10 |
| 4.7 | Pre-run UCC search in Wyoming (proactive) | Borrower's Counsel | Day 10 |
| 4.8 | Cooperate with independent valuation if lender requests | Borrower | Per lender |

### CPs Satisfied

| CP ID | Item |
|:------|:-----|
| CP-21 | Holder-specific STC Position Statement |
| CP-22 | Negative lien / no prior pledge confirmation |
| CP-26 | DTC/DWAC Eligibility Confirmation |
| CP-27 | Coupon Payment Evidence |
| CP-28 | Chain of Custody Documentation (already on file) |

### Success Criteria
- ✅ STC Position Statement delivered (lender-addressed)
- ✅ No prior liens confirmed (officer cert + UCC search)
- ✅ DTC/DWAC eligibility confirmed
- ✅ Coupon evidence delivered
- ✅ **Goal achieved: "asset exists and lender can control it"**

---

## STEP 5 — LEGAL PACKAGE DISTRIBUTED

*Days 15–25 — "Counsel begins redlines without getting spooked."*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 5.1 | Open full `05_LEGAL/` to lender's counsel | Borrower | Day 15 |
| 5.2 | Share all template agreements: Facility, Security, Pledge, Control, UCC-1 | Borrower | Day 15 |
| 5.3 | Request full insurance policy schedule from C.J. Coleman | Borrower → Broker | Day 15 |
| 5.4 | Request participating insurers list from C.J. Coleman | Borrower → Broker | Day 15 |
| 5.5 | Prepare facility-specific Manager Resolution | Borrower | Day 16 |
| 5.6 | Prepare facility-specific Incumbency Certificate | Borrower | Day 16 |
| 5.7 | Deliver valuation memo / Broker Opinion of Value | Borrower | Day 15–20 |
| 5.8 | Receive and review lender counsel redlines | Borrower's Counsel | Day 20–25 |
| 5.9 | Negotiate document terms — target agreed form | Both Counsels | Day 20–25 |

### CPs Satisfied

| CP ID | Item |
|:------|:-----|
| CP-16 | Borrower financial summary |
| CP-17 | BBC template + initial BBC |
| CP-18 | Valuation memo / haircut basis (**primary gating item**) |
| CP-23 | Evidence of $3B cost basis funding |
| CP-41 | Full Insurance Policy Schedule |

### Success Criteria
- ✅ Full legal package shared with lender's counsel
- ✅ Insurance schedule received from C.J. Coleman
- ✅ Valuation memo delivered
- ✅ Redlines received and negotiation underway
- ✅ **Goal achieved: counsel redlining without structural concern**

---

## STEP 6 — TERM SHEET ISSUED

*Days 20–35 — The deal takes shape.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 6.1 | Receive indicative term sheet from lender | Lender | Day 20–30 |
| 6.2 | Review term sheet — compare to borrower's proposed terms | Borrower | 2 BD |
| 6.3 | Prepare markup / counter-proposal | Borrower | 2 BD |
| 6.4 | Negotiate key terms — rate, advance rate, tenor, covenants, fees | Both | 3–5 BD |
| 6.5 | Agree final commercial terms | Both | Per negotiation |
| 6.6 | File in silo: `10_CORRESPONDENCE/[LENDER]/Term_Sheet/TERM_SHEET_EXECUTED.pdf` | Borrower | Same day |
| 6.7 | **Freeze** Folders 01, 02, 03, 08, 09 for that lender (versioned snapshot) | Borrower | Same day |
| 6.8 | Update CP Tracker with lender-specific status | Borrower | Same day |

### Key Negotiation Parameters

| Term | Borrower Position | Typical Range | Reference |
|:-----|:------------------|:-------------|:----------|
| Advance Rate | 40% LTV | 35–50% | Borrowing Base Policy (Folder 01) |
| Facility Size | $75M–$300M per institution | Per lender appetite | Executive Summary |
| Interest Rate | SOFR + spread | SOFR + 400–600 bps | Market dependent |
| Tenor | 2–3 years | 1–5 years | Negotiable |
| Covenants | Per Loan Commitment Package | Standard ABL covenants | CP-47 through CP-57 |

### Success Criteria
- ✅ Term sheet received and filed in lender silo
- ✅ Key commercial terms agreed
- ✅ Data room snapshot frozen for this lender
- ✅ **Goal achieved: "interest" → "binding intent"**

---

## STEP 7 — CP TRACKER ACTIVATED (Execution Mode)

*Days 30–45+ — Turn interest into close.*

### Actions

| # | Action | Owner | Timeline |
|:--|:-------|:------|:---------|
| 7.1 | Initialize lender-specific CP Tracker: `10_CORRESPONDENCE/[LENDER]/CP_TRACKER.xlsx` | Borrower | Day 30 |
| 7.2 | Move Phase 2–4 items into lender-specific tracker view | Borrower | Day 30 |
| 7.3 | Produce all Phase 3 documents in final form | Borrower's Counsel | Days 30–40 |
| 7.4 | File UCC-1 in Wyoming | Borrower's Counsel | Day 35 |
| 7.5 | Obtain STC acknowledgment of Control Agreement | Borrower + STC | Days 35–40 |
| 7.6 | Order fresh Good Standing Certificate | Borrower | Day 38 |
| 7.7 | Prepare Officer Certificate (no default, no litigation) | Borrower | Day 39 |
| 7.8 | Prepare Initial Borrowing Base Certificate | Borrower | Day 39 |
| 7.9 | Request insurance certificate naming lender as loss payee | Borrower → C.J. Coleman | Day 35 |
| 7.10 | Exchange wire instructions | Both | Day 40 |
| 7.11 | Receive lender counsel sign-off | Lender | Day 42–45 |
| 7.12 | **Close — funds wired** | Lender | Closing day |

### Phase 3–4 CPs Satisfied at Closing

| CP ID | Item |
|:------|:-----|
| CP-29 | Facility Agreement (executed) |
| CP-30 | Security Agreement (executed) |
| CP-31 | Control Agreement (acknowledged by STC) |
| CP-32 | Pledge Agreement (executed) |
| CP-33 | UCC-1 filed and search-confirmed |
| CP-34 | Insurance endorsements (lender-named) |
| CP-35 | Closing checklist complete |
| CP-36 | Officer Certificate |
| CP-37 | Good Standing Certificate (fresh) |
| CP-38 | Lender Counsel Opinion |
| CP-42 | Executed facility documents |
| CP-43 | Filed UCC-1 (stamped) |
| CP-44 | Funding wire confirmation |
| CP-45 | Custodian control effective |
| CP-46 | Lender counsel sign-off |

### Success Criteria
- ✅ All CP-01 through CP-46 satisfied
- ✅ Facility funded
- ✅ Post-closing covenants (CP-47 through CP-57) monitoring begins
- ✅ Lender silo contains complete closing binder
- ✅ **Goal achieved: FUNDED**

---

## TIMELINE SUMMARY

```
STEP 0    Pre-NDA Prep (internal)
          Create lender silo, load templates, confirm data room
          
Day 0     STEP 1 — NDA Executed → Level A Access
          9/13 Phase 1 CPs delivered immediately
               
Days 1–5  STEP 2 — IC Packet Delivered
          All 13 Phase 1 CPs complete; analyst can write memo
               
Days 5–15 STEP 3 — Diligence Kickoff Call
          Level B/C access; Q&A log active; compliance engaged
               
Days 10–20 STEP 4 — Collateral Verification
           STC position + DTC/DWAC + no liens confirmed
               
Days 15–25 STEP 5 — Legal Package + Valuation
           Counsel redlines; valuation memo delivered
               
Days 20–35 STEP 6 — Term Sheet Issued
           Commercial terms agreed; data room snapshot frozen
               
Days 30–45+ STEP 7 — CP Tracker Activated → Closing → FUNDED
            All CPs satisfied → wire confirmation
```

---

## PARALLEL LENDER MANAGEMENT

### Recommended Sequencing for Wave 1 (14 Lenders)

| Wave | Lenders | NDA Target | Rationale |
|:-----|:--------|:-----------|:----------|
| **1A** (Week 1–2) | Ares, Apollo, KKR, HPS | Days 1–10 | Highest facility targets; set market pricing |
| **1B** (Week 2–3) | Fortress, Stonebriar, Benefit Street, Oaktree | Days 8–18 | Mid-tier; benefit from 1A momentum |
| **1C** (Week 3–4) | Cerberus, BlueMountain, CS Legacy, Deutsche Bank | Days 15–25 | Fills remaining capacity |
| **1D** (Week 4+) | Standard Chartered, Barclays | Days 22+ | Bank-adjacent; longer decision cycle |

### Rules
1. Each lender has its own silo — no leakage between silos
2. Each lender has its own CP Tracker copy in their silo
3. Folders 01–09 are shared (all lenders see same base documents)
4. Folder 10 is strictly siloed (no lender sees another's correspondence)
5. Stagger NDA timing — avoid all lenders at same diligence phase simultaneously
6. Use first 1–2 lenders' feedback to harden process before broader outreach

---

## ESCALATION PROTOCOL

| Situation | Escalation | Timeline |
|:----------|:-----------|:---------|
| Lender non-responsive > 5 BD | Follow-up email + call from Jimmy | Day 5 |
| Lender non-responsive > 10 BD | Escalate to lender's senior contact | Day 10 |
| Diligence question outside scope | Consult K. Knowles or infrastructure partner | 2 BD |
| STC delayed > 5 BD | Direct call to STC Plano TX | Same day |
| C.J. Coleman delayed > 7 BD | Direct call to broker | Same day |
| Term sheet terms unacceptable | Counter-proposal within 3 BD; prepared to walk | 3 BD |
| Legal counsel impasse | Escalate to principals on both sides | Per situation |

---

*This runbook is maintained by OPTKAS1 LLC. Contact jimmy@optkas.com for lender engagement coordination.*
