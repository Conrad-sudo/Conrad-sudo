# Hi, I'm Conrad 👋

**Smart contract & AI engineer.** I build, test and deploy secure, production-ready smart contracts and LLM agents, from the Solidity all the way to the agent that uses it on-chain.

[![Cyfrin Updraft SSCD+ certified](https://img.shields.io/badge/Cyfrin_Updraft-SSCD%2B_certified-5B4FE9)](https://profiles.cyfrin.io/u/conrad_sudo/certificates)

- 🎓 **Certified:** Cyfrin Updraft SSCD+ ([my Cyfrin profile](https://profiles.cyfrin.io/u/conrad_sudo/certificates))
- ⛓️ **Smart contracts:** Solidity and Foundry, from design through unit, fuzz, invariant and fork tests to multi-chain deployment
- 🛡️ **Security first:** checks-effects-interactions, reentrancy guards, access control, oracle staleness checks, written threat models
- 🤖 **LLM agents:** LangChain agents and tools that read chain data and prepare transactions, with guardrails so the model can't overspend
- 🚀 **Shipping:** deploy scripts, CI, FastAPI backends and React frontends around the contracts

---

## 🧩 Protocols & standards I work with

| Area | What I've built with |
|---|---|
| **Account abstraction** | ERC-4337 (EntryPoint, UserOperations, bundling), ERC-7579 modular accounts, zkSync native account abstraction |
| **DeFi** | Uniswap V2 & V3, PancakeSwap, overcollateralized stablecoins with liquidations, rebasing tokens |
| **Oracles & cross-chain** | Chainlink Price Feeds, VRF, Automation and CCIP |
| **Tokens** | ERC-20, ERC-721, airdrops with Merkle proofs |
| **Signatures & identity** | EIP-712, ECDSA, Sign-In with Ethereum (SIWE), ERC-8004 Trustless Agents |
| **Contract patterns** | UUPS upgradeable proxies, EIP-1167 minimal clones, OpenZeppelin Governor + Timelock |
| **Chains** | Ethereum, Arbitrum, Base, BNB Chain, zkSync, Sepolia |

---

## ⛓️ Smart contract projects

### [SessionHandler Protocol](https://github.com/Conrad-sudo/sh-protocol): agentic wallet infrastructure

Each user gets a smart wallet that an AI assistant runs from plain-language requests: sending, swapping, adding liquidity. The user keeps the root key, and the contracts, not the AI, decide what is allowed. Every transaction is checked against a daily US-dollar spending cap priced by Chainlink.

- ERC-4337 smart account + ERC-7579 spending-limit hook, with oracle, factory, registry and treasury contracts
- Unit, invariant and fork tests against live Ethereum, Arbitrum, Base and BNB Chain state
- LangChain agent, FastAPI backend, React web app and a Telegram bot on top

[![SessionHandler Protocol demo](https://img.youtube.com/vi/OIOLdvbGoNQ/hqdefault.jpg)](https://www.youtube.com/watch?v=OIOLdvbGoNQ)

### [Denari Stablecoin](https://github.com/Conrad-sudo/Denari_Stablecoin): USD-pegged stablecoin

An algorithmic ERC-20 stablecoin backed by outside crypto collateral. Users deposit collateral and mint Denari. A health factor priced by Chainlink keeps every position overcollateralized, and anyone can liquidate a position that falls below it.

`Solidity` `Chainlink Price Feeds` `OpenZeppelin` `invariant fuzz testing`

### [Merkle Airdrop](https://github.com/Conrad-sudo/merkle-airdrop): gas-efficient token airdrop

Eligible addresses are stored as one Merkle root instead of a list, and each claimer proves their place in it. Claims carry an EIP-712 signature, so someone else can pay the gas for a claim without being able to redirect it.

`Merkle proofs` `EIP-712` `ECDSA` `SafeERC20`

### [Crypto Lottery](https://github.com/Conrad-sudo/crypto-lottery): provably fair raffle

Players buy in, and Chainlink Automation triggers the draw on a schedule. Chainlink VRF supplies randomness nobody can predict or rig. Tested with unit and integration suites.

`Chainlink VRF` `Chainlink Automation` `unit + integration tests`

### [Smart Election](https://github.com/Conrad-sudo/smart-election): NFT-gated voting

One NFT, one vote. Covers candidate registration, a fixed voting window, double-vote protection and on-chain tie detection.

`ERC-721` `OpenZeppelin` `time-based testing`

### [FundMe](https://github.com/Conrad-sudo/foundry-fundme): crowdfunding with a USD minimum

Contributions are priced in US dollars through a Chainlink feed, so the minimum holds whatever ETH does. The Foundry test suite includes zkSync-specific checks.

`Chainlink Price Feeds` `zkSync` `Foundry scripts`

---

## 🤖 LLM agents & AI tools

### Open-source packages on PyPI

LangChain tools that turn on-chain actions into execution plans. A normal wallet can sign them, or a smart wallet can batch them.

| Package | What it does | |
|---|---|---|
| [langchain-erc8004](https://github.com/Conrad-sudo/langchain-erc8004) | ERC-8004 "Trustless Agents" registries: agent identity, reputation and validation | [![PyPI](https://img.shields.io/pypi/v/langchain-erc8004)](https://pypi.org/project/langchain-erc8004/) |
| [langchain-erc20](https://github.com/Conrad-sudo/langchain-erc20) | ERC-20 balances, allowances, transfers, approvals, and native wrap/unwrap | [![PyPI](https://img.shields.io/pypi/v/langchain-erc20)](https://pypi.org/project/langchain-erc20/) |
| [langchain-uniswap-v2](https://github.com/Conrad-sudo/langchain-uniswap-v2) | Query Uniswap V2 pools and build swaps on any EVM chain | [![PyPI](https://img.shields.io/pypi/v/langchain-uniswap-v2)](https://pypi.org/project/langchain-uniswap-v2/) |

### AI and trading tools

| Project | What it is |
|---|---|
| [ai-tool-platform](https://github.com/Conrad-sudo/ai-tool-platform) | AI assistants that chat over live web data, Wikipedia and your own documents |
| [lead-marketer](https://github.com/Conrad-sudo/lead-marketer) | Finds a company's employees on LinkedIn and drafts personal sales messages with an LLM |
| [Arbot](https://github.com/Conrad-sudo/Arbot) | Finds arbitrage opportunities across crypto exchanges |
| [Trade-Accountant](https://github.com/Conrad-sudo/Trade-Accountant) | Matches buy and sell orders across exchanges and works out the trading balance |

---

## 🛠️ Tools I use

![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-FFDB1C?logoColor=black)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=openzeppelin&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?logo=chainlink&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![web3.py](https://img.shields.io/badge/web3.py-F16822?logo=web3dotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
