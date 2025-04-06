# efePiSwap - Decentralized Exchange for Efe Nexus Pi

**efePiSwap** is a decentralized exchange (DEX) built for the Efe Nexus Pi ecosystem on the Pi Network blockchain. It allows users to swap the Efe Nexus Pi token with other tokens and manage liquidity, optimized for the Pi Browser.

## Features
- **Token Swapping:** Trade tokens with a basic 1:1 rate (expandable to AMM).
- **Liquidity Management:** Add or withdraw liquidity using the Efe Nexus Pi token.
- **Pi Network Ready:** Designed for Pi Network’s mobile-first ecosystem.

## Getting Started

### Prerequisites
- Node.js and npm
- Truffle (`npm install -g truffle`)
- Ganache (`npm install -g ganache-cli`) for local testing
- A Pi Network-compatible wallet

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/EfeNexus/efePiSwap.git
   cd efePiSwapInstall dependencies:npm installCompile and deploy contracts:ganache-cli  # Run in a separate terminal
truffle compile
truffle migrate --network developmentStart the frontend:npm startVisit http://localhost:3000 in your browser.ConfigurationUpdate migrations/1_deploy_contracts.js with the Efe Nexus Pi token address.Adjust truffle-config.js for Pi Network mainnet when available.UsageSwap Tokens: Enter token addresses and amounts in the frontend.Add Liquidity: Deposit Efe Nexus Pi tokens to enable trading.Project StatusCurrent: Basic swapping and liquidity features.Future: AMM support, Pi Network mainnet deployment.ContributingFork the repo, make changes, and submit a pull request.LicenseMIT LicenseContactCreated by username. Use GitHub Issues for questions or feedback.---
