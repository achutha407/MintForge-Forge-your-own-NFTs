# MintForge – Forge your own NFTs

**MintForge** is a full-stack NFT minting dApp that allows users to connect their wallets, upload artwork, and mint NFTs directly on the blockchain. All NFT metadata and images are stored on IPFS, ensuring decentralization and permanence.

## Features
- Wallet integration with **MetaMask**. 
- Upload images and metadata to **IPFS**.
- Mint NFTs using **ERC-721 smart contracts**. 
- View all minted NFTs associated with your wallet.
- Full-stack implementation with **React frontend + Solidity backend + Node.js server (optional)**.

## Tech Stack
- **Frontend:** CSS/HTML  
- **Backend:** Node.js  
- **Blockchain:** Ethereum Testnet (Goerli) or Polygon Mumbai  
- **Smart Contracts:** Solidity (ERC-721 standard)  
- **Storage:** IPFS (images and metadata)  
- **Wallet Integration:** MetaMask  

## Architecture
1. **Frontend React App:** Connect wallet, handle form input, display minted NFTs.
2. **IPFS Integration:** Upload images and JSON metadata to IPFS, retrieve CID.
3. **Smart Contract:** Mint NFT using ERC-721 contract with metadata URI pointing to IPFS.
4. **NFT Display:** Fetch minted NFTs via contract calls and display in user gallery.
