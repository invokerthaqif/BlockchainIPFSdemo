# Blockchain Certificate System with IPFS

A decentralized certificate issuance, verification, and revocation system using:

- Solidity Smart Contract (Deployed via Ganache)
- IPFS file storage (Pinata)
- MetaMask wallet integration
- Node.js + Express backend
- React.js frontend

## Folders
- `cert-frontend/`: Frontend (React)
- `cert-backend/`: Backend (Node + Express + Web3)

## How to Run
1. Start Ganache and deploy contract
2. Update `.env` in `cert-backend/`
3. Run backend:
   ```bash
   cd cert-backend
   npm install
   node app.mjs
