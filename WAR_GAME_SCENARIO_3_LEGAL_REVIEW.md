# OUTSIDE COUNSEL REVIEW — CONFIDENTIAL / ATTORNEY WORK PRODUCT

## PRIVILEGED LEGAL REVIEW: OPTKAS1 LLC SECURED CREDIT FACILITY

**Prepared for:** [Credit Fund Name] — Credit Committee  
**Prepared by:** Outside Counsel  
**Date:** February 9, 2026  
**Scope:** Lender-facing documents only — legal risk and ambiguity review  
**Standard:** Identify language requiring redline, qualification, side letter, or re-papering

---

## REVIEW METHODOLOGY

We have reviewed the following lender-facing documents provided by OPTKAS1 LLC in connection with the proposed secured credit facility:

1. Loan Commitment Package (pre-formatted lender response)
2. Collateral Summary Sheet
3. Executive Summary (LENDER_SUBMISSION_PACKAGE)
4. Legal Opinion — K. Knowles & Co. (January 13, 2026)
5. Certificate of Formation
6. Operating Agreement
7. Signer Attestations
8. Wave 1 Lender Package (Apollo Global — sample)

This review does not constitute a legal opinion. It identifies language that is technically true but legally imprecise, statements requiring qualification, and clauses that could force re-papering or side letters.

---

## 🔴 CRITICAL FINDING — DOCUMENT INCONSISTENCY

### Finding C-1: EXECUTIVE SUMMARY (LENDER_SUBMISSION_PACKAGE) CONTRADICTS ENTIRE STACK

**Severity: CRITICAL — Must be resolved before ANY lender outreach.**

The Executive Summary located at `LENDER_SUBMISSION_PACKAGE/EXECUTIVE_SUMMARY.md` describes a fundamentally different transaction from what is presented in the Loan Commitment Package, Collateral Summary, and Wave 1 packages:

| Parameter | Executive Summary States | All Other Docs State |
|:----------|:------------------------|:---------------------|
| Facility Amount | $4,000,000 | $75,000,000 – $300,000,000 |
| Business Description | "Digital asset custody and settlement infrastructure" | SPV holding MTN collateral |
| Market Opportunity | "$150B+ institutional custody market" | Not applicable (this is a secured lending transaction) |
| Technical Infrastructure | "XRPL blockchain settlement rails" / "Smart Contract Settlement" | DTC/DWAC FAST system |
| Revenue Sources | Custody fees, settlement fees, technology licensing | Coupon income + facility refinancing |
| Collateral Reference | "XRPL blockchain settlement rails" as collateral | TC Advantage MTN (CUSIP 87225HAB4) |
| Collateral Value | "$10,000,000+" | $5,000,000,000 |
| Coverage Metrics | "$10M collateral / $4M facility" | "$5B / $2B max" |
| Interest Rate | "8-12% APR" | "Per lender term sheet" |

**Legal Risk:** If a lender receives BOTH this Executive Summary and the Loan Commitment Package, counsel will immediately flag material inconsistency. This creates a credibility risk that could terminate diligence. At minimum it would require an explanation, and more likely would trigger re-papering of all borrower representations.

**Required Action:** This document must be either (a) completely rewritten to match the core document stack, or (b) withdrawn from the lender-facing package entirely. It should NOT be sent to any lender in its current form.

---

## 🟡 FINDINGS REQUIRING QUALIFICATION AT CLOSING

### Finding Q-1: Residual Placeholder Fields in Loan Commitment Package

**Location:** LOAN_COMMITMENT_PACKAGE_POPULATED.md, Section 1.1

The following fields remain as placeholders in a document marked "Pre-Filled":

- `Manager/Signatory: [Authorized manager]`
- `Tax ID / EIN: [On file]`

**Legal Risk:** Low — these are standard closing deliverables. However, a document titled "Pre-Filled" should not contain unfilled brackets. Lender's counsel will note the inconsistency between the document's stated purpose and its completion state.

