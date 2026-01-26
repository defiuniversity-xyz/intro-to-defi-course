---
course: intro-to-defi
module: 2
lesson: 6
title: "Lending and Borrowing"
description: "How DeFi enables loans without banks or credit checks"
---

# Lending and Borrowing
![Header](https://storage.googleapis.com/intro-to-defi-media/images/lesson_06/intro-to-defi_06_header.png)


**Core concept:** DeFi lending protocols let you earn interest by lending crypto or borrow crypto by posting collateral—no credit checks, no applications, instant execution.

---

## Pawn Shop with Code

Think about how a pawn shop works:
- You bring valuable items (collateral)
- They give you cash (loan)
- You pay interest over time
- Pay back the loan + interest, get your items back
- Don't pay back? They keep your items

DeFi lending works similarly:
- You deposit crypto (collateral)
- Smart contract lets you borrow other crypto
- You pay interest over time
- Repay loan + interest, get collateral back
- If collateral value drops too much? Automatic liquidation

The "pawn shop" is a smart contract. No negotiation. No credit check. Just math.

---

## How DeFi Lending Works


![Infographic](https://storage.googleapis.com/intro-to-defi-media/images/lesson_06/intro-to-defi_06_infographic.png)
**For Lenders (Depositors):**
1. You deposit crypto into a lending protocol
2. Your deposit joins a lending pool
3. Borrowers pay interest on what they borrow
4. You earn a portion of that interest
5. Withdraw your deposit + earned interest anytime

**For Borrowers:**
1. You deposit collateral (usually more than you borrow)
2. Protocol lets you borrow up to a certain percentage of collateral value
3. You pay interest on borrowed amount
4. Repay anytime to get collateral back
5. If collateral value drops, you might get liquidated

---

## The Overcollateralization Requirement

Unlike traditional loans (where you might borrow $250,000 for a $300,000 house), DeFi requires more collateral than what you borrow:

**Example:**
- You want to borrow $1,000 USDC
- Protocol requires 150% collateralization
- You must deposit $1,500 worth of ETH
- If ETH price drops and your collateral falls to $1,200, liquidation may occur

Why so much collateral? Because:
- No credit checks to assess risk
- No legal system to chase you for repayment
- Smart contracts can't send debt collectors

Overcollateralization is how DeFi manages risk without knowing who you are.

---

## Why Would You Borrow?

If you need to deposit more than you borrow, why borrow at all?

**Keep asset exposure:**
You want to hold ETH but need cash. Instead of selling, you borrow against it. If ETH goes up, you still benefit.

**Tax efficiency:**
In some jurisdictions, borrowing against assets isn't a taxable event, but selling is.

**Leverage:**
Advanced users borrow to increase their position. (High risk—not for beginners!)

**Access different assets:**
Your wealth is in ETH but you need stablecoins for something.

---

## Popular Lending Protocols

**Aave:**
Multi-chain lending protocol. Supports many assets. Variable and stable rates.

**Compound:**
Pioneer in DeFi lending. Primarily on Ethereum.

**MakerDAO:**
Create DAI stablecoin by depositing collateral. Unique model.

**Morpho:**
Peer-to-peer layer on top of Aave/Compound for better rates.

Each has different rates, supported assets, and risk profiles.

---

## Risks of DeFi Lending

**Liquidation risk:**
If collateral value drops, you can lose it. Market volatility is real.

**Smart contract risk:**
Bugs in lending protocol code could result in lost funds.

**Interest rate volatility:**
Rates can change rapidly based on supply/demand.

**Oracle risk:**
Protocols rely on price feeds (oracles). Faulty prices can cause improper liquidations.

**Opportunity cost:**
Funds locked as collateral can't be used for other purposes.

---


![Summary](https://storage.googleapis.com/intro-to-defi-media/images/lesson_06/intro-to-defi_06_summary.png)

## Key Takeaways

- **DeFi lending lets you earn interest** by depositing crypto into lending pools
- **Borrowing requires overcollateralization**—deposit more value than you borrow
- **No credit checks or applications**—smart contracts enforce rules automatically
- **Liquidation is automatic** if collateral value drops below threshold
- **Use cases include** maintaining exposure, tax efficiency, and accessing different assets
- **Significant risks exist**—liquidation, smart contract bugs, and rate volatility

---

## Media Specifications

### Header Image
**Concept:** Pawn shop counter where transaction is handled by robot/code instead of person
**Style:** Traditional meets automated
**Dimensions:** 1200x630px

### Concept Infographic
**Title:** "DeFi Lending Flow"
**Content:** Two parallel flows: Lender (deposit → earn interest) and Borrower (deposit collateral → borrow → repay or liquidation)
**Style:** Dual pathway diagram

### Analogy Illustration
**Concept:** Pawn shop with visible rules—"150% collateral required"
**Style:** Clear, transparent pawn transaction

### Audio Notes
- Pawn shop analogy is universally understood
- Explain overcollateralization clearly
- Cover liquidation risk seriously
- Duration target: 4-5 minutes

### Video Concept
- Animation of lend/borrow cycle
- Show what happens during liquidation
- Interest rate mechanics
- Duration: 3 minutes
