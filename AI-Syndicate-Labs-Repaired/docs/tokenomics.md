# AI Syndicate Labs – Tokenomics Overview

This document details the dual-token model powering the AI Syndicate ecosystem: **$ASI** (index token) and **$SYN** (governance token).

---

## 🔹 $ASI – AI Syndicate Index Token

### Purpose:
Tracks a dynamic, quant-weighted portfolio of top AI utility and meme tokens. One token = diversified exposure to crypto AI.

### Type:
ERC-20 Index Token (non-governance)

### Utility:
- Represents a share of the underlying AI asset basket
- Tradable on DEXs
- Auto-rebalanced monthly via on-chain logic
- Can be staked for $SYN emissions in future phases

### Supply:
- Initial supply: **1,000,000 ASI** (minted to vault)
- No additional emissions — minted once, backed by underlying assets
- Supply increases only when users deposit liquidity (mint mechanism)

### Backing:
- Composably backed by a smart-contract-managed vault
- Portfolio viewable in `/data/token_metadata.json`

---

## 🔹 $SYN – Syndicate Governance Token

### Purpose:
Governs the ASI Index methodology, DAO treasury, and roadmap decisions.

### Type:
ERC-20 Governance Token

### Utility:
- Propose and vote on:
  - Asset inclusion/exclusion
  - Methodology changes
  - Treasury allocations
  - DAO appointments
- Stake to boost voting weight

### Supply:
- Total max supply: **100,000,000 $SYN**

### Distribution:
| Category            | Allocation | Vesting         |
|---------------------|------------|-----------------|
| Community Airdrop   | 10%        | TGE             |
| Contributor Rewards | 15%        | 1-year linear   |
| DAO Treasury        | 30%        | Unlocked        |
| Index LP Stakers    | 25%        | Emitted over 3y |
| Team & Advisors     | 20%        | 6mo cliff, 2yr vest |


---

## 🔁 Token Interactions
- **$ASI** can be staked to earn **$SYN**
- **$SYN** governs changes to how **$ASI** operates
- **Treasury** (funded by $ASI streaming fees) is controlled by $SYN holders

---

## 💡 Future Utility Expansion
- Integration with DeFi lending and vaults
- Synthetic derivatives on AI sector performance
- AI-driven DAO tooling and sentiment-adjusted governance weights

> $ASI tracks the sector. $SYN governs the system.

---

For token contract addresses and deployment logs, see `/contracts/`.
