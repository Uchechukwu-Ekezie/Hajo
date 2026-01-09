# Hajoo

Hajoo is a simple, onchain community savings (Ajo/Esusu) app built on Hedera. Create a rotational savings pool with friends, contribute on schedule, and track everything transparently from a clean dashboard.

## What’s included (MVP)
- Rotational savings pool creation and contributions
- Wallet connection via WalletConnect AppKit (MetaMask, etc.)
- Hedera Testnet/Mainnet configuration
- Minimal dashboard for pools and activity

## Tech Stack
- Frontend: Next.js, React, Tailwind CSS
- Wallet/Chains: wagmi + @reown/appkit (WalletConnect)
- Contracts: Solidity (Factory + Pool), Hardhat/Foundry
updatind the rear. sjjs
## Quickstart
1) Prerequisites
- Node.js 18+
- A WalletConnect Project ID

2) Env vars (frontend/.env.local)
```
NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID=your_project_id
NEXT_PUBLIC_FACTORY_ADDRESS=0x...
NEXT_PUBLIC_TOKEN_ADDRESS=0x...
# Optional custom RPC
NEXT_PUBLIC_HEDERA_RPC_URL=https://testnet.hashio.io/api
```

3) Run the app
```
cd frontend
npm install
npm run dev
```
Open http://localhost:3000

## Notes
- If MetaMask extension isn’t installed, use WalletConnect (QR) or MetaMask Mobile browser.
- Hedera networks supported: Testnet (296) and Mainnet (295).

## Links
- Repo: https://github.com/NOM-GAME/Hajo
- Chain: https://hedera.com
