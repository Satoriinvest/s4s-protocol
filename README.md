# 🏺 Search4Satori (S4S) Protocol — Genesis V5.5

> *"Dirt on hands, stars in eyes."*

**Status: LIVE on Solana Mainnet-Beta** | June 2026

---

## What is S4S?

Search4Satori is a **100-year sovereign financial architecture** — a decentralised hub-and-spoke ecosystem bridging digital capital with real-world physical regeneration, marine sovereignty, and ecological stewardship.

The S4S token is the circulatory system connecting five elemental product streams, each solving a real problem while feeding back into the shared protocol ledger.

---

## 🪙 Token

| Field | Value |
|-------|-------|
| **Name** | Search4Satori |
| **Symbol** | S4S |
| **Network** | Solana Mainnet-Beta |
| **Mint** | `Dx7RCVwuXKHHmShzua6895Z8RWTiQSi1pabia4DGRB5D` |
| **Standard** | Token-2022 (1% transfer fee) |
| **Supply** | 1,000,000,000 S4S |
| **Governance** | Sovereign Council Multisig (2-of-4) |
| **Metadata** | [Arweave (permanent)](https://arweave.net/gmbH48sveQolPvxnuHyL2MvW6puY9_Ms2DbBzLIcVAo) |
| **Logo** | [Arweave (permanent)](https://arweave.net/0frRgezPejpEudnkRuT8w_uIkrJxfsBMO9iVnoX6Swk) |

---

## 🏗️ Hub-and-Spoke Architecture

```
              S4S PROTOCOL HUB
         (100-year sovereign ledger)
                    │
    ┌───────┬───────┼───────┬───────┐
    ▼       ▼       ▼       ▼       ▼
  WATER   WOOD    FIRE   EARTH  METAL
  FLOW   BUILD   TECH   INVEST   CO
```

### Five Elemental Streams

| Element | Spoke | Focus | Products |
|---------|-------|-------|---------|
| 🌊 Water | SatoriFLOW | Marine health, ocean data, blue carbon | SatoriHELPR, Ocean Protocol trading |
| 🌿 Wood | SatoriBUILD | Eco-construction, resilience, H&S | Slipstream safety app |
| 🔥 Fire | SatoriTECH | Digital infrastructure, AI, DePIN | Harmonic Navigator, SatoriINSIGHTS; enabling infrastructure for SatoriREGEN |
| 🌍 Earth | SatoriINVEST | Land vaults, conservation, RWA | BTC-backed terra vaults |
| ⚙️ Metal | SatoriCO | Protocol governance, provenance | SatoriMEMORIES, coaching |

SatoriREGEN is Earth-domain and Fire-powered: its product domain is ecological projects, MRV evidence, and environmental-credit state; SatoriTECH supplies the digital control-plane, event-routing, AI, and orchestration infrastructure. At the wider S4S level, Earth can include foundational assets and reserves such as BTC; SatoriREGEN does not own SatoriINVEST's real-estate or BTC-treasury functions. This taxonomy is not proof of credit integrity or deployed integrations.

## Canonical sources and project updates

- This repository owns S4S ecosystem policy and product taxonomy. `satori.json` is the machine-readable product registry; README, VISION, MISSION, and whitepaper text summarize it for people.
- `Satoriinvest/s4s-shared/events/` owns the executable event schemas, validators, fixtures, and runtime. This repository does not define a competing event schema.
- SatoriTECH rollout guidance governs approval and operation; it must refer to the shared contract rather than restate its payload shapes.
- Product repositories own their app code, data, and app-specific requirements. They consume reviewed protocol and shared versions through pinned commits or releases and review PRs.
- Propose upstream changes through PRs to the owning source. Do not directly push from an app Repl, and do not consume draft branches as approved dependencies.
- `s4s-shared/s4s.config.ts` is a compatibility surface for shared constants, not a source of product ownership. Where token/vault values overlap with `satori.json`, report drift rather than changing copies independently.

---

## 🪣 Five Vaults (Mainnet)

| Vault | Address | Allocation | Purpose |
|-------|---------|-----------|---------|
| 🌿 Wood | `8fiTjLSXnp7wrowtgqWip6A5ibaJtbW3zGWHeHAfWJD3` | 400M (40%) | Community & Ecosystem |
| ⚙️ Metal | `ogCuniVGfMcpDUoFW6cAnKit9PymgCF9gJt5W3hvgLi` | 200M (20%) | Sovereign Reserve (vested) |
| 🌍 Earth | `54nrK3Hnhb5RZMWciMBzt6MFF1ciRGJc4qDcHdZ1HaLU` | 150M (15%) | Foundation & Infrastructure |
| 🌊 Water | `ECgFCuEWcuUJwFxaFEGaoABBhsFZMr7LuACwtKtzRXy3` | 150M (15%) | Liquidity |
| 🔥 Fire | `9sesX5oJHU8qDU85yByTmRjvk3r6z9t5xAxd2UZMBqLb` | 100M (10%) | Operations & Rewards |

### Metal Vesting
- **Cliff:** 12 months (unlocks Feb 2027)
- **Linear vest:** 48 months (~4.17M S4S/month)
- **Full vest:** February 2031

---

## 🌐 Ecosystem Products

| Product | Status | Description |
|---------|--------|-------------|
| [SatoriMEMORIES](https://asset-manager-satoriinvest.replit.app) | Live | Physical collectibles + Arweave provenance minting |
| Harmonic Navigator | Live | Sovereign OS for personal alignment (astrology, Human Design, Gene Keys, Ayurveda) |
| SatoriINSIGHTS | Building | Crypto tax reconciliation — NZ IRD, CARF compliance |
| SatoriFLOW | Live | Marine & environmental data capture, Ocean Protocol |
| SatoriHELPR | Live | Marine AI navigation and safety |
| SatoriREGEN | Spec | Earth-domain ecological and enterprise green-IT MRV/credit-state rail; Fire-powered by SatoriTECH |
| SatoriBUILD Slipstream | Live | Construction health & safety management |
| [Job Sorted Pro](https://jobsorted.pro) | Live | Trades & services marketplace |

---

## 🔧 Infrastructure

Built on sovereign, local-first infrastructure:
- **I9Rig** — Waihi, New Zealand. i9-10900K, 62GB RAM, Ubuntu 24.04
- **DePIN Nodes** — AIOZ (CDN), Grass (bandwidth), Nexus (ZK proofs), Bitcoin Core
- **Storage** — Arweave (permanent), NAS (11TB), Starlink (connectivity)
- **AI Trinity** — Claude (Navigator), Gemini (Architect), DeepSeek/phi4 (local execution)

---

## 🧭 Philosophy

*Subtractive Creation* — reveal the sovereign signal by removing interference.

The S4S ecosystem operates on the principle that the most resilient systems mimic nature: decentralised, regenerative, and built for a 100-year horizon — not the next quarter.

**Website:** [search4satori.com](https://www.search4satori.com)

---

*Built in Waihi, New Zealand. Dirt on hands, stars in eyes.*