**Recommendation:** Fill with "Jimmy, Manager" and "Available upon NDA execution" respectively. Do not leave brackets in a document described as pre-formatted.

---

### Finding Q-2: Insurance "Wrap" Characterization vs. Actual Coverage

**Location:** Collateral Summary Sheet (PPM Security Clause quotation); Loan Commitment Package Section 2.2

The PPM states: *"The Offered TC ADVANTAGE 5% SECURED MEDIUM TERM NOTE will be fully secured by an insurance wrap along with underlying properties."*

The Lloyd's confirmation letter shows: **$625,000,000 sum insured** against a **$5,000,000,000 program.**

**Legal Risk:** Moderate. The word "fully" in the PPM implies complete coverage. The actual insurance represents 12.5% of face value. In a credit agreement, a lender will likely require a representation that "insurance coverage is as described in [specific document]" rather than incorporating the PPM language by reference. If the PPM's "fully secured" language is incorporated into borrower representations, it could create a technical misrepresentation if the $625M is the total coverage.

**Recommendation:** In the credit agreement, reference the Lloyd's confirmation letter specifically (sum insured: $625M) rather than incorporating the PPM's "fully secured by an insurance wrap" language. The borrower should represent the insurance as "$625M insured amount per Lloyd's confirmation" — not as "fully insured." This avoids any ambiguity at closing.

---

### Finding Q-3: Legal Opinion Jurisdiction Gap

**Location:** Legal Opinion — K. Knowles & Co.

K. Knowles & Co. is Bahamas counsel. The opinion addresses:
- Issuer standing (Bahamas law) ✓ Appropriate
- Note validity (Securities Act) — Bahamas counsel opining on US securities law
- SPV authority (Wyoming LLC Act) — Bahamas counsel opining on Wyoming law
- UCC perfection (Wyoming UCC Articles 8 and 9) — Bahamas counsel opining on Wyoming law

**Legal Risk:** Moderate. While the opinion is competent and well-structured, lender's counsel will note that a Bahamas firm is opining on Wyoming UCC and US securities law matters. This does not invalidate the opinion, but standard practice requires:

1. A US-qualified counsel opinion on Wyoming UCC perfection and enforceability
2. Bahamas counsel opinion limited to Issuer matters and Bahamas law

**Recommendation:** This is a "clarify at closing" item, not a structural deficiency. The borrower's materials already acknowledge this implicitly by referencing counsel. Lender should engage its own counsel for US law matters (which is standard regardless). No re-papering required.

---

### Finding Q-4: "DTC-Eligible" vs. Actual DTC Holding

**Location:** Multiple documents reference "DTC/DWAC FAST system" settlement

The documents describe settlement via DTC/DWAC FAST, and STC is listed as transfer agent. However, the materials do not explicitly confirm whether the notes are currently held at DTC or are merely DTC-eligible.

**Legal Risk:** Low. STC participation in the FAST system strongly implies DTC eligibility. However, the credit agreement should include a representation that the collateral is "DTC-eligible and book-entry transferable via the FAST system" rather than assuming current DTC deposit.

**Recommendation:** Clarify at closing. Add specific representation in Security Agreement.

---

### Finding Q-5: Advance Rate vs. Legal Opinion Range

**Location:** Loan Commitment Package Section 2.3; Legal Opinion

The Loan Commitment Package proposes a 40% advance rate. The Legal Opinion states discounted LTV limits of "10–30% of face" are "commercially reasonable and legally unobjectionable."

**Legal Risk:** Low. The 40% advance rate exceeds the upper bound of the range cited in the legal opinion (30%). This does not create a legal deficiency — the opinion endorses the lower range as "unobjectionable," not as a cap — but lender's counsel will note the discrepancy.

**Recommendation:** In the credit agreement, size the advance rate independently of the legal opinion range. If the legal opinion is cited as support for the advance rate, acknowledge that 40% exceeds the opinion's cited range but remains within the borrowing base formula approved by credit. Alternatively, obtain a supplemental opinion letter confirming 40% is acceptable.

