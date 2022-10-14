#  DECENTRALIZED CRYPTO EXCHANGE

Hardhat Crypto Exchange where users can buy and trade crypto currency

# Getting Started

## Requirements
- Node.js
- Hardhat
- npm

## Quick start
```
git clone https://github.com/nickatnight23/Crypto-exchange.git
cd blockchain-developer-bootcamp
npm install
```

## Usage
Deploy:

If you are using localhost you are going to run a local node using hardhat
```
npx hardhat node
npx hardhat run --network localhost scripts/1_deploy.js
npx hardhat run --network localhost scripts/2_seed-exchange.js 
```
If you are using Goerli testnet you can do the following

```
npx hardhat run --network goerli scripts/1_deploy.js 
npx hardhat run --network goerli scripts/2_seed-exchange.js
```
Make sure that you have connected to a node provider and have Goerli connected
to Metamask and your account funded with test funds

## Test
```
npx hardhat test
```