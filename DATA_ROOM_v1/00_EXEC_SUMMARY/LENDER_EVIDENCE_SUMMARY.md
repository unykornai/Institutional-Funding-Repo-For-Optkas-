# LENDER EVIDENCE SUMMARY
## Complete Collateral Chain of Custody — One-Page Reference

**OPTKAS1-MAIN SPV | Secured Credit Facility**  
**Prepared:** February 8, 2026  
**Classification:** Confidential — Lender Due Diligence

---

## THE CHAIN: PPM → Notes → Facility → Custody → Hashes

```
┌─────────────────────────────────────────────────────────────────┐
│  1. SOURCE OFFERING                                             │
│  ─────────────────                                              │
│  TC Advantage Traders, Ltd. — Series B PPM (May 29, 2020)       │
│  $5B offering of 5% Secured Medium Term Notes                   │
│  Rule 144A / Reg S exempt | QIB only                            │
│  SHA-256: 5134F730E60CA8965BCE7598D41EFF73ECDC7E60DF7DE26B84F.. │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│  2. THE NOTES                                                   │
│  ────────────                                                   │
│  TC Advantage 5% Secured Medium Term Notes                      │
│  CUSIP (144A): 87225HAB4     ISIN: US87225HAB42                 │
│  CUSIP (Reg S): P9000TAA8    ISIN: BSP9000TAA83                 │
│  Face Value: $10,000,000     Coupon: 5.00% p.a.                 │
│  Maturity: May 31, 2030      Insurance: $25.75M (C.J. Coleman)  │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│  3. CUSTODY & VERIFICATION                                      │
│  ─────────────────────────                                      │
│  Transfer Agent: Securities Transfer Corporation (STC)          │
│  Address: 2901 Dallas Parkway, Suite 380, Plano, TX 75093       │
│  STC Position Statement: ON FILE (dated 2026-01-23)             │
│  SHA-256: CF913B0FA430FBDC742B3A98BB0327C169B0F5BF0FB9508D30B.. │
│  Status: OPTKAS1-MAIN SPV confirmed as holder of record         │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│  4. THE FACILITY                                                │
│  ───────────────                                                │
│  $4,000,000 Secured Credit Facility                             │
│  Borrower: OPTKAS1-MAIN SPV (Wyoming Series LLC)                │
│  Collateral Coverage: 250%+ ($10M backing $4M)                  │
│  Advance Rate: 40% (conservative)                               │
│  Perfection: UCC Article 8/9 + STC Control Agreement            │
│  Enforcement: Traditional — no platform dependency              │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│  5. EXECUTION & DOCUMENTATION                                   │
│  ────────────────────────────                                   │
│  Strategic Infrastructure Agreement: EXECUTED 2026-02-07        │
│  Exhibit A Economic Participation: EXECUTED 2026-02-07          │
│  Signature Page: EXECUTED 2026-02-07 (Option A — 10% NCF)       │
│  Sponsor Consideration Note: EXECUTED 2026-02-07                │
│  Sponsor Note Estoppel: EXECUTED 2026-02-07                     │
│  All 5 agreements signed by both parties.                       │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│  6. INTEGRITY VERIFICATION (SHA-256 HASHES)                     │
│  ──────────────────────────────────────────                     │
│  Infrastructure Agreement: 75F909AFD1DC4584...                  │
│  Exhibit A Economic:       1BB360D17A9C4D29...                  │
│  Signature Page:           CB373863474DCCBA...                  │
│  Sponsor Note:             2284E41B3C4A88D1...                  │
│  Estoppel Certificate:     D3660229EC8DE22B...                  │
│  STC Statement:            CF913B0FA430FBDC...                  │
│  TC Advantage PPM:         5134F730E60CA896...                  │
│                                                                 │
│  XRPL Attestation Account: rEYYpZJ7KNqj5dqHExM9VCQWNG6j7j1GLV │
│  All hashes independently verifiable.                           │
└─────────────────────────────────────────────────────────────────┘
```

---

## DOCUMENT CROSS-REFERENCE TABLE

| Document | Location | Hash (first 16) | Status |
|:---------|:---------|:-----------------|:-------|
| TC Advantage PPM (Series B) | 02_COLLATERAL_AND_CREDIT/ | `5134F730E60CA896` | ✅ On file |
| STC Position Statement | 02_COLLATERAL_AND_CREDIT/ | `CF913B0FA430FBDC` | ✅ On file |
| FedEx Delivery Scan | 05_CHAIN_OF_CUSTODY/ | Verified | ✅ On file |
| Strategic Agreement (executed) | EXECUTION_v1/02_SIGNED/ | `75F909AFD1DC4584` | ✅ Executed |
| Facility Agreement (template) | 99_APPENDIX/ | Complete | ✅ Ready |
| Security Agreement (template) | 99_APPENDIX/ | Complete | ✅ Ready |
| STC Control Agreement (template) | 99_APPENDIX/ | Complete | ✅ Ready |
| Borrowing Base Policy | 02_COLLATERAL_AND_CREDIT/ | Complete | ✅ Ready |
| Executive Summary | 00_EXEC_SUMMARY/ | Complete | ✅ Ready |

---

## IDENTIFIER RECONCILIATION

| Identifier | PPM | STC Statement | Facility Docs | Annex A | Result |
|:-----------|:----|:--------------|:--------------|:--------|:-------|
| CUSIP (144A) | 87225HAB4 | 87225HAB4 | 87225HAB4 | 87225HAB4 | ✅ 4/4 |
| ISIN (144A) | US87225HAB42 | US87225HAB42 | US87225HAB42 | US87225HAB42 | ✅ 4/4 |
| Face Value | $10,000,000 | $10,000,000 | $10,000,000 | $10,000,000 | ✅ 4/4 |
| Maturity | May 31, 2030 | May 31, 2030 | May 31, 2030 | May 31, 2030 | ✅ 4/4 |
| Coupon | 5.00% | 5.00% | 5.00% | 5.00% | ✅ 4/4 |
| Transfer Agent | STC | STC | STC | STC | ✅ 4/4 |

**Reconciliation Result: 24/24 data points match across all source documents.**

---

## WHAT THIS MEANS FOR LENDERS

| Lender Question | Answer | Evidence |
|:----------------|:-------|:---------|
| "Is the collateral real?" | Yes — $10M MTN confirmed by STC position statement | STC_Statement.pdf |
| "Where did these notes come from?" | TC Advantage Traders $5B offering program | TC_Advantage_PPM_Series_B.pdf |
| "Who is the transfer agent?" | STC — SEC-registered, DTC participant | PPM + STC Statement |
| "Is the CUSIP valid?" | Yes — 87225HAB4, cross-verified across 4 documents | Reconciliation table above |
| "What's the coverage?" | 250%+ ($10M collateral / $4M facility) | Borrowing Base Policy |
| "How do I enforce?" | Traditional UCC Article 8/9 + STC Control Agreement | Security Agreement template |
| "Is there insurance?" | Yes — $25.75M C.J. Coleman wrapper | PPM Section 3 |
| "Are the docs executed?" | Yes — 5 agreements signed 2026-02-07, hashed | EXECUTION_v1/02_SIGNED/ |

---

## DATA ROOM ACCESS

**Full institutional data room:** `DATA_ROOM_v1/` (38 documents, 7 categories)  
**Reading order for credit analysts:**
1. `00_EXEC_SUMMARY/EXECUTIVE_SUMMARY.md`
2. `01_TRANSACTION_STRUCTURE/LOAN_COMMITMENT_PACKAGE-v2.md`
3. `02_COLLATERAL_AND_CREDIT/STC_Statement.pdf`
4. `02_COLLATERAL_AND_CREDIT/TC_Advantage_PPM_Series_B.pdf`
5. `02_COLLATERAL_AND_CREDIT/BORROWING_BASE_POLICY.md`
6. `01_TRANSACTION_STRUCTURE/ANNEX_A_Tranche_Details.md`

---

*This summary is a convenience reference for credit officers and due diligence teams. All source documents are independently verifiable in the data room.*
