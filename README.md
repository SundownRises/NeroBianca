🎮 NeroBianca: The Trustless Gaming Asset Marketplace
Gaming deals must be black and white, not gray.

NeroBianca is a decentralized, trustless gaming asset marketplace that brings in-game items and account data on-chain using the power of the NERO Chain, Account Abstraction (AA), and Paymaster infrastructure.

🚀 What It Does
🔐 Automated Wallet Onboarding
Web2 sign-in (email, OAuth) triggers invisible smart-contract wallet creation on NERO Chain.

Uses NERO's AA-Platform for seamless, gasless onboarding.

🤝 Trustless Escrow Trading
Game assets (skins, accounts, etc.) are locked in custom smart contracts.

Items are released only upon mutual confirmation or arbiter approval.

Arbiters validate transactions and earn reputation tokens.

⛽ Gas Sponsorship & Token Payments
Gasless onboarding with 10–15 free transactions (Type-0).

After quota: Users pay gas in ERC-20 tokens (e.g. USDC, WETH) (Type-1).

Native token not required. Clean, simple UX.

📜 Smart Contract-Powered Escrow
Built using OpenZeppelin’s Escrow and AccessControl libraries.

Atomic swaps upon successful trade fulfillment.

Integrated arbiter-based dispute resolution.

🏅 On-Chain Reputation via Soulbound Tokens (SBTs)
Non-transferable SBTs issued post-trade to all parties (buyers, sellers, arbiters).

Builds a trust layer with visible, verifiable reputation.

🌟 Permanent Gasless Trading for VIPs
High-trust users (reliable traders & arbiters) enjoy lifetime gas sponsorship.

Funded by a portion of escrow contract fees.

🔒 Security-First Approach
No session keys. Every transaction is explicitly signed.

No background delegation. User-first control.

❓ Why NeroBianca?
Pain Points Solved

Problem	Solution
Complex onboarding & gas fees	Invisible wallets & sponsored gas via NERO Paymaster
Scam-prone third-party markets	Smart contract-based escrow with arbiter resolution
Fragmented cross-game trading	Unified, on-chain marketplace with account abstraction
🧱 Technologies Used
🔗 Blockchain & Smart Contracts
NERO Chain w/ Blockspace 2.0 & Account Abstraction

Solidity w/ OpenZeppelin’s Escrow + AccessControl

Foundry for testing & deployment

🖥️ Frontend & Auth
Next.js (SSR)

RainbowKit / Wagmi for wallet connectivity

Web2 login (OAuth, passkeys)

🗄️ Storage & Hosting
Lighthouse.storage (encrypted, token-gated access)

Vercel for hosting

🧩 How It Works
Wallet & Paymaster Setup
Configure AA flows via NERO’s AA Docs

Deploy escrow & periphery contracts

Attach Paymaster API for gas sponsorship

Escrow Contract Development
Lock → Validate → Release pattern

Arbiter-based resolution with reputation token issuance

Soulbound Token System
Minted post-trade

Reflects credibility, arbitration feedback, and platform trust

🕹️ Target Games & Use Cases

Game	Feature
CS:GO	Peer-to-peer trading, Steam Market
PUBG	Skin & account trading
Modern Warships	In-game marketplace with dynamic pricing
Overwatch 2	Cross-platform progression & account merging
Warframe	Cross-play & cross-save
Brawlhalla	Full cross-platform play
Rocket League	Inventory sync via Epic Games
⚠️ The Problem With Existing Platforms
🚨 Example: $6M CS:GO Skins Stolen in 2022
Platforms like Tradeit.gg and CS.MONEY have suffered major breaches due to lack of trustless trading.

🔒 Our Solution
Smart contract-based, trustless trading

Soulbound tokens for reputation

Real-time monitoring, fraud prevention & user education

📚 Read: CS:GO $6M Theft News

📄 Documentation
🔗 NERO Chain Docs

📘 OpenZeppelin Docs
