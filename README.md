# Blockchain Contracts

📌 Showcase of my Solidity smart contracts built with Foundry and OpenZeppelin.

---

## 📂 Contracts
- **ERC20 – JobsToken**  
  Basic fungible token with mint, pause, and cap functionality.  

- **ERC721 – JobsNFT**  
  NFT contract with metadata storage.  

- **Advanced ERC721 – JobsNFTBurnable**  
  NFT contract with burn functionality.  

---

## 🚀 Deployment
Contracts are deployed and tested on **Sepolia testnet** using **Foundry**.

Example deployment command:
```bash
forge script script/DeployJobsNFT.s.sol --rpc-url $SEPOLIA_RPC --private-key $PRIVATE_KEY --broadcast
