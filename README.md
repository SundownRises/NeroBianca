# 🎮 NeroBianca: A Trustless Game-Asset Marketplace

**Gaming deals must be black and white, not gray.**

NeroBianca is a concise, trustless game-asset marketplace bringing in-game items and account data on-chain using the **NERO Chain** with **Account Abstraction (AA)** and **Paymaster** mechanisms.

---

## 🔧 What It Does

### ✅ Automated Wallet Onboarding
- Users sign in via Web2 accounts (email, OAuth).
- Smart-contract wallets are deployed invisibly using AA on NERO Chain.
- Seamless onboarding — no native tokens or wallets needed.

### 🔐 Trustless Escrow Trading
- In-game assets (skins, accounts, progression) are locked in a bespoke escrow contract.
- Release only on mutual confirmation or via arbiter approval.
- Arbiters earn reputation tokens for validation.

### ⛽ Gas Sponsorship & Token Payments
- **Type-0 (Free Gas):** 10–15 free transactions per new user.
- **Type-1 (ERC-20 Gas):** After quota, users pay with USDC, WETH — no NERO tokens needed.
- Cleaner UX with gas auto-deducted from ERC-20 balances.

### 🔁 Smart Contract Escrow
- Trustless trades using atomic swaps.
- Escrow holds both assets & funds.
- Dispute resolution powered by verified arbiters.

### 🏅 On-Chain Reputation with Soul-Bound Tokens (SBTs)
- SBTs issued to buyers, sellers, and arbiters after trades.
- Non-transferable and immutable – reflects user credibility.
- Used for trust scores and arbiter eligibility.

### 🔄 Permanent Gasless Trading for Trusted Users
- Lifetime gas sponsorship for reliable users.
- Funded via escrow contract fees.
- Incentivizes loyalty and good behavior.

### 🔐 Security-First UX
- No session keys or background delegation.
- All actions explicitly signed for full control and minimized abuse risk.

---

## 💡 The Problem It Solves

- ❌ **Complex Onboarding:** Manual wallets & crypto purchases.
- ❌ **Scams & Theft:** $6M+ in stolen CS:GO skins in 2022.
- ❌ **Fragmented Platforms:** No unified, tamper-proof asset marketplace for cross-platform games.

✅ **NeroBianca Fixes That** with:
- Smart-contract escrow trading.
- On-chain credibility via SBTs.
- Seamless, gasless entry and trading.

---

## 🔗 Game Support

### 🔫 PUBG & CS:GO (Steam)
- Steam Market integration for skins & accounts.
- CS:GO supports peer-to-peer trading.

### 🚢 Modern Warships (Mobile)
- In-game trading of ships, missiles, gear.
- Dynamic, supply-demand economy.

### 🎮 Overwatch 2
- Cross-platform account merging & skin sync.

### ⚔️ Warframe
- Cross-play & cross-save support.

### 🥊 Brawlhalla
- Unified progression across PC, console, mobile.

### 🚗 Rocket League
- Cross-platform item trading via Epic accounts.

---

## 🛠️ Technologies Used

### 🔗 Blockchain & Account Abstraction
- NERO Chain (Blockspace 2.0, ERC-4337 AA)
- AA-Platform Paymaster for sponsored gas

🔗 [docs.nerochain.io](https://docs.nerochain.io)

### 🧠 Smart Contracts
- Solidity
- OpenZeppelin's Escrow & AccessControl

🔗 [OpenZeppelin Docs](https://docs.openzeppelin.com/)

### 🌐 Frontend & Auth
- **Next.js** (SSR)
- **RainbowKit** / **Wagmi** for wallet connect
- Web2 login + passkey authentication

### 📦 Storage & Hosting
- **Lighthouse.storage** for encrypted metadata
- **Vercel** for frontend
- **Foundry** for testing/deployment

---

## 🧱 Architecture Overview

### 1. AA Wallet & Paymaster
- UserOperation flows with gasless transactions.
- Paymaster API integration with escrow contracts.

### 2. Escrow Contract Logic
- Minimal-trust `lock → validate → release` pattern.
- Based on OpenZeppelin’s base escrow.

### 3. Frontend Integration
- Next.js + AA SDK
- Real-time status, Paymaster policy handling

### 4. Reputation Engine
- Non-transferable SBT contract.
- Tracks trade completion & arbiter feedback.

---

## 📣 Learn More

- [Nero Chain Documentation](https://docs.nerochain.io)
- [OpenZeppelin Escrow](https://docs.openzeppelin.com/contracts/)
- [Vitalik on Soul-Bound Tokens](https://vitalik.eth.limo/general/2022/01/26/soulbound.html)
- [CS:GO Theft News](https://www.pcgamer.com/csgo-skin-scam-2022/)
- [Tradeit.gg](https://tradeit.gg/)

---

