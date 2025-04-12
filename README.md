# 🌐 **AstraSwap Staking Contract Suite**  
*Stake Smarter. Earn XUSD. Power the Future of DeFi.*

---

## 🧭 Introduction

**AstraSwap** is an innovative, **interoperable**, and fully **modular decentralized finance (DeFi) protocol** running on the scalable **EpicChain blockchain**. Designed with composability and capital efficiency in mind, AstraSwap empowers users to make the most of their assets through staking, yield strategies, and stablecoin issuance — all centered around one powerful tool: the **AstraSwap Vault**.

At its core, the **Vault** serves as an all-in-one **asset management** and **stablecoin issuance** hub. Here, users can:
- Stake assets and liquidity tokens
- Earn **XUSD** as yield and protocol incentives
- Mint more **XUSD** through overcollateralization
- Manage positions with transparent smart contracts

The Vault ecosystem is optimized for decentralized performance, letting users keep full custody while participating in AstraSwap's token economy.

---

## 🔐 What is Staking in AstraSwap?

Staking in AstraSwap is more than just passive income — it’s an **interactive and reward-generating mechanism** that powers the entire ecosystem. Users deposit supported assets (XEP-5 tokens such as wrapped tokens or LP tokens) into the Vault and receive rewards in **XUSD**, AstraSwap's stable and protocol-native token.

Upon staking, users:
- Earn **XUSD** in real-time as staking rewards
- Use the same staked collateral to **mint XUSD**
- Gain access to advanced DeFi opportunities like liquidity farming, trading, or lending

This creates a sustainable, dual-utility model for **XUSD**, driving both its demand and usability.

---

## 💠 Vault Mechanics — Stake, Earn, Mint

### 🔄 How It Works

1. **Select Your Token:**  
   Choose from a whitelist of **XEP-5 tokens** including:
   - Wrapped XPR/XPP (e.g., wXPR, wXPP)
   - AstraSwap LP tokens from liquidity pools
   - Native tokens approved by governance

2. **Deposit & Lock in the Vault:**  
   Tokens are deposited into the **Staking Contract**, optionally locked for a predefined duration (7, 14, or 30 days).

3. **Earn XUSD Rewards:**  
   Based on:
   - Amount of tokens staked
   - Lock duration (longer = higher rewards)
   - Asset type multiplier (certain assets may yield more)

4. **Mint More XUSD:**  
   Your collateral supports the issuance of fresh **XUSD**:
   - Minting limit: 80% Loan-to-Value (LTV)
   - Oracle-verified pricing ensures safety
   - This XUSD can be re-used across AstraSwap services or off-chain integrations

5. **Withdraw When Ready:**  
   After lockup or repayment of any XUSD minted, users can reclaim their full stake.

---

## 🧾 Supported Token Types

| Token Type       | Utility                                           | Eligibility for XUSD Rewards |
|------------------|---------------------------------------------------|-------------------------------|
| **Wrapped Assets** | Cross-chain tokens like wXPR, wXPP                | ✅ Yes                        |
| **LP Tokens**    | Liquidity pool shares on AstraSwap AMM            | ✅ Yes                        |
| **Whitelisted Assets** | Other protocol-specific or DAO-approved tokens | ✅ Yes                        |

📌 New tokens may be added through DAO voting mechanisms.

---

## 🛠️ Contract Scripthash

Below is a list of contracts deployed as part of the AstraSwap Staking ecosystem. Developers and integrators can use these scripthashes for Web3 dApps, wallets, or explorer lookups.

| Contract Name           | Script Hash                                     |
|-------------------------|-------------------------------------------------|
| **Staking Contract**    | `0xabcdef1234567890fedcba0987654321aabbccdd`    |
| **XUSD Token Contract** | `0x9988ffcc1122aabb4433ddeeff88997766554433`    |
| **Vault Core Logic**    | `0x1234567890abcdef1234567890abcdefabcdef12`    |
| **Reward Manager**      | `0xaabbccddeeff00112233445566778899aabbccdd`    |

> Always verify network (Mainnet/Testnet) before executing transactions.

---

## 💹 XUSD Rewards Model

AstraSwap uses a **block-by-block emission** model, where stakers receive **XUSD rewards** proportional to:

- ✅ Total stake value (based on USD equivalent)
- 🕒 Lock duration (bonus multipliers up to 2x)
- 📊 Token type weight

This means the longer you stake and the more value you provide, the higher your **XUSD reward yield**. Additionally:

- Rewards are updated **in real-time**
- Users can **compound** rewards or **claim manually**
- Future staking rounds may introduce **veXUSD governance** participation

---

## 🧮 Example Use Case

Let’s say **John** has **$1,000 worth of LP Tokens**.

- He locks them into the **Vault** for 30 days.
- The protocol assigns a **1.5x multiplier** for LP tokens with this duration.
- He receives daily **XUSD rewards** based on the adjusted stake value of $1,500.
- After 7 days, John has earned **125 XUSD** in rewards.
- He decides to **mint another 700 XUSD** against his LP collateral (70% LTV).
- John can now use **XUSD** to provide liquidity, swap, or lend elsewhere!

---

## 🛡️ Risk Management & Liquidations

All positions within the Vault follow robust **risk control mechanisms**:

- ✅ **Over-collateralization:** Users can only mint XUSD up to a safe percentage of their collateral value (e.g., 70–80% LTV).
- 📉 **Real-time Oracles:** Ensure accurate pricing of collateral assets.
- ⚠️ **Auto-liquidation:** If collateral value drops below safety thresholds, positions are liquidated, and XUSD debt is repaid.
- 🛠️ **Liquidator Incentives:** A portion of liquidated assets is given as a reward to protocol-maintained or third-party liquidators.

---

## 🧑‍💻 Developer & dApp Integrations

The AstraSwap Vault and Staking Contracts are fully composable and available for external integrations.

### 🔌 Integrate into Your dApp:

- Use the **Vault API SDK**
- Interact with **XUSD minting/burning**
- Fetch reward data and histories
- Connect staked assets to your product ecosystem

> 📚 Documentation: [docs.epic-chain.org/astraswap/sdk](https://docs.epic-chain.org/astraswap/sdk)

---

## 📘 Licensing

```
© 2023–2025 EpicChain Labs | AstraSwap Protocol

Licensed under the Apache License 2.0.
Use, copy, modify, and distribute under the terms outlined in the LICENSE file.
```

---

## 🧠 Acknowledgements

Big thanks to the following contributors and communities:

- EpicChain Blockchain Foundation
- EpicChain Labs core developers
- Contributors from SovereignEdge Quantum DAO
- DeFi inspiration from protocols like MakerDAO, Aave, and Curve
