# ASI Index Methodology

This document outlines the core methodology behind the **ASI Index**, developed by AI Syndicate Labs. ASI is a fully on-chain crypto index token offering diversified exposure to AI utility protocols and meme assets.

## 🎯 Objective
To provide structured, transparent, and composable exposure to the AI narrative in crypto using a smart-contract-backed, data-driven index token.

## 🧠 Asset Selection Criteria
1. **AI Relevance**
   - Core functionality must involve artificial intelligence, data processing, or AI branding/narrative.
2. **Liquidity Threshold**
   - ≥ $500K daily volume on major CEX or DEX
3. **Market Cap Range**
   - Minimum $20M MC for utility
   - Minimum $5M MC for meme sector
4. **On-Chain Activity**
   - Active contract usage, verified deployment, or staking/liquidity involvement
5. **Community/Sentiment**
   - Measured via social velocity, mentions, and Telegram/X engagement

## 🧮 Index Scoring Model
Each token is scored based on four factors:

| Factor            | Weight |
|-------------------|--------|
| Market Cap        | 30%    |
| Liquidity         | 25%    |
| Narrative Score   | 25%    |
| Inverse Volatility| 20%    |

### Composite Score Formula:
```
Index Score = 0.30*(MCap Score) + 0.25*(Liquidity/10) + 0.25*(Narrative/10) + 0.20*(1/Volatility)
```

## 🔁 Rebalancing Logic
- Frequency: Every 30 days
- Trigger: Manual or automated execution (future DAO governance)
- Method: Set new weights via `setAllocations()` in the smart contract
- Max Weight Cap: 25% per token

## 📤 Data Sources
- CoinGecko/CoinMarketCap APIs for MC + Liquidity
- DEX aggregators for pricing + volume
- Custom scripts for volatility & narrative indexing

## 🛡️ Risk Controls
- Tokens must pass minimum security check (audit, time on-chain)
- Volatility threshold: capped influence from extremely volatile tokens
- Meme tokens limited to 30% of total index exposure

## 📈 Future Additions
- Automated rebalancing via Chainlink Keepers or Gelato
- DAO voting for token inclusion/removal
- Rollout of AI-derived sentiment scoring engine

> The future is indexed — transparently, intelligently, and on-chain.