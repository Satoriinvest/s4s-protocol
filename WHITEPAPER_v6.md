# Search4Satori (S4S) Ecosystem — Master Whitepaper
## Version 6.0 | June 2026 | Mainnet Live
### *"Dirt on hands, stars in eyes."*

---

## Executive Summary

The Search4Satori (S4S) ecosystem is a sovereign, modular financial and technology architecture designed to bridge digital capital with long-term physical regeneration. Operating as a Hub-and-Spoke protocol on Solana, S4S connects five elemental product streams — each generating independent revenue — through a shared token that enforces programmatic value distribution across ecosystem vaults.

**Current Status (June 2026):**
- S4S token: live on Solana mainnet-beta
- Active products: 7 live, 2 in development
- Infrastructure: sovereign local compute (Waihi, NZ), DePIN nodes generating yield
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
| Metal | ⚙️ Precision | `ogCuniVGfMcpDUoFW6cAnKit9PymgCF9gJt5W3hvgLi` | 200M (20%) | Founder — vested |
| Earth | 🌍 Stability | `54nrK3Hnhb5RZMWciMBzt6MFF1ciRGJc4qDcHdZ1HaLU` | 150M (15%) | Foundation & Infrastructure |
| Water | 🌊 Flow | `ECgFCuEWcuUJwFxaFEGaoABBhsFZMr7LuACwtKtzRXy3` | 150M (15%) | Liquidity |
| Fire | 🔥 Spark | `9sesX5oJHU8qDU85yByTmRjvk3r6z9t5xAxd2UZMBqLb` | 100M (10%) | Operations & Rewards |

### Metal Vault Vesting (Founder)
- Genesis: February 21, 2026
- Cliff: 12 months (no unlock until February 2027)
- Vesting: 48 months linear after cliff (~4,166,667 S4S/month)
- Full vest: February 21, 2031

### Token Liquidity
- Status: PENDING — to be funded organically via product revenue
- Target: ~$500-1,000 USD equivalent in SOL for initial Raydium pool
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

Each spoke is architecturally decoupled — sovereign failure isolation ensures no single product failure affects the protocol or other spokes.

---

## III. Product Suite & Revenue Models

### 🔥 SatoriTECH (Fire Element)

**Harmonic Navigator** | Status: Live
- Personal alignment OS synthesising 6 wisdom traditions: Western Astrology, Gene Keys, Human Design, Ayurveda, Five Elements/TCM, and live planetary transits
- AI engine: Anthropic Claude (deterministic astronomical calculations via astronomy-engine)
- Revenue model: Freemium + "Sovereign" tier subscription via Stripe
  - Free: Daily profile, basic birth chart, Yin-Yang matrix
  - Sovereign: Full AI cross-synthesis, Gene Keys Activation Sequence, full Human Design BodyGraph, Data Vault, Echo Chamber, meal/mood tracking
- Database: PostgreSQL (Drizzle ORM), session data only — no third-party sharing
- Wallet: Solana wallet connection for on-chain profile hashing (Shadow Drive integration planned)

**SatoriINSIGHTS** | Status: Building (Replit)
- Crypto tax reconciliation SaaS for NZ IRD compliance, CARF, and global frameworks
- Key features: bank CSV ↔ exchange reconciliation, NZD cost basis, ACB pooling for DeFi, residency tracking (183-day/325-day rules), PPOA monitoring
- Revenue model: Subscription SaaS + per-report fee
- Data policy: session-only retention — raw transaction data never stored
- Target markets: Tier 1 (NZ retail crypto investors), Tier 2 (global/US 1099-DA gap), Tier 3 (digital nomads, MNEs, Pillar Two)

**SatoriREGEN** | Status: Spec/Development
- Decentralised incentive framework for enterprise green IT
- Verifies EU Code of Conduct on Data Centre Energy Efficiency compliance
- Issues S4S micro-rewards for verified Carbon Aware Software practices
- Revenue: B2B SaaS licensing + S4S reward distribution fees

### 🌊 SatoriFLOW (Water Element)

**SatoriFLOW App** | Status: Live
- Marine and environmental data capture platform
- Integrates with Ocean Protocol for data marketplace trading
- Revenue: Data marketplace transaction fees + subscription
- Physical: yacht-based AMICA sensor nodes (NUC hardware, planned)

**SatoriHELPR** | Status: Live
- Marine AI navigation, sustainable fishing optimisation, safety alerts
- Revenue: Subscription (professional fishermen, recreational boaters, research institutions)

### 🌿 SatoriBUILD (Wood Element)

**Slipstream H&S App** | Status: Live
- Construction and trades health & safety management platform
- Revenue: B2B SaaS per-site/per-user licensing

### ⚙️ SatoriCO (Metal Element)

**SatoriMEMORIES** | Status: Live
- Physical collectibles marketplace with Arweave provenance minting
- Flow: item sourced → scanned → sealed → Arweave NFT minted → delivered
- Revenue: Sealing fee distributed across 5 S4S vaults:
  - Wood 40% | Metal 20% | Earth 15% | Water 15% | Fire 10%
- Payment: Solana (SOL/USDC) + S4S token
- Agentic roadmap: ElizaOS agents to autonomously browse TradeMe/FB Marketplace, flag items, trigger human fulfillment

### 🌍 SatoriINVEST (Earth Element)

**Status:** Spec/Early Development
- Conservation land acquisition, food forests, BTC-backed Real World Asset (RWA) vaults
- Tokenised land stewardship with S4S staking mechanics
- Revenue: Yield from conservation credits + land appreciation

### ⚙️ SatoriINSUR (Metal/Cross-Element)

**Status:** Business plan complete, development pending
- Proof of Vitality (PoV) insurance model — decoupled spoke
- Replaces actuarial age-banding with health-verified premiums
- Targets NZ insurance market failure (medical inflation 14.5% 2025, major provider hikes 17-33%)
- Revenue: Premiums + PoV reward distribution in S4S

### Side Projects
**Job Sorted Pro** (jobsorted.pro) — Trades and services marketplace. Independent revenue stream.

---

## IV. Infrastructure

### Sovereign Compute (I9Rig — Waihi, NZ)
- Hardware: i9-10900K, 62GB RAM, Ubuntu 24.04, 231GB SSD
- Connectivity: Starlink (primary), NAS via switch
- Local AI: Ollama (deepseek-r1:14b — Sentinel, phi4:14b — Mechanic)
- Storage: NAS 11TB (operational), GDrive 2TB (mirror/docs)
- Permanent storage: Arweave (provenance, whitepapers, token metadata)

### DePIN Nodes (Active Yield)
| Node | Type | Status | Yield |
|------|------|--------|-------|
| AIOZ | Video CDN | Active | AIOZ tokens |
| Grass | Bandwidth sharing | Active | GRASS tokens |
| Nexus | ZK proof computation | Active | Nexus points |
| Bitcoin Core | Full node | Active | Network participation |

### Payment Rails
- Solana: primary on-chain payments (SOL, USDC, S4S)
- Base/EVM: x402 micro-payment rail (`0xeB424380753Ec763106E2F26A729E60EB1263fF3`)
- Stripe: fiat subscription billing (Harmonic Navigator, SatoriINSIGHTS)

### Cognitive Trinity (AI Operations)
| Role | Model | Function |
|------|-------|---------|
| Navigator | Claude (Anthropic) | Strategy, security, final review |
| Architect | Gemini | System DNA, documentation, GDrive sync |
| Mechanic | phi4:14b (local) | Scripts, automation, bash execution |
| Sentinel | deepseek-r1:14b (local) | Analysis, research, code review |

---

## V. Revenue Flow Architecture

```
PRODUCT REVENUE
      │
      ├─ Stripe (fiat) → NZ bank → Operating expenses
      │
      ├─ Solana payments → Hot wallet → Swap to USDC → Kamino yield
      │
      ├─ SatoriMEMORIES sealing fees → 5 vaults (Wood/Metal/Earth/Water/Fire split)
      │
      ├─ DePIN rewards → Swap to USDC/JitoSOL → Kamino collateral
      │
      └─ S4S transfer fees (1%) → Multisig → Protocol treasury
```

**Liquidity flywheel:**
1. Product revenue funds S4S liquidity pool (Raydium)
2. Token liquidity enables S4S payments across products
3. S4S transfer fees accumulate in multisig → fund operations
4. DePIN yield compounds via Kamino → trading/operational capital

---

## VI. ⚠️ Tax & Legal Considerations
### *REQUIRES REVIEW BY QUALIFIED NZ TAX ADVISOR AND LEGAL COUNSEL*
### *This section identifies issues only — it does not constitute legal or tax advice*

### NZ Tax Residency
- Founder resident in Waihi, New Zealand
- All worldwide income potentially subject to NZ income tax
- IRD CARF implementation (2026): crypto exchanges now reporting to IRD automatically

### S4S Token Classification
**Issue:** IRD/OECD have not issued definitive guidance on all token types.
- **Utility token argument:** S4S grants access to ecosystem services (Harmonic Navigator, SatoriMEMORIES discounts, governance)
- **Payment token argument:** S4S accepted as payment across products
- **Security token risk:** If Metal vault vesting + founder allocation characterised as equity-like, securities law implications (FMA NZ jurisdiction)
- **REVIEW REQUIRED:** Classification determines: GST treatment, income vs capital, whether token issuance is a taxable event

### Transfer Fee (1%) Tax Treatment
- 1% collected on every S4S transfer to Squads multisig
- **Issue:** Each fee collection may be a taxable receipt in the period received
- **Issue:** If fees paid in S4S tokens, FMV at time of receipt needed for income calculation
- **REVIEW REQUIRED:** Protocol treasury treatment — is multisig a partnership, company, or trust for NZ tax?

### Vault Distributions
- Metal vault: 200M S4S vesting to founder over 60 months
- **Issue:** Each vest unlock may be a taxable income event at FMV on unlock date
- **Issue:** If S4S token has no established market price at unlock, valuation methodology needed
- **REVIEW REQUIRED:** Is vesting schedule documented in a formal agreement? Needs to be for tax purposes.

### SatoriMEMORIES Sealing Fees
- Fees split across 5 vaults in S4S tokens
- **Issue:** GST on digital services supplied from NZ to overseas buyers
- **Issue:** Physical goods component (shipping) vs digital service (Arweave minting) — different GST treatment
- **REVIEW REQUIRED:** Is each vault a separate taxable entity or all attributed to founder?

### Stripe Subscription Revenue
- Harmonic Navigator + SatoriINSIGHTS subscription fees
- Standard NZ income: assessable in year received
- GST: if turnover exceeds $60,000 NZD/year, GST registration required
- Overseas customers: exported services may be zero-rated for GST
- **RELATIVELY STRAIGHTFORWARD** — standard SaaS treatment

### DePIN Node Rewards
- AIOZ, Grass, Nexus tokens earned as network rewards
- **Issue:** Are these income (taxed when received at FMV) or capital (taxed on disposal)?
- IRD's position on crypto mining/staking rewards: generally income when received
- **REVIEW REQUIRED:** DePIN rewards closer to mining (income) or staking (potentially different)

### Arweave Storage
- Costs paid in AR tokens for permanent storage
- Generally deductible as business expense
- **Issue:** AR token purchases are capital acquisitions — only cost basis matters, deduction is the AR token FMV at time of use

### Vanuatu/Global Entity Structure
- Documents reference potential Vanuatu entity for global operations
- **CRITICAL REVIEW REQUIRED:** Vanuatu entity must have genuine substance to avoid NZ tax anti-avoidance rules
- NZ Controlled Foreign Corporation (CFC) rules may attribute offshore income back to NZ
- Transfer pricing rules apply to any NZ↔Vanuatu transactions
- **Do not establish offshore structure without specialist advice**

### Ocean Protocol Data Sales (SatoriFLOW)
- Data sold on Ocean Protocol marketplace
- Revenue received in OCEAN tokens
- **Issue:** Income in year tokens received at FMV
- **Issue:** Data privacy obligations (Privacy Act 2020 NZ) for any personal data components

---

## VII. Governance

### Sovereign Council (Multisig)
- Structure: Squads 2-of-4 multisig on Solana
- Address: `PddCBK3cEiQkzjHTDtWBxAw6mCP3JNxGrk2GAqpguPj`
- Controls: mint authority, fee config, fee withdrawal, metadata updates
- All protocol-level changes require 2 of 4 signatories

### Operational Wallets
| Wallet | Address | Purpose |
|--------|---------|---------|
| Personal | `6huWPSh85Fyk5ft1gmUnyBXRA432WDmLZYk7X1TnFApA` | Founder — NOT foundry controlled |
| Foundry Hot | `H6R24JdYnmJZTQFgA5J7N6XD8HXxJQwt1N2hNF2LpZ8g` | Operations |
| Base/EVM | `0xeB424380753Ec763106E2F26A729E60EB1263fF3` | x402 rail |

---

## VIII. Roadmap (Next 90 Days)

| Priority | Item | Element |
|---------|------|---------|
| 1 | SatoriINSIGHTS MVP live | Fire |
| 2 | S4S token liquidity (Raydium) | Water |
| 3 | ElizaOS agentic layer install | Fire |
| 4 | SatoriMEMORIES agent (TradeMe/FB) | Metal |
| 5 | NUC yacht node deployment | Water |
| 6 | Wix → agent-maintained content | Fire |
| 7 | Local 70b LLM (GPU fund) | Fire |
| 8 | SatoriINSUR development | Metal |

---

## IX. Key Links

| Resource | URL |
|---------|-----|
| Website | search4satori.com |
| GitHub | github.com/Satoriinvest |
| SatoriMEMORIES | asset-manager-satoriinvest.replit.app |
| Job Sorted Pro | jobsorted.pro |
| Token on Solscan | solscan.io/token/Dx7RCVwuXKHHmShzua6895Z8RWTiQSi1pabia4DGRB5D |

---

*Document prepared for internal review and legal/tax advisor session. All on-chain addresses verified against Solana mainnet-beta at time of writing. This document does not constitute legal or financial advice.*

*Built in Waihi, New Zealand. Version 6.0 — June 2026.*
