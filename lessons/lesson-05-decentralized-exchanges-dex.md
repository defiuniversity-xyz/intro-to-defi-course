---
course: intro-to-defi
module: 2
lesson: 5
title: "Decentralized Exchanges (DEX)"
description: "How trading works without a centralized company in the middle"
---

# Decentralized Exchanges (DEX)

![Header](https://storage.googleapis.com/intro-to-defi-media/images/lesson_05/intro-to-defi_05_header.png)


**Core concept:** A DEX (Decentralized Exchange) lets you trade cryptocurrencies directly from your wallet using smart contracts—no accounts, no company holding your funds.

---

## Swap Meet with Smart Rules

Imagine a swap meet where:
- No organizer takes your items to hold
- You bring your stuff, someone else brings theirs
- A robot referee ensures fair trades
- You leave with what you traded for, directly

That's essentially a DEX. The "robot referee" is a smart contract that ensures trades execute fairly according to transparent rules.

Unlike centralized exchanges (Coinbase, Binance) where:
- You deposit funds to their wallet
- They hold your assets
- They match orders on their systems
- You trust them with custody

DEXs work differently:
- You connect your wallet
- Smart contracts execute trades
- Assets move directly between wallets
- No company ever holds your funds

---

## How DEXs Work

Most DEXs use "Automated Market Makers" (AMMs):

**The Liquidity Pool:**
Instead of matching buyers and sellers, DEXs use pools of tokens. A USDC/ETH pool contains both tokens.

**The Swap:**
You send ETH to the pool. The smart contract calculates how much USDC you should receive based on a mathematical formula. You receive USDC directly to your wallet.

**The Price:**
Prices are determined by the ratio of tokens in the pool. If lots of people buy ETH (removing it from pool), ETH becomes scarcer and its price goes up relative to USDC.

**No Order Book:**
Unlike traditional exchanges with lists of buy/sell orders, AMMs have pools and formulas. Anyone can trade at any time as long as there's liquidity.

---

## Popular DEXs

**Uniswap (Ethereum):**
The original and still largest DEX. Pioneered the AMM model.

**SushiSwap (Ethereum + others):**
Fork of Uniswap with additional features.

**Curve (Ethereum):**
Specialized for stablecoin and similar-asset swaps with lower fees.

**Jupiter (Solana):**
Leading DEX aggregator on Solana.

**Raydium (Solana):**
Major AMM on Solana blockchain.

Each blockchain has its own DEX ecosystem. DEX aggregators (like Jupiter, 1inch) find the best prices across multiple DEXs.

---

## Advantages of DEXs

**Self-custody:**
You keep control of your assets until the moment of trade.

**No registration:**
Connect wallet and trade. No accounts, KYC, or approval.

**Access to more tokens:**
DEXs list tokens permissionlessly. New tokens available before centralized exchanges.

**Transparency:**
All trades on-chain. Pool states visible. No hidden operations.

**24/7:**
Trade anytime. No market hours.

---

## Disadvantages of DEXs

**Complexity:**
More complicated than centralized exchange "buy" buttons.

**Gas fees:**
On Ethereum, fees can be significant during busy periods.

**Slippage:**
Large trades in small pools can get worse prices.

**No fiat:**
Can't buy with dollars directly—need to onboard crypto elsewhere first.

**Risk:**
Smart contract bugs, malicious tokens, and user errors have no recourse.

---

## Key DEX Concepts

**Slippage:**
The difference between expected price and actual price. Large trades or thin liquidity causes more slippage. DEXs let you set max slippage tolerance.

**Liquidity:**
How much capital is in trading pools. More liquidity = better prices, less slippage.

**Price impact:**
How much your trade itself moves the price. Large trades have more impact.

**MEV (Maximal Extractable Value):**
Sophisticated actors can manipulate transaction ordering for profit. Various protections exist but it's a consideration.

---


![Summary](https://storage.googleapis.com/intro-to-defi-media/images/lesson_05/intro-to-defi_05_summary.png)

## Key Takeaways

- **DEXs enable direct wallet-to-wallet trading** via smart contracts
- **AMMs use liquidity pools** instead of order books—math determines prices
- **Advantages**: self-custody, no registration, more token access, transparency
- **Disadvantages**: complexity, gas fees, slippage, no fiat support
- **Many DEXs exist** across different blockchains—use ones appropriate to your assets
- **Key concepts to understand**: slippage, liquidity, price impact

---

## Media Specifications

### Header Image
**Concept:** Swap meet with robot referee ensuring fair trades between two parties
**Style:** Futuristic marketplace
**Dimensions:** 1200x630px

### Concept Infographic
**Title:** "How DEX Trading Works"
**Content:** Flow: Your wallet → Connect to DEX → Smart contract calculates trade → Assets swap → Return to your wallet
**Style:** Process flow with wallet icons

### Analogy Illustration
**Concept:** Swap meet with automated fair rules
**Style:** Market scene with visible "rules" displayed

### Audio Notes
- Swap meet analogy grounds the concept
- Explain AMM/pool model simply
- Cover advantages AND disadvantages
- Duration target: 4-5 minutes

### Video Concept
- Animation of pool-based trading
- Show how price changes as pool ratios change
- Compare to centralized exchange process
- Duration: 3 minutes
