# Search4Satori (S4S) Ecosystem — Master Whitepaper
## Version 6.0 | June 2026 | Mainnet Live
### *"Dirt on hands, stars in eyes."*

---

## Executive Summary

The Search4Satori (S4S) ecosystem is a sovereign, modular financial and technology architecture designed to bridge digital capital with long-term physical regeneration. Operating as a Hub-and-Spoke protocol on Solana, S4S connects five elemental product streams — each generating independent revenue — through a shared token that enforces programmatic value distribution across ecosystem vaults.

**Current Status (June 2026):**
- S4S token: live on Solana mainnet-beta
- Active products: 7 live, 2 in development
- Infrastructure: sovereign compute node, DePIN nodes generating yield
- GitHub: github.com/Satoriinvest (all products versioned)
- Revenue: multiple streams active across Stripe, Solana payments, and data marketplaces

---

## I. Token Architecture

### S4S Token (Confirmed Mainnet)

| Field | Value |
|-------|-------|
| Name | Search4Satori |
| Symbol | S4S |
| Network | Solana Mainnet-Beta |
| Mint | `Dx7RCVwuXKHHmShzua6895Z8RWTiQSi1pabia4DGRB5D` |
| Standard | Token-2022 |
| Transfer Fee | 1% (auto-collected to multisig) |
| Total Supply | 1,000,000,000 S4S |
| Decimals | 9 |
| Governance | Squads Multisig 2-of-4 |
| Multisig | `PddCBK3cEiQkzjHTDtWBxAw6mCP3JNxGrk2GAqpguPj` |
| Logo | arweave.net/0frRgezPejpEudnkRuT8w_uIkrJxfsBMO9iVnoX6Swk |
| Metadata | arweave.net/gmbH48sveQolPvxnuHyL2MvW6puY9_Ms2DbBzLIcVAo |

### Five Vault Distribution

| Vault | Element | Address | Allocation | Purpose |
|-------|---------|---------|-----------|---------|
| Wood | 🌿 Growth | `8fiTjLSXnp7wrowtgqWip6A5ibaJtbW3zGWHeHAfWJD3` | 400M (40%) | Community & Ecosystem |
| Metal | ⚙️ Precision | `ogCuniVGfMcpDUoFW6cAnKit9PymgCF9gJt5W3hvgLi` | 200M (20%) | Sovereign Reserve — vested |
| Earth | 🌍 Stability | `54nrK3Hnhb5RZMWciMBzt6MFF1ciRGJc4qDcHdZ1HaLU` | 150M (15%) | Foundation & Infrastructure |
| Water | 🌊 Flow | `ECgFCuEWcuUJwFxaFEGaoABBhsFZMr7LuACwtKtzRXy3` | 150M (15%) | Liquidity |
| Fire | 🔥 Spark | `9sesX5oJHU8qDU85yByTmRjvk3r6z9t5xAxd2UZMBqLb` | 100M (10%) | Operations & Rewards |

### Metal Vault Vesting Schedule
- Genesis: February 21, 2026
- Cliff: 12 months (no unlock until February 2027)
- Vesting: 48 months linear after cliff (~4,166,667 S4S/month)
- Full vest: February 21, 2031

### Token Liquidity
- Status: PENDING — funded organically via product revenue
- Target: initial Raydium liquidity pool
- Strategy: product revenue funds liquidity, not token sale

---

## II. Hub-and-Spoke Architecture

```
              S4S PROTOCOL HUB
         (Solana mainnet — immutable ledger)
                    │
    ┌───────┬───────┼───────┬───────┐
    ▼       ▼       ▼       ▼       ▼
  WATER   WOOD    FIRE   EARTH  METAL
  FLOW   BUILD   TECH   INVEST   CO
```

Each spoke is architecturally decoupled — sovereign failure isolation ensures no single product failure affects the protocol or other spokes. The S4S token is the connective tissue: every product interaction triggers value flow back through the vault system.

---

## III. Product Suite & Revenue Models

### 🔥 SatoriTECH (Fire Element)

**Harmonic Navigator** | Status: Live
- Personal alignment OS synthesising 6 wisdom traditions: Western Astrology, Gene Keys, Human Design, Ayurveda, Five Elements/TCM, and live planetary transits
- AI engine: Anthropic Claude with deterministic astronomical calculations
- Revenue model: Freemium + Sovereign tier subscription via Stripe
  - Free tier: Daily resonance profile, basic birth chart, Yin-Yang matrix
  - Sovereign tier: Full AI cross-synthesis, Gene Keys Activation Sequence, full Human Design BodyGraph, Data Vault, Echo Chamber, meal/mood tracking
- Data policy: PostgreSQL session data, no third-party sharing
- Solana wallet: on-chain profile hashing (Shadow Drive integration planned)

