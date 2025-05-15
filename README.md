# 🧠 AI Syndicate Index (ASI)

The **AI Syndicate Index (ASI)** is the first fully on-chain, quant-weighted index tracking the performance of AI-centric cryptocurrencies. It algorithmically blends AI utility protocols and memecoins into a single ERC-20 token ($ASI), delivering structured, automated exposure to the Web3 AI economy.

> Think $SPY for crypto-AI — fully composable, data-driven, and community-governed.

---

## 🧬 What It Does

- Tracks a curated basket of AI-related tokens (FET, AGIX, GRT, TURBO, PEPEAI, etc.)
- Scores tokens using a custom quantitative model
- Assigns portfolio weights monthly using normalized on-chain and social data
- Publishes index weights, token scores, and allocations transparently
- Enables future DAO governance via $SYN token

---

## 🧠 Why It Matters

AI narratives dominate Web3, but exposure is fragmented and risky. The ASI Index is:

- **Composable** — one token ($ASI) gives broad AI exposure
- **Transparent** — weights are driven by verifiable data
- **Balanced** — capped allocations and sector constraints
- **DAO-ready** — designed to transition control to $ASI holders

---

## 🧪 Scoring Model

```python
Score = (
  0.30 * market_cap_normalized +
  0.25 * liquidity_score +
  0.25 * narrative_velocity +
  0.20 * inverse_volatility
)
