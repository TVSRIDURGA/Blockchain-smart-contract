# Blockchain-smart-contract
🚀 Ethereum Smart Contracts using Truffle & Ganache

This project demonstrates Ethereum smart contract development using Truffle and Ganache.
The contracts are compiled, deployed, and tested on a local blockchain network.
The project includes two example smart contracts:
->🪙 MetaCoin – a simple token transfer contract
->🔧 ConvertLib – a utility library used by MetaCoin
The contracts are compiled using Solidity 0.8.21 and deployed through Truffle to a Ganache local blockchain.

📌 Project Overview
This repository shows the complete workflow of Ethereum smart contract development:
1️⃣ Writing smart contracts in Solidity
2️⃣ Compiling contracts using Truffle
3️⃣ Deploying contracts to a local blockchain (Ganache)
4️⃣ Viewing accounts, transactions, blocks, and contracts

🛠️ Technologies Used
💻 Solidity (v0.8.21)
⚙️ Truffle Framework
⛓️ Ganache
🟢 Node.js
🌐 Ethereum Blockchain
The compiler configuration is defined in the Truffle configuration file.

📂 Project Structure
project-folder
│
├── contracts/
│   ├── ConvertLib.sol
│   └── MetaCoin.sol
│
├── migrations/
│   └── deployment scripts
│
├── test/
│   └── contract test files
│
├── truffle-config.js
│
└── README.md

📜 Smart Contracts
🔧 ConvertLib
ConvertLib is a Solidity library used for basic token value conversions.
✨ Features:
->Reusable smart contract library
->Utility functions
->Used by the MetaCoin contract

🪙 MetaCoin
MetaCoin is a sample cryptocurrency contract that allows users to:
💸 Send tokens to other accounts
🔍 Check account balances
🔄 Demonstrate blockchain transactions

🧪 Local Blockchain Setup
This project uses Ganache to simulate a local Ethereum blockchain.
Ganache provides:
👥 Test accounts
💰 Free ETH for transactions
⛏️ Real-time block mining
📊 Transaction tracking


🧱 Blocks
Ganache automatically mines blocks when transactions occur.
Each block contains:
🔢 Block number
⏰ Mining timestamp
⛽ Gas used
🔗 Transactions included


🔁 Transactions
Transactions include:
📦 Contract deployment
💱 Token transfers
⚡ Smart contract function calls
Each transaction includes:
🔑 Transaction hash
👤 Sender address
📍 Contract addres
⛽ Gas used

📦 Deployed Contracts
The following contracts were successfully deployed:
| Contract          Status     |
| --------------    ---------- |
| 🔧 ConvertLib  | ✅ Deployed |
| 🪙 MetaCoin    | ✅ Deployed |