---

### Finding Q-6: Signatory C Attestation Incomplete

**Location:** Signer Attestations — K. Knowles & Co. section

The document shows Signatory C (K. Knowles & Co.) as "DESIGNATED" with "Attestation: To be completed upon engagement formalization at facility closing."

**Legal Risk:** Low. This is an expected CP item for deal counsel. The dual authorization protocol is documented and the threshold table is clear. However, the completion checklist shows this as the only unchecked item, which is appropriate.

**Recommendation:** No action required before outreach. Complete at closing.

---

### Finding Q-7: SBLC Section Contains Aspirational Language

**Location:** Loan Commitment Package Section 3.1

The SBLC section describes characteristics including "Irrevocable, unconditional, freely transferable, cash-backed" and "Issued by Top 100 World Bank." The issuing bank field states "[To be designated by Borrower]."

**Legal Risk:** Low. This section is clearly conditional ("If required by lender"). However, stating that the SBLC "will be" cash-backed and from a Top 100 bank creates a forward-looking representation. If the borrower cannot deliver such an instrument, this becomes a failed CP rather than a misrepresentation — but lender's counsel may seek to convert this into a binding obligation.

**Recommendation:** Reframe as "Borrower proposes" or "Subject to availability" rather than "Borrower confirms SBLC will be." This prevents the pre-commitment document from being construed as a binding representation.

---

## 🟢 ITEMS THAT ARE LEGALLY CLEAN

The following items were reviewed and require no qualification, redline, or re-papering:

| Item | Assessment |
|:-----|:-----------|
| Certificate of Formation | Clean. Formation date, file number, registered agent, entity type are consistent and verifiable. |
| Operating Agreement structure | Clean. Manager authority, series designation, purpose clause are standard Wyoming LLC provisions. |
| Signer Attestations (Signatories A and B) | Clean. Corporate authorization language is standard. Dual authorization protocol is well-documented. |
| Wave 1 Lender Packages (Apollo sample) | Clean. No crypto/digital asset language. Figures consistent with core documents. Lender-specific positioning is appropriate. |
| Collateral Summary Sheet | Clean. Internally consistent with Loan Commitment Package. All figures traceable to cited sources. |
| Loan Commitment Package (substantive content) | Clean. Pre-formatted responses are comprehensive and source-cited. Borrower representations are appropriately qualified. |
| Covenant structure | Clean. Affirmative and negative covenants are standard for secured lending. Coverage ratio triggers are clearly defined. |
| Enforcement path | Clean. UCC foreclosure, Control Agreement, and court remedies are conventional secured creditor rights. |
| Data room organization | Clean. Materials are well-organized and indexed. |

---

## SUMMARY — PASS / FAIL ASSESSMENT

| Category | Result | Detail |
|:---------|:-------|:-------|
| Structural redlines | **NONE** | No document requires fundamental restructuring (other than C-1 below) |
| Re-papering required | **ONE DOCUMENT** | Executive Summary (LENDER_SUBMISSION_PACKAGE) — must be rewritten or withdrawn |
| Side letters required | **NONE** | All issues addressable within standard credit agreement negotiation |
| Closing qualifications | **6 items** (Q-1 through Q-6) | All standard "clarify at closing" — none block term sheet issuance |
| Aspirational language | **1 item** (Q-7) | SBLC section — minor reframe recommended |

### OVERALL VERDICT

**PASS — with one critical pre-condition.**

The lender-facing document stack is legally sound for term sheet issuance, **provided the LENDER_SUBMISSION_PACKAGE Executive Summary is either rewritten or excluded from any materials sent to lenders.** All other findings are "clarify at closing" items that would be resolved in normal credit agreement negotiation. No side letters or structural re-papering required.

The documentation quality is above average for a borrower at the pre-commitment stage. Source citations, verification pathways, and covenant structures are well-developed. Counsel would not block on the basis of document quality.

---

**Outside Counsel Review — Privileged and Confidential**  
**Date:** February 9, 2026

