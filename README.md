## Overview
A secure, gas‑optimized Ethereum raffle contract built with **Solidity**, **Foundry**, and **Chainlink VRF v2.5**.This project delivers **auditable randomness**, **reentrancy protection**, and **role‑based access control** for transparent prize draws on the **Sepolia testnet**.Includes full deployment scripts, comprehensive tests, and automatic **Etherscan verification**.

---

##  Features
- Automated draws with configurable intervals
- Chainlink VRF v2.5 randomness integration
- Security: access control & reentrancy protection
- Gas optimization using Foundry benchmarks
- Verified on Etherscan for public transparency
- Full script support for deploy & interactions---

##  Contract Details
- **Network:** Sepolia Testnet
- **Contract Address:** [`0xDBBf13cEE59ef8dDE693fb6327abe0490703e858`](https://sepolia.etherscan.io/address/0xdbbf13cee59ef8dde693fb6327abe0490703e858)
- **Verification:** [Etherscan Link](https://sepolia.etherscan.io/address/0xdbbf13cee59ef8dde693fb6327abe0490703e858#code)
- **Gas Used (Deploy):** `2,283,833` units (~0.00000228 ETH)

---

##  Tech Stack
- Solidity v0.8.18+
- Foundry (Forge, Cast, Anvil)
- Chainlink VRF v2.5
- Alchemy RPC for Sepolia
- Etherscan API (contract verification)
- Metamask
  

---

##  Deployment
bashforge script script/DeployRaffle.s.sol:DeployRaffle \
 --rpc-url $SEPOLIA_RPC_URL \
 --private-key $PRIVATE_KEY \
 --broadcast \
 --verify \
 --etherscan-api-key $ETHERSCAN_API_KEY \
 -vvvv

---

##  Testing
bash

forge test -vvv

forge coverage

Tests include:
- Entry validation
- Interval rules
- Randomness verification
- Winner payout logic

##  Security Considerations
- Role‑restricted draw execution
- Safe VRF callback handling
- Subscription funding checks
- Gas usage optimization---

##  Case Study
**Problem:** Need a decentralized raffle that’s verifiably fair and secure.

**Solution:** Built a Solidity contract integrating Chainlink VRF, deployed & verified via Foundry.

**Outcome:** Production‑ready draw system with transparent randomness and minimal gas cost.

---

## 🙏 Thank You
Thank you for taking the time to explore this project!  
If you found it interesting or useful, please ⭐  the repository and **follow* my GitHub profile for more blockchain and smart contract projects.  
Your support motivates me to keep building and sharing.