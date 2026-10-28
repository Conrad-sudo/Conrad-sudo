# Hi, I'm Conrad 👋

**Blockchain & AI engineer.** I build smart-contract wallets that AI agents can run safely, and the open-source tools that let those agents work with DeFi.

- 🔐 Smart accounts and account abstraction: ERC-4337, ERC-7579, session keys, on-chain spending limits
- 🤖 AI agents that act on-chain: LangChain tools, ERC-8004 agent identity and reputation
- 🧪 Solidity with Foundry: fork tests, fuzzing, gas work, security reviews

---

## ⭐ Featured: SessionHandler Protocol

**[sh-protocol](https://github.com/Conrad-sudo/sh-protocol)**: agentic wallet infrastructure.

Each user gets a smart wallet. An AI assistant runs it for them from plain-language requests: sending, swapping, adding liquidity. The user keeps the root key, and the contracts, not the AI, decide what is allowed. Every transaction is checked against a daily US-dollar spending cap priced by Chainlink.

- **On-chain:** ERC-4337 smart account + ERC-7579 spending-limit hook, Chainlink oracle, factory, registry and treasury contracts
- **Agent:** LangChain agent with quote-then-confirm transactions, Uniswap V2/V3 and PancakeSwap swaps, ERC-8004 identity
- **Apps:** FastAPI backend, React web app with wallet sign-in (SIWE), and a Telegram bot
- **Chains:** Ethereum, Arbitrum, Base, BNB Chain and Sepolia

[![SessionHandler Protocol demo](https://img.youtube.com/vi/OIOLdvbGoNQ/hqdefault.jpg)](https://www.youtube.com/watch?v=OIOLdvbGoNQ)

▶️ *Demo video: an AI agent running a smart wallet*

---

## 📦 Open-source packages (on PyPI)

LangChain tools that turn on-chain actions into execution plans. A normal wallet can sign them, or a smart wallet can batch them.

| Package | What it does | |
|---|---|---|
| [langchain-erc8004](https://github.com/Conrad-sudo/langchain-erc8004) | Tools for the ERC-8004 "Trustless Agents" registries: agent identity, reputation and validation | [![PyPI](https://img.shields.io/pypi/v/langchain-erc8004)](https://pypi.org/project/langchain-erc8004/) |
| [langchain-erc20](https://github.com/Conrad-sudo/langchain-erc20) | ERC-20 balances, allowances, transfers, approvals, and native wrap/unwrap | [![PyPI](https://img.shields.io/pypi/v/langchain-erc20)](https://pypi.org/project/langchain-erc20/) |
| [langchain-uniswap-v2](https://github.com/Conrad-sudo/langchain-uniswap-v2) | Query Uniswap V2 pools and build swaps on any EVM chain | [![PyPI](https://img.shields.io/pypi/v/langchain-uniswap-v2)](https://pypi.org/project/langchain-uniswap-v2/) |

---

## ⛓️ More smart contracts

| Project | What it is |
|---|---|
| [Denari Stablecoin](https://github.com/Conrad-sudo/Denari_Stablecoin) | Algorithmic ERC-20 stablecoin pegged to the US dollar, backed by outside collateral |
| [merkle-airdrop](https://github.com/Conrad-sudo/merkle-airdrop) | Token airdrop where claimers prove eligibility with Merkle proofs |
| [smart-election](https://github.com/Conrad-sudo/smart-election) | NFT-gated voting: one NFT, one vote, with time limits and tie detection |
| [crypto-lottery](https://github.com/Conrad-sudo/crypto-lottery) | Raffle that picks winners with Chainlink VRF randomness |
| [foundry-fundme](https://github.com/Conrad-sudo/foundry-fundme) | Crowdfunding contract with a USD minimum via a Chainlink price feed |

## 🐍 AI and trading tools

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
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?logo=chainlink&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=openzeppelin&logoColor=white)
