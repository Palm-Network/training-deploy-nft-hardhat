# Training material: How to deploy a contract on Palm

Training code for Palm documentation. This repo aims at supporting those learning how to deploy a contract on Palm using `Hardhat` and `Ethers.js`

This repo contains all the finished code explained at: https://docs.palm.io/HowTo/Deploy-using-Hardhat/.


### Installation

        npm install

### Configuration

Add an `.env` file matching the variables found in `hardhat.config.js`

### Usage

#### Deployment to Palm Testnet:

        npx hardhat run scripts/deploy.js --network palm_testnet

#### Deployment to Palm Mainnet:

        npx hardhat run scripts/deploy.js --network palm_mainnet
