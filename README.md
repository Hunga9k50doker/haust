# HAUST AUTO CLAIM FAUCET

![banner](image.png)
- Website https://haust.network/

## What Is Haust Network

Haust Network: A Versatile Blockchain Solution

Haust is a built on Ethereum Virtual Machine (EVM) blockchain specifically designed for micropayment solutions and gas-intensive smart contracts. Haust Network is a versatile project that leverages the permissionless nature of blockchain technology to deliver innovative solutions.

It provides decentralized finance (DeFi) solutions and also pioneers the implementation of a symbiotic network.

Haust boasts hight security low commissions and provides its own SDK for native integrations with Telegram and other messengers. Notably, the network introduces Haustoria, a feature enabling liquid staking on various networks directly connected to Haust.

## auto mint / bridge and distribute eth
- auto distribute eth sepilia to another addr in wallets json
- just input `y` if you want to auto distribute eth to another wallet
- input `n` to continue mint and bridge process
- Make sure you setup private key on  in config.json and the wallet have sepolia eth
   ```
   node bridge
   ```
   
## Update
- add auto deploy and interact with contract
- `git pull` and re install dependencies `npm install`

- run deploy: 
   ```bash
   node deploy
   ```

## Features

- **Auto Generate New Wallets**
- **Auto Claim Faucets To New Address**
- **All Wallets information Saved In wallets.json** 
- **Haust Token Faucet Is Limited so Act Fast**

   ![faucet](image-1.png)

## Requirements

- **Node.js**: Ensure you have Node.js installed.
- **npm**: Ensure you have npm installed.


## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Hunga9k50doker/haust.git
   cd haust
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Setup: to create new wallets 
   ```bash
   node setup
   ```
4. Run The Script:
   ```bash
   node start
   ```


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
