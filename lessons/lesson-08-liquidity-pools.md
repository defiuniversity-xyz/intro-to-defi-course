---
course: intro-to-defi
module: 2
lesson: 8
title: "Liquidity Pools"
description: "How shared token pools enable decentralized trading"
---

# Liquidity Pools
![Header](https://storage.googleapis.com/intro-to-defi-media/images/lesson_08/intro-to-defi_08_header.png)


**Core concept:** Liquidity pools are shared pots of tokens that enable trading on DEXs—anyone can contribute to the pot and earn fees from trades.

---

## Community Potluck

Imagine a community potluck:
- Everyone brings a dish (contributes)
- Everyone can take from any dish (trade)
- The more food, the better the selection
- Contributors help everyone else eat

Liquidity pools work similarly:
- Users contribute tokens (provide liquidity)
- Traders swap using the pooled tokens
- Larger pools mean better trades (less slippage)
- Liquidity providers earn fees for their contribution

The "potluck" keeps trading possible without needing individual counterparties.

---

## How Pools Work

A typical liquidity pool contains two tokens in a pair:

**Example: ETH/USDC pool**
- Pool holds $1,000,000 of ETH
- Pool holds $1,000,000 of USDC
- Total value: $2,000,000 in liquidity

**When someone trades:**
They send ETH to the pool and receive USDC (or vice versa). The pool's ratio changes. A mathematical formula (like x*y=k for simple AMMs) determines how much they receive.

**The result:**
No order matching needed. Trades execute instantly against the pool. Pool ratios adjust automatically.

---

## Becoming a Liquidity Provider

Anyone can add liquidity:

1. **Prepare tokens:** You need both tokens in the pair (e.g., ETH and USDC)
2. **Add to pool:** Deposit equal value of both tokens
3. **Receive LP tokens:** You get tokens representing your share of the pool
4. **Earn fees:** Trading fees accumulate to your share
5. **Withdraw anytime:** Return LP tokens to get your share back

If the pool earns 0.3% on every trade and does $10M daily volume, that's $30,000/day in fees distributed to liquidity providers.

---

## Impermanent Loss: The Hidden Risk

**The problem:**
When token prices change, liquidity providers can end up with less value than if they'd just held the tokens.

**Simple example:**
- You deposit 1 ETH + $2,000 USDC (ETH = $2,000)
- ETH price doubles to $4,000
- Pool mechanics mean you now have roughly 0.7 ETH + $2,800 USDC
- Value: ~$5,600

But if you'd just held:
- 1 ETH = $4,000 + $2,000 USDC = $6,000

You "lost" $400 by providing liquidity instead of holding.

**Why "impermanent"?**
If prices return to original levels, the loss disappears. It only becomes permanent if you withdraw while prices have diverged.

**The trade-off:**
Fees earned might exceed impermanent loss, making it worthwhile. Or they might not. Depends on trading volume, fee rates, and price movements.

---

## Pool Selection Factors

When considering providing liquidity:

**Trading volume:**
Higher volume = more fees. Check historical volume data.

**Fee tier:**
Some pools have higher fees (0.3% vs 0.05%). Higher fees mean more per trade but might have less volume.

**Token volatility:**
Stable pairs (USDC/USDT) have minimal impermanent loss. Volatile pairs have more.

**Incentives:**
Some pools offer extra token rewards. Factor this into total returns.

**Protocol reputation:**
Established protocols with audited contracts are safer.

---

## Liquidity for the Ecosystem

Liquidity providers serve a crucial role:

- They make trading possible
- More liquidity = better prices for traders
- They get compensated via fees
- The system depends on them

Understanding this relationship helps you see why DeFi protocols work to attract liquidity and why "liquidity mining" incentives exist.

---


![Summary](https://storage.googleapis.com/intro-to-defi-media/images/lesson_08/intro-to-defi_08_summary.png)

## Key Takeaways

- **Liquidity pools are shared token reserves** enabling DEX trading
- **Anyone can provide liquidity** and earn a share of trading fees
- **Impermanent loss occurs** when token prices diverge—a real risk for volatile pairs
- **Pool selection involves** volume, fees, volatility, and incentives
- **More liquidity benefits everyone**—better prices, less slippage
- **Understand risks before providing**—impermanent loss can exceed fees earned

---

## Media Specifications

### Header Image
**Concept:** Community potluck table with many dishes, people contributing and taking
**Style:** Communal resource sharing visual
**Dimensions:** 1200x630px

### Concept Infographic
**Title:** "How Liquidity Pools Work"
**Content:** Pool diagram showing: contributions from many → pooled tokens → traders swap → fees distributed back
**Style:** Circular flow with pool in center

### Analogy Illustration
**Concept:** Potluck contribution and consumption
**Style:** Friendly community scene

### Audio Notes
- Potluck analogy makes pools intuitive
- Explain impermanent loss with concrete numbers
- Emphasize it's not "free money"
- Duration target: 4-5 minutes

### Video Concept
- Animation of pool filling with liquidity
- Show swap happening and fees distributing
- Impermanent loss scenario visualized
- Duration: 3 minutes
