# STRATEGIC INFRASTRUCTURE & EXECUTION AGREEMENT

**Document Status:** ![Execution Ready](https://img.shields.io/badge/Status-EXECUTION%20READY-success) ![Version](https://img.shields.io/badge/Version-1.0-blue)

---

This Strategic Infrastructure & Execution Agreement (this **"Agreement"**) is entered into as of **January 26, 2026** (the **"Effective Date"**), by and between:

**Unykorn 7777, Inc.**, a technology corporation (**"Unykorn"**), and

**OPTKAS1 LLC**, a OPTKAS1 LLC (**"SPV"**).  
**Contact:** jimmy@optkas.com

Unykorn and SPV may be referred to individually as a **"Party"** and collectively as the **"Parties."**

---

## 1. PURPOSE AND ROLE

### 1.1 Engagement

SPV hereby engages Unykorn as its **RWA Infrastructure & Cryptographic Systems Partner** in connection with the structuring, documentation architecture, verification systems, documentation, audit-readiness, and execution support of the financing and collateral program associated with the TC Advantage Traders 5% Secured Medium Term Notes and related credit facilities (the **"Transaction"**).

### 1.2 Nature of Services

Unykorn specializes in **Real World Asset (RWA) infrastructure**, **cryptographic verification and settlement systems**, and **institutional-grade documentation frameworks**. Unykorn's role includes:

- RWA structuring and documentation architecture
- Cryptographic-based chain-of-custody and attestation systems
- Settlement mechanism design for automated distribution
- Lender-grade documentation and audit-trail infrastructure
- Verification frameworks and evidence preservation

Unykorn is not acting as:

- a broker-dealer,
- an investment adviser,
- a placement agent,
- a lender, or
- a fiduciary to investors or lenders.

---

## 2. SCOPE OF CONTRIBUTIONS

Unykorn has materially contributed and shall continue to contribute, as applicable:

| Contribution Area | Description | Status |
|:------------------|:------------|:------:|
| **RWA Structuring** | Asset classification, collateral mapping, documentation architecture | ✅ Complete |
| **Cryptographic Infrastructure** | cryptographic integration, attestation design, cryptographic verification | ✅ Complete |
| **Collateral Documentation** | Structuring and reconciliation of identifiers, STC verification | ✅ Complete |
| **Borrowing Base Framework** | Development of haircut methodologies and advance rates | ✅ Complete |
| **Lender Documentation** | Preparation of credit-committee-ready submission package | ✅ Complete |
| **Chain of Custody** | Cryptographic-based verification architecture and evidence frameworks | ✅ Complete |
| **Snapshot & Reporting** | Day-0 baseline, cryptographic attestation, immutable audit trails | ✅ Complete |
| **Settlement Mechanism Settlement** | Design and implementation of automated payment rails | ⏳ Ongoing |
| **Funding Coordination** | Support through funding and stabilization phases | ⏳ Ongoing |:-------|:--------|
| **Primary (Digital)** | cryptographic Address: `[Settlement Account]` |
| **Fallback (Wire/ACH)** | Per wire instructions furnished by Unykorn in writing |

SPV agrees that payment to the above-designated address(es) constitutes full discharge of the payment obligation. In the event Unykorn assigns its rights pursuant to Section 9.4, the assignee may furnish updated payment instructions, and SPV shall direct payments accordingly.

---

## SIGNATURES

IN WITNESS WHEREOF, the Parties have executed this Agreement as of the Effective Date.

> **EXECUTION INSTRUCTIONS:**
> 1. Select Option A or Option B in Exhibit A (check one box)
> 2. Initial the selected option
> 3. Sign and date below
> 4. Return executed copy to counterparty
> 5. SHA-256 hash will be computed and anchored to cryptographic post-execution

---

**UNYKORN 7777, INC.**

| | |
|:--|:--|
| By: | /s/ Kevan |
| Name: | Kevan |
| Title: | CEO / Authorized Signatory |
| Date: | February 7, 2026 |

---

**OPTKAS1 LLC**

| | |
|:--|:--|
| By: | /s/ Jimmy |
| Name: | Jimmy (Manager) |
| Title: | Manager |
| Date: | February 7, 2026 |

---

# EXHIBIT A

## ECONOMIC PARTICIPATION SCHEDULE

### Selected Participation Structure

☐ **Option A: Net Cash Flow Participation (Recommended)** ← _Initial here if selected: _______

| Component | Value |
|:----------|:------|
| Participation Rate | 10% of Net Distributable Cash Flows |
| Waterfall Position | After senior debt service, before residual sponsor distributions |
| Payment Frequency | Concurrent with each distribution event |
| Settlement Method | Smart contract + direct wire fallback |

☐ **Option B: Hybrid Success Fee + Participation** ← _Initial here if selected: _______

| Component | Value |
|:----------|:------|
| Success Fee | 2% of funded facility amount (payable at initial close) |
| Ongoing Participation | 4% of Net Distributable Cash Flows |
| Payment Frequency | Success fee at close; participation concurrent with distributions |
| Settlement Method | Smart contract + direct wire fallback |

---

### Definitions

**"Net Distributable Cash Flows"** means all cash receipts attributable to the Transaction, less:
- Senior debt service (principal, interest, fees)
- Operating expenses approved by the SPV manager
- Mandatory reserves

**"Transaction"** means the TC Advantage Secured Notes financing program and all related credit facilities, including any refinancing, extension, or replacement thereof.

---

### Election

The Parties hereby elect:

☐ Option A — 10% Net Cash Flow Participation

☐ Option B — 2% Success Fee + 4% Ongoing Participation

**Initialed by Unykorn:** _______

**Initialed by SPV:** _______

---

# EXHIBIT B

## SETTLEMENT MECHANISM SETTLEMENT SPECIFICATION

### Purpose

This specification governs the automated settlement mechanism implementing the economic terms of this Agreement.

### Technical Parameters

| Parameter | Value |
|:----------|:------|
| Network | cryptographic (primary) / alternative settlement (alternative) |
| Trigger Mechanism | SPV Manager dual authorization authorization (dual) |
| Distribution Logic | Fixed percentage of inflow (10% or 4% per election) |
| Recipient Address | `[Settlement Account]` |
| Explorer | [View Account](https://livenet.verification portal/accounts/[Settlement Account]) |
| Fallback | Wire transfer within 5 business days |

### Settlement Mechanism Functions

```
Function: distributeParticipation()
├─ Input: grossAmount (total distributable)
├─ Calculation: unykornsShare = grossAmount × participationRate
├─ Output: Transfer unykornsShare to designatedRecipient
└─ Emit: DistributionEvent(timestamp, amount, recipient)
```

### Audit Trail

All settlement mechanism executions shall be logged with:
- Timestamp
- Block/ledger reference
- Amount distributed
- Transaction hash

### Amendment Process

Changes to settlement addresses or percentages require:
- Written amendment to this Agreement
- dual dual authorization authorization
- 5-day notice period

---

**Document Hash (SHA-256):** _To be computed at execution_

**cryptographic Attestation TX:** _To be anchored post-execution_

---

*This document is confidential and intended for the named parties only.*