**SatoriINSIGHTS** | Status: Building
- Crypto tax reconciliation SaaS for NZ IRD compliance, CARF, and global frameworks
- Features: bank CSV ↔ exchange reconciliation, NZD cost basis, ACB pooling for DeFi, residency tracking (183-day/325-day rules), PPOA monitoring
- Revenue model: Subscription SaaS + per-report fee
- Data policy: session-only retention — raw transaction data never stored
- Target markets: NZ retail crypto investors, global CARF-affected users, digital nomads and MNEs

**SatoriREGEN** | Status: Development
- Decentralised incentive framework for enterprise green IT
- Verifies EU Code of Conduct on Data Centre Energy Efficiency compliance
- Issues S4S micro-rewards for verified Carbon Aware Software practices
- Revenue: B2B SaaS licensing + S4S reward distribution

### 🌊 SatoriFLOW (Water Element)

**SatoriFLOW App** | Status: Live
- Marine and environmental data capture platform
- Ocean Protocol integration for data marketplace trading
- Revenue: Data marketplace transaction fees + subscription
- Hardware: AMICA sensor nodes (marine edge compute, planned)

**SatoriHELPR** | Status: Live
- Marine AI navigation, sustainable fishing optimisation, safety alerts
- Revenue: Subscription across professional, recreational, and research sectors

### 🌿 SatoriBUILD (Wood Element)

**Slipstream H&S App** | Status: Live
- Construction and trades health & safety management
- Revenue: B2B SaaS per-site/per-user licensing

### ⚙️ SatoriCO (Metal Element)

**SatoriMEMORIES** | Status: Live
- Physical collectibles marketplace with Arweave provenance minting
- Flow: item sourced → authenticated → sealed → Arweave NFT minted → delivered
- Revenue: Sealing fee distributed across 5 S4S vaults (Wood 40% / Metal 20% / Earth 15% / Water 15% / Fire 10%)
- Payment: Solana (SOL/USDC) + S4S token
- Agentic roadmap: autonomous agents browse marketplaces, flag items, trigger verified human fulfilment

### 🌍 SatoriINVEST (Earth Element)

**Status:** Spec/Early Development
- Conservation land acquisition, food forests, BTC-backed Real World Asset (RWA) vaults
- Tokenised land stewardship with S4S staking mechanics
- Revenue: Conservation credit yield + land appreciation

### SatoriINSUR (Cross-Element Spoke)

**Status:** Business plan complete, development pending
- Proof of Vitality (PoV) insurance model — architecturally decoupled spoke
- Replaces actuarial age-banding with health-verified premiums
- Addresses NZ insurance market failures (significant premium inflation 2024-2025)
- Revenue: Premiums + PoV reward distribution in S4S

### Side Projects
**Job Sorted Pro** (jobsorted.pro) — Trades and services marketplace. Independent revenue stream outside the S4S hub.

---

## IV. Infrastructure

### Sovereign Compute Node
- Local compute: high-performance workstation running Ubuntu 24.04
- Connectivity: Starlink (primary)
- Local AI: Ollama (deepseek-r1:14b, phi4:14b)
- Storage: NAS operational, GDrive mirror/docs
- Permanent storage: Arweave (provenance, token metadata, whitepapers)
- Planned: additional edge nodes (marine deployment)

### DePIN Nodes (Active Yield)
| Node | Type | Status |
|------|------|--------|
| AIOZ | Video CDN | Active |
| Grass | Bandwidth sharing | Active |
| Nexus | ZK proof computation | Active |
| Bitcoin Core | Full node | Active |

### Payment Rails
- Solana: primary on-chain payments (SOL, USDC, S4S)
- Base/EVM: x402 micro-payment rail
- Stripe: fiat subscription billing

### Cognitive Trinity (AI Operations)
| Role | Model | Function |
|------|-------|---------|
| Navigator | Claude (Anthropic) | Strategy, security, audit |
| Architect | Gemini | System DNA, documentation |
| Mechanic | phi4:14b (local) | Automation, scripts |
| Sentinel | deepseek-r1:14b (local) | Research, code review |

---

## V. Revenue Flow Architecture

```
PRODUCT REVENUE
      │
      ├─ Stripe subscriptions → Operating expenses
      │
      ├─ Solana payments → USDC → Yield (Kamino)
      │
      ├─ SatoriMEMORIES sealing fees → 5 vaults (elemental split)
      │
      ├─ DePIN rewards → USDC/JitoSOL → Kamino collateral
      │
      └─ S4S transfer fees (1%) → Multisig → Protocol treasury
```

**Liquidity flywheel:**
1. Product revenue funds S4S liquidity pool (Raydium)
2. Token liquidity enables S4S payments across all products
3. S4S transfer fees accumulate in multisig → fund protocol operations
4. DePIN yield compounds via Kamino → operational capital

---

## VI. ⚠️ Tax & Legal Considerations
### *FOR ADVISOR REVIEW ONLY — NOT LEGAL OR TAX ADVICE*
### *Issues flagged for qualified legal and tax counsel*

