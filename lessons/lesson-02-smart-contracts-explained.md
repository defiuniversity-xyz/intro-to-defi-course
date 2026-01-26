---
course: intro-to-defi
module: 1
lesson: 2
title: "Smart Contracts Explained"
description: "How self-executing code enables DeFi without intermediaries"
---

# Smart Contracts Explained
![Header](https://storage.googleapis.com/intro-to-defi-media/images/lesson_02/intro-to-defi_02_header.png)


**Core concept:** Smart contracts are programs that automatically execute actions when specific conditions are met—like if-this-then-that rules for money that no one can change.

---

## If-This-Then-That for Money

You've probably used automation before:

- "If motion detected, turn on lights"
- "If email from boss, send notification"
- "If calendar event in 15 minutes, alert me"

Smart contracts apply this logic to financial transactions:

- "If loan collateral drops below 150%, liquidate position"
- "If user deposits ETH, send them equivalent tokens"
- "If trade request meets conditions, execute swap"

The key difference: these rules are enforced by code on a blockchain that no one—not even the creators—can change after deployment.

---

## How Smart Contracts Work


![Infographic](https://storage.googleapis.com/intro-to-defi-media/images/lesson_02/intro-to-defi_02_infographic.png)
**Writing:** Developers write code defining the contract's rules (in languages like Solidity for Ethereum).

**Deployment:** The code is uploaded to the blockchain, where it gets its own address (like a wallet).

**Interaction:** Users send transactions to the contract's address to trigger its functions.

**Execution:** If conditions are met, the contract executes automatically. No human approves or processes.

**Permanence:** Once deployed, the code generally can't be changed. What's written is what executes.

---

## Why This Changes Everything

Traditional finance requires trust at every step:

**Bank loan:**
- You trust the bank to process fairly
- You trust them to follow their stated terms
- You trust them not to change terms arbitrarily

**Smart contract loan:**
- The terms are code—visible to everyone
- Execution is automatic—no subjective decisions
- No one can change the rules after you agree

You don't trust people or companies. You verify code. The rules are the same for everyone, enforced identically every time.

---

## Real DeFi Smart Contract Examples

**Automated Market Maker (Uniswap):**
"If user sends Token A, calculate Token B amount using formula, send Token B to user."
No matching orders. No counterparty. Math determines the trade.

**Lending Protocol (Aave):**
"If user deposits collateral, allow borrowing up to X%. If collateral value drops below threshold, automatically liquidate."
No loan officers. No credit committees. Code enforces the rules.

**Yield Farming:**
"If user provides liquidity, track contribution, distribute rewards proportionally."
Automatic, transparent, calculable.

---

## Limitations of Smart Contracts

Smart contracts are powerful but limited:

**They can't access external data:**
A smart contract can't check today's weather or stock prices on its own. It only knows what's on the blockchain. "Oracles" bridge this gap by feeding external data to contracts—but oracles are points of trust.

**They can't be easily updated:**
Once deployed, code is generally permanent. Bugs can be devastating. Some contracts have upgrade mechanisms, but these reintroduce trust concerns.

**They only work within their scope:**
A contract can move crypto but can't call your bank or file a lawsuit. Real-world enforcement still requires traditional systems.

**Garbage in, garbage out:**
Perfect code still produces bad results if the data or parameters it works with are bad.

---

## Security Implications

Because smart contracts control real money and can't be easily changed:

**Audits matter:** Before using a protocol, check if the code has been professionally audited.

**Bugs are catastrophic:** Exploited contracts have lost hundreds of millions.

**Testing is extensive:** Good projects test extensively before deploying.

**Simplicity helps:** More complex contracts have more potential vulnerabilities.

When evaluating DeFi protocols, understanding whether they use audited, battle-tested smart contracts is crucial.

---


![Summary](https://storage.googleapis.com/intro-to-defi-media/images/lesson_02/intro-to-defi_02_summary.png)

## Key Takeaways

- **Smart contracts are automated if-then programs** running on blockchain
- **They execute automatically** when conditions are met—no human in the loop
- **Rules are transparent and immutable**—you can verify code before interacting
- **This enables trustless finance**—trust the code, not companies
- **Limitations include**: no external data access, difficult to update, bugs can be catastrophic
- **Security matters enormously**—audits and track record are important

---

## Media Specifications

### Header Image
**Concept:** Visual of "If → Then" flowchart with financial operations (deposit, receive tokens, earn yield)
**Style:** Logic flow diagram meets finance
**Dimensions:** 1200x630px

### Concept Infographic
**Title:** "How Smart Contracts Execute"
**Content:** Flow: User sends transaction → Contract checks conditions → Conditions met? → Execute action → Update blockchain
**Style:** Process flowchart

### Analogy Illustration
**Concept:** If-this-then-that automation (smart home) applied to money
**Style:** Smart home controls → Smart money controls

### Audio Notes
- If-then automation is universally relatable
- Use concrete DeFi examples (Uniswap, Aave)
- Emphasize both power and limitations/risks
- Duration target: 4-5 minutes

### Video Concept
- Animation of smart contract receiving transaction
- Condition checking process
- Automatic execution
- What happens when conditions aren't met
- Duration: 2-3 minutes
