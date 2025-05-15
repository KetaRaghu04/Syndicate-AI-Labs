# Governance – AI Syndicate DAO

The governance of the AI Syndicate Index is powered by a **dual-token, community-first structure** where protocol direction, upgrades, rebalancing, and treasury actions are controlled by $SYN holders.

---

## 🗳️ Governance Principles

- **Decentralized**: Power flows to $SYN holders, not a central team.
- **Transparent**: All proposals, votes, and treasury moves are public.
- **Composable**: Governance logic is modular and integrates with existing DeFi standards.
- **Progressive**: Governance power expands over time as adoption grows.

---

## 🔑 Governance Token: $SYN

$SYN is used to propose, vote, and delegate on:

- Token additions/removals from the index
- Rebalance rules and weight cap changes
- Streaming/performance fee settings
- Automation integrations (e.g., Chainlink Keepers)
- Treasury spending or grant issuance
- Emergency protocol responses

---

## 🧰 Voting System

| Feature              | Implementation              |
|----------------------|-----------------------------|
| Proposal Creation    | Snapshot + DAO multisig     |
| Vote Delegation      | Enabled                     |
| Minimum Quorum       | 2% of $SYN supply (adjustable) |
| Voting Period        | 5–7 days (adjustable)       |
| Proposal Threshold   | 0.2% of $SYN to submit      |
| Execution Layer      | Safe multisig → Timelock (future: full DAO execution) |

> All governance data will be stored transparently on IPFS and indexed by third-party explorers.

---

## 🧪 Proposal Types

1. **Index Management**
   - Add/remove token from ASI Index
   - Modify sector cap (e.g. meme sector limit)
   - Change weight formula or metrics

2. **Protocol Parameters**
   - Adjust rebalancing frequency
   - Update automation providers
   - Enable/disable specific smart contract modules

3. **Treasury & Emissions**
   - Approve funding grants
   - Control streaming or performance fees
   - Burn excess $SYN or $ASI
   - Launch new products or subindexes

---

## 🔄 DAO Evolution Phases

| Phase       | Description                                  |
|-------------|----------------------------------------------|
| **V0**      | Team-led governance, hardcoded parameters    |
| **V1**      | Snapshot voting with delegated DAO multisig  |
| **V2**      | On-chain proposals + time-locked execution   |
| **V3**      | Fully autonomous DAO w/ treasury programs    |

> The community may choose to accelerate the roadmap through governance proposals.

---

## 🧱 Governance Infrastructure

- **Snapshot**: For off-chain voting and delegation
- **Safe**: Gnosis multisig for execution until full DAO handover
- **OpenZeppelin Timelock**: To allow proposal delay + transparency
- **Subgraph Indexing**: For on-chain governance analytics
- **Community Forum**: For proposal drafts, discussion, and upgrades

---

## 🤝 Contributor Roles

| Role          | Responsibility                             |
|---------------|---------------------------------------------|
| Token Holders | Vote on proposals and delegate votes        |
| Delegates     | Represent others' votes with permission     |
| Builders      | Submit protocol improvements or code PRs    |
| Strategists   | Propose rebalances, weights, or token changes |
| Treasury DAO  | Manage protocol funds via multisig          |

All roles are optional and fluid; participation is encouraged but not required.

---

## 🔮 Governance Goals

- Grow active voter base through incentives
- Launch governance-focused dashboards
- Expand $SYN utility across DeFi
- Implement quadratic voting for fair participation
- Launch seasonal “Index Wars” to evolve the token list competitively

---

## 📘 Related Files

| File                      | Purpose                                   |
|---------------------------|-------------------------------------------|
| `docs/tokenomics.md`      | Token supply, utility, and emissions       |
| `contracts/IndexRebalancer.sol` | Executable governance parameter relay |
| `scripts/rebalance.py`    | DAO-approved rebalance execution pipeline |
| `src/models/scoring_model.py` | Backtested weights and change previews |

---

> Governance is the brain of ASI. $SYN is your voice.