### S4S Token Classification
- **Utility token argument:** S4S grants access to ecosystem services, discounts, and governance
- **Payment token argument:** S4S accepted as payment across products
- **Security token risk:** Vesting schedule on Metal vault may be characterised as equity-like in some jurisdictions
- **REVIEW REQUIRED:** Classification determines GST treatment, income vs capital, and whether token issuance is a taxable event

### Transfer Fee (1%) Tax Treatment
- 1% auto-collected on every S4S transfer to Squads multisig
- **Issue:** Each fee collection may be a taxable receipt in the period received
- **Issue:** FMV methodology needed if fees received as S4S tokens
- **REVIEW REQUIRED:** Protocol treasury legal structure — partnership, company, or trust treatment

### Metal Vault Vesting
- 200M S4S vesting over 60 months (12-month cliff)
- **Issue:** Each unlock event may constitute a taxable income event at FMV on unlock date
- **Issue:** Valuation methodology required where no established market price exists
- **REVIEW REQUIRED:** Formal vesting agreement documentation for tax purposes

### SatoriMEMORIES Sealing Fees
- Fees distributed across 5 vaults as S4S tokens
- **Issue:** GST treatment on digital services — jurisdiction of supply matters
- **Issue:** Physical goods component (shipping) vs digital service (Arweave minting) — different treatment
- **REVIEW REQUIRED:** Vault attribution and entity structure

### Stripe Subscription Revenue
- Subscription fees from Harmonic Navigator and SatoriINSIGHTS
- Standard income treatment: assessable in year received
- GST: registration may be required depending on turnover threshold
- Overseas customers: exported services may qualify for zero-rating
- **Generally straightforward SaaS treatment**

### DePIN Node Rewards
- Tokens earned from AIOZ, Grass, Nexus participation
- **Issue:** Income (taxed at FMV when received) vs capital (taxed on disposal)
- General position in most jurisdictions: network rewards are income when received
- **REVIEW REQUIRED:** DePIN classification vs mining vs staking

### Arweave Storage Costs
- AR tokens used for permanent storage
- Generally deductible as business expense at FMV of AR at time of use
- **Issue:** AR token acquisition is a capital event — track cost basis separately

### Ocean Protocol Data Sales
- OCEAN tokens received for data marketplace transactions
- **Issue:** Income recognised at FMV of OCEAN tokens when received
- **Issue:** Data privacy obligations — confirm no personal data in datasets sold

### Global Entity Structure
- Potential offshore entity considered for global operations
- **CRITICAL REVIEW REQUIRED:** Any offshore structure must have genuine commercial substance
- Controlled Foreign Corporation rules may attribute offshore income to NZ resident entity
- Transfer pricing rules apply to any cross-border related-party transactions
- **Do not establish any offshore structure without specialist advice**

---

## VII. Governance

### Sovereign Council
- Structure: Squads 2-of-4 multisig on Solana
- Address: `PddCBK3cEiQkzjHTDtWBxAw6mCP3JNxGrk2GAqpguPj`
- Controls: mint authority, fee configuration, fee withdrawal, metadata updates
- All protocol-level changes require 2 of 4 signatories

### Operational Payment Addresses
| Address | Network | Purpose |
|---------|---------|---------|
| `H6R24JdYnmJZTQFgA5J7N6XD8HXxJQwt1N2hNF2LpZ8g` | Solana | Operational — DePIN swaps, x402 |
| `0xeB424380753Ec763106E2F26A729E60EB1263fF3` | Base/EVM | x402 micro-payment rail |

---

## VIII. Roadmap (Next 90 Days)

| Priority | Item | Element |
|---------|------|---------|
| 1 | SatoriINSIGHTS MVP live | Fire |
| 2 | S4S token liquidity (Raydium pool) | Water |
| 3 | ElizaOS agentic execution layer | Fire |
| 4 | SatoriMEMORIES autonomous agent | Metal |
| 5 | Marine edge node deployment | Water |
| 6 | Agent-maintained web presence | Fire |
| 7 | Local 70b LLM deployment | Fire |
| 8 | SatoriINSUR development start | Metal |

---

## IX. Key Links

| Resource | URL |
|---------|-----|
| Website | search4satori.com |
| GitHub | github.com/Satoriinvest |
| SatoriMEMORIES | asset-manager-satoriinvest.replit.app |
| Job Sorted Pro | jobsorted.pro |
| Token (Solscan) | solscan.io/token/Dx7RCVwuXKHHmShzua6895Z8RWTiQSi1pabia4DGRB5D |

---

*All on-chain addresses verified against Solana mainnet-beta at time of writing.*
*This document does not constitute legal or financial advice. Tax and legal considerations require review by qualified advisors.*

*Search4Satori Ecosystem — Version 6.0 — June 2026*
