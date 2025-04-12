# 🌟 **AstraSwap IDO Smart Contract Suite**  

Welcome to the **AstraSwap Initial DEX Offering (IDO) Platform**, your gateway to the future of decentralized token launches. AstraSwap’s IDO ecosystem is engineered to empower developers, investors, and blockchain innovators with a robust, secure, and scalable infrastructure for launching and investing in new digital assets.  

Whether you're a project looking to raise capital, or a community member excited to get early access to groundbreaking tokens, the **AstraSwap IDO Contract Suite** is the ideal starting point.

---

## 🚀 What is AstraSwap IDO?

The **AstraSwap IDO (Initial DEX Offering)** is a powerful smart contract-based framework built to manage decentralized token launches. With AstraSwap IDO, new blockchain projects can raise funds through token sales directly on the decentralized exchange (DEX), leveraging smart contract automation, transparency, and trustlessness.  

Our platform architecture is modular and flexible — designed to handle token-specific logic and maintain a seamless experience for both developers and investors.

---

## 🛠️ System Architecture & Development Overview

The AstraSwap IDO system is structured around **two core contract types**:

1. **Main IDO Contract**  
   - Central to the AstraSwap IDO system, this contract orchestrates the entire token offering logic.  
   - It handles IDO lifecycle management, user participation rules, and global IDO settings.

2. **IDO Pair Contracts**  
   - Each new token launch is associated with its own dedicated IDO Pair Contract.  
   - These contracts manage token-specific details such as contribution limits, vesting, distribution, and asset custody.

> 📁 **Directory Structure**  
> - Main IDO Contract: `contracts/IdoContract`  
> - Sample IDO Pair Contract: `contracts/IdoPairContract`  

The modular architecture ensures that each token project can operate independently, yet still leverage the core services provided by the main contract.

---

## 🧪 Testing the IDO Contracts

Before running tests on the IDO system, certain supporting contracts — known as **mock contracts** — must be deployed on your local or private testnet environment. These contracts simulate interactions and dependencies required by the IDO system.

### ✅ Testing Setup Instructions

1. Navigate to the test directory of the main IDO contract:  
   ```
   cd contracts/IdoContract/test
   ```

2. Run the unit tests:  
   ```
   dotnet test
   ```

> 🔎 Mock Contracts Location: `contracts/IdoContract/mock`

These tests validate critical logic including:
- Token contribution rules
- Token distribution logic
- User allocation limits
- Admin management features
- Vesting and refund mechanisms

---

## 🏗️ Building the Contracts

To compile and build the main IDO contract suite, follow these simple steps:

1. Navigate to the contract’s source directory:  
   ```
   cd contracts/IdoContract/src
   ```

2. Run the build command using the .NET CLI:  
   ```
   dotnet build
   ```

This will generate the compiled binaries and artifacts needed for deployment and further development.

---

## 📚 Documentation Summary

| Section            | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Main Contract      | Core logic for managing IDO campaigns and admin controls     |
| IDO Pair Contracts | Manages individual token sale configurations and parameters  |
| Testing            | Unit testing via `dotnet test`, mock setup required          |
| Build              | Build via .NET CLI using `dotnet build`                      |

---

## 🌐 Get Involved

AstraSwap is more than just a product — it’s a community of pioneers reshaping the future of token launches. We invite developers, blockchain enthusiasts, and contributors to explore the codebase, deploy your own tokens, and push the boundaries of decentralized finance (DeFi).

> 🔧 Stay tuned for advanced features such as KYC support, whitelisting tools, community voting for token launches, and automated liquidity generation!

Let’s build the future together. 🚀