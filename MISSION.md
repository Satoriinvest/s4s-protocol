# Satori Foundry — Mission Context
*Updated: 2026-06-21 | Status: Mainnet Live*

## S4S Token (MAINNET)

- **Token:** S4S (Search4Satori)
- **Network:** Solana Mainnet-Beta
- **Mint Address:** `Dx7RCVwuXKHHmShzua6895Z8RWTiQSi1pabia4DGRB5D`
- **Standard:** Token-2022 (1% transfer fee)
- **Total Supply:** 1,000,000,000 S4S
- **Logo (permanent):** `arweave.net/0frRgezPejpEudnkRuT8w_uIkrJxfsBMO9iVnoX6Swk`
- **Metadata (permanent):** `arweave.net/gmbH48sveQolPvxnuHyL2MvW6puY9_Ms2DbBzLIcVAo`
- **Multisig:** S4S Sovereign Council 2-of-4 `PddCBK3cEiQkzjHTDtWBxAw6mCP3JNxGrk2GAqpguPj`

## Five Elements Vault System (MAINNET)

| Vault  | Allocation  | %   | Purpose                     | Address |
|--------|-------------|-----|-----------------------------|---------|
| Wood   | 400,000,000 | 40% | Community & Ecosystem Growth | `8fiTjLSXnp7wrowtgqWip6A5ibaJtbW3zGWHeHAfWJD3` |
| Metal  | 200,000,000 | 20% | Sovereign Reserve (Vested)   | `ogCuniVGfMcpDUoFW6cAnKit9PymgCF9gJt5W3hvgLi` |
| Earth  | 150,000,000 | 15% | Foundation & Infrastructure  | `54nrK3Hnhb5RZMWciMBzt6MFF1ciRGJc4qDcHdZ1HaLU` |
| Water  | 150,000,000 | 15% | Liquidity Provision          | `ECgFCuEWcuUJwFxaFEGaoABBhsFZMr7LuACwtKtzRXy3` |
| Fire   | 100,000,000 | 10% | Operations & Rewards         | `9sesX5oJHU8qDU85yByTmRjvk3r6z9t5xAxd2UZMBqLb` |

All authorities (mint, fee config, fee withdraw, metadata) transferred to multisig ✅

## Metal Vesting Schedule

- **Genesis Date:** February 21, 2026
- **Cliff Period:** 12 months (no tokens unlock until Feb 2027)
- **Linear Vesting:** 48 months after cliff
- **Monthly Unlock:** ~4,166,667 S4S/month
- **Full Vest Date:** February 21, 2031

## Wallet Registry (Public Addresses Only)

| Wallet            | Address                                        | Role |
|-------------------|------------------------------------------------|------|
| Personal (Solflare) | `6huWPSh85Fyk5ft1gmUnyBXRA432WDmLZYk7X1TnFApA` | Mike's private wallet — NOT foundry-controlled |
| Foundry Hot       | `H6R24JdYnmJZTQFgA5J7N6XD8HXxJQwt1N2hNF2LpZ8g` | DePIN swaps, x402 micro-payments |
| Forge (Base/EVM)  | `0xeB424380753Ec763106E2F26A729E60EB1263fF3`    | Base mainnet, x402 rail |
| Token Authority   | `r5Ec9TDV5qwDh9AoNtqxq7fyqiH6sKbJJfRUpdVdpuq` | Squads multisig — mint authority |
| ❌ NEVER USE      | `3SVPL...`                                     | Compromised 2026-03-26 |

## Hub-and-Spoke Architecture

```
         S4S PROTOCOL HUB
    (Sovereign 100-year ledger)
              │
  ┌─────┬─────┼─────┬─────┐
  ▼     ▼     ▼     ▼     ▼
WATER  WOOD  FIRE EARTH METAL
FLOW  BUILD TECH INVEST   CO
```

| Spoke       | Element | Products                                           |
|-------------|---------|---------------------------------------------------|
| SatoriFLOW  | Water   | Marine app, ocean data → Ocean Protocol, AMICA    |
| SatoriBUILD | Wood    | Slipstream H&S app, eco-construction, resilience  |
| SatoriTECH  | Fire    | Harmonic Navigator, SatoriINSIGHTS, SatoriREGEN, DePIN |
| SatoriINVEST| Earth   | Land vaults, conservation, BTC-backed RWA         |
| SatoriCO    | Metal   | Protocol governance, coaching, SatoriMEMORIES     |

## Infrastructure

### I9Rig (Waihi Shed)
- i9-10900K, 62GB RAM, Ubuntu 24.04
- Connectivity: Starlink (primary)
- Ollama: deepseek-r1:14b (Sentinel), phi4:14b (Mechanic)

### DePIN Nodes (Active)
- **AIOZ:** Video CDN node (Docker, aiozAiNodeWrapper v2.1.17)
- **Grass:** Bandwidth sharing (Docker)
- **Nexus:** ZK proof computation (active proving)
- **Bitcoin Core:** Full node (Docker, satori-btc)

## Disambiguation Rules

When element names appear in a query:
1. **Default:** S4S vault context
2. **Physical indicators** (shed/workshop/material/tool): physical context
3. **Token indicators** (vault/balance/supply/vesting/solana): S4S token context
4. **Healing indicators** (Mike/frequency/TCM/organ/Ayurveda): Five Elements healing context

## Side Projects
- **Job Sorted Pro** (jobsorted.pro) — service/trades marketplace
