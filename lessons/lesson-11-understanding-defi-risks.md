# Understanding DeFi Risks

![Header](https://storage.googleapis.com/intro-to-defi-media/images/lesson_11/intro-to-defi_11_header.png)


**Core concept:** DeFi offers unique opportunities but also unique risks that don't exist in traditional finance—understanding them is essential before participating.

---

## New Restaurant vs Chain

Trying a new restaurant is exciting:
- Might discover amazing food
- Might get food poisoning
- Less track record to judge

Chain restaurants are safer:
- Know what to expect
- Health inspections, standards
- Less chance of bad surprise

DeFi protocols are like new restaurants. Exciting, potentially rewarding, but also riskier. Traditional finance is the chain—boring but predictable.

---

## Smart Contract Risk

**The risk:**
All DeFi runs on code. Code can have bugs. Bugs can be exploited. Exploits drain funds.

**Real examples:**
- $600M stolen from Ronin bridge (2022)
- $200M+ from various DeFi hacks annually
- Even audited contracts get exploited

**Mitigation:**
- Use established, battle-tested protocols
- Check for audits (but know audits aren't guarantees)
- Diversify across protocols
- Don't put more than you can afford to lose

---

## Liquidation Risk

**The risk:**
If you borrow in DeFi and your collateral value drops, you can be automatically liquidated—losing your collateral.

**How it happens:**
- You borrow $8,000 against $10,000 collateral
- Collateral drops to $9,000
- Protocol liquidates you (sells collateral to cover debt)
- You might get back $500-1,000, losing $8,000-9,000

**Mitigation:**
- Keep collateral ratio well above minimum
- Monitor positions actively
- Set alerts for price movements
- Don't use maximum borrowing capacity

---

## Impermanent Loss

**The risk:**
Providing liquidity to pools can result in less value than just holding, if token prices diverge significantly.

**How it happens:**
Pool mechanics automatically rebalance your position. When prices move, you end up with more of the less-valuable token.

**Mitigation:**
- Understand IL before providing liquidity
- Use stable pairs for lower IL exposure
- Factor IL into expected returns
- Fees earned should exceed IL for profit

---

## Oracle Manipulation

**The risk:**
DeFi protocols rely on price feeds (oracles). Manipulated prices can cause improper liquidations or exploits.

**How it happens:**
Attacker manipulates price on a smaller exchange that the oracle uses. DeFi protocol acts on false price.

**Mitigation:**
- Use protocols with robust oracle implementations
- Protocols using Chainlink or multiple sources are safer
- Be cautious with protocols using single-source oracles

---

## Rug Pulls and Exit Scams

**The risk:**
Project creators disappear with user funds.

**How it happens:**
- Project collects deposits
- Creators drain funds
- Project abandoned

**Mitigation:**
- Research team thoroughly
- Check for liquidity locks
- Avoid protocols with single points of failure
- Be extremely cautious with new/unaudited protocols

---

## User Error

**The risk:**
You make a mistake. There's no undo button.

**Common mistakes:**
- Sending to wrong address
- Approving malicious contracts
- Not understanding what you're signing
- Losing seed phrase

**Mitigation:**
- Double-check everything
- Use small test transactions
- Understand what you're doing before doing it
- Follow security best practices

---

## Risk Management Framework

**Size positions appropriately:**
Never put more than you can afford to lose in any single protocol.

**Diversify:**
Don't keep everything in one protocol or one chain.

**Stay informed:**
Follow protocol updates, security disclosures, and community discussions.

**Have an exit plan:**
Know how to withdraw quickly if needed.

**Learn continuously:**
DeFi evolves fast. Keep learning.

---


![Summary](https://storage.googleapis.com/intro-to-defi-media/images/lesson_11/intro-to-defi_11_summary.png)

## Key Takeaways

- **DeFi has unique risks** not present in traditional finance
- **Smart contract bugs** can drain funds instantly
- **Liquidation risk** is real with borrowing—monitor positions
- **Impermanent loss** affects liquidity providers
- **Oracle manipulation** can cause improper protocol behavior
- **User error** is unforgiving—no customer support, no undo
- **Risk management** includes sizing, diversification, and continuous learning
