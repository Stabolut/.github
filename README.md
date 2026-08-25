# Stabolut — Decentralized Stablecoin Ecosystem

Welcome to the official GitHub organization of **Stabolut**, a dual-stablecoin and gasless payment ecosystem powered by the **USB Stablecoin** and **SBL Governance Token**.

---

## 🏛️ Ecosystem Architecture & Repositories

```
                               ┌───────────────────────────┐
                               │   STABOLUT ECOSYSTEM      │
                               └─────────────┬─────────────┘
                                             │
      ┌──────────────────┬───────────────────┼───────────────────┬──────────────────┐
      ▼                  ▼                   ▼                   ▼                  ▼
┌───────────┐      ┌───────────┐       ┌───────────┐       ┌───────────┐      ┌───────────┐
│  mobile   │      │  backend  │       │ frontend  │       │smartcontr.│      │   Audit   │
│React Native│     │NodeJS API │       │ React Web │       │Solidity   │      │ Contracts │
│Wallet App │      │& Relayer  │       │Buy Portal │       │ ERC-865   │      │ & Reports │
└───────────┘      └───────────┘       └───────────┘       └───────────┘      └───────────┘
```

### 📦 Public Repositories

| Repository | Description | Tech Stack | Status |
| :--- | :--- | :--- | :---: |
| **[`mobile`](https://github.com/Stabolut/mobile)** | Non-custodial mobile wallet with biometric security, staking, and gasless transfers | React Native, Redux, Ethers | 🟢 Active |
| **[`backend`](https://github.com/Stabolut/backend)** | REST API, WebSockets, and EIP-712 gasless transaction relayer for Arbitrum & XDC | Node.js, Express, MongoDB, Web3 | 🟢 Active |
| **[`frontend`](https://github.com/Stabolut/frontend)** | Web purchase portal enabling users to buy USB tokens with ETH and BTC | React 18, MetaMask, UniSat | 🟢 Active |
| **[`smartcontracts`](https://github.com/Stabolut/smartcontracts)** | Core ERC-865 USB Token smart contracts with pre-signed off-chain gasless transfers | Solidity ^0.8.20, Hardhat | 🟢 Active |
| **[`Audit`](https://github.com/Stabolut/Audit)** | Full smart contract audit suite, Foundry unit tests, treasury engine, and architecture | Solidity, Foundry, Python | 🟢 Active |
| **[`Whitepaper`](https://github.com/Stabolut/Whitepaper)** | LaTeX source and compiled PDF for the core Stabolut USB and SBL tokenomics | LaTeX, PDF | 🟢 Active |
| **[`Whitepaper-Mica`](https://github.com/Stabolut/Whitepaper-Mica)** | LaTeX source and regulatory documentation for European MiCA compliance (ESB Token) | LaTeX, Markdown | 🟢 Active |

---

## ⚡ Quick Start: Running the Ecosystem Locally

### 1. Start Backend & MongoDB
```bash
git clone https://github.com/Stabolut/backend.git
cd backend
cp .env.example .env
docker compose up --build
```
*API available at `http://localhost:8003` with Swagger docs at `http://localhost:8003/api-docs`.*

### 2. Run the Mobile Wallet
```bash
git clone https://github.com/Stabolut/mobile.git
cd mobile
npm install
npm start
# In a new terminal: npm run android (or npm run ios)
```

### 3. Run the Web Purchase Portal
```bash
git clone https://github.com/Stabolut/frontend.git
cd frontend
npm install && npm start
```

---

## 📄 License & Community
All code across the Stabolut ecosystem is open-sourced under the **MIT License** (and GPL-3.0 for Whitepapers/Audit specifications).
- Website: [stabolut.com](https://stabolut.com)
- Telegram: [t.me/stabolut](https://t.me/stabolut)
- Twitter: [@stabolut](https://twitter.com/stabolut)
