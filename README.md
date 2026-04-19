# 🚀 Monad Testnet Automation

![Monad-BOT](https://img.shields.io/badge/Monad-BOT-blue.svg) ![License](https://img.shields.io/badge/License-ISC-green.svg) ![Platform](https://img.shields.io/badge/Platform-MacOS%2FLinux%2FWindows-lightgrey.svg)

Monad-Testnet-Automation is a blockchain automation tool designed to interact with various cryptocurrency services for swapping and staking tokens. It provides a **real-time dashboard** to monitor operations, logs transactions, and automates token interactions such as **wrapping/unwrapping** and **staking/unstaking**.

---

## ✨ Features

✔️ **Interactive Dashboard** - Real-time updates on balance, network status, and transaction history.  
✔️ **Automated Cycles** - Configurable task cycles for executing swap and staking operations.  
✔️ **Blockchain Interactions** - Uses `ethers.js` for seamless smart contract execution.  
✔️ **Multi-Service Support** - Supports Rubic Swap, Izumi Swap, Bean Swap, and more.  
✔️ **Private Key Security** - Loads private keys securely from `private.key`.  
✔️ **Customizable Configuration** - Easily adjust cycle parameters, RPC settings, and contract addresses.  
✔️ **Multiple Wallet Support** - Run the bot for multiple wallets simultaneously by adding multiple private keys.  

---

## 📦 Installation Guide

### ✅ Prerequisites

Ensure you have the following installed:
- **Node.js** (v16 or later) - [Download Here](https://nodejs.org/)
- **Git** (optional, for cloning the repository)

### 🔧 Installation Steps

#### 🖥️ MacOS & Linux
1️⃣ Open a terminal and run:
```bash
# Clone the repository
git clone https://github.com/Zack914/Monad-Testnet-Automation.git
cd Monad-Testnet-Automation

# Install dependencies
npm install
```

2️⃣ Add your **private keys** to `private.key` (one per line for multiple wallets):
```bash
nano private.key
```

3️⃣ Start the bot:
```bash
npm start
```

#### 🖥️ Windows
1️⃣ Open **PowerShell** and run:
```powershell
# Clone the repository
git clone https://github.com/Zack914/Monad-Testnet-Automation.git
cd Monad-Testnet-Automation

# Install dependencies
npm install
```

2️⃣ Add your **private keys** to `private.key` (using Notepad/ Notepad++ or PowerShell, one per line for multiple wallets):
```powershell
notepad private.key  # Open Notepad to edit the file
```
Paste your **private keys**, save the file, and close Notepad/ Notepad++.

3️⃣ Start the bot:
```powershell
npm start
```

---

## 🛠️ Configuration

Modify the `config/config.json` file to customize settings:
- **Network Settings**: Update the RPC URL and block explorer.
- **API Endpoints**: Define external API endpoints for staking and liquidity services.
- **Contract Addresses**: Adjust addresses for smart contracts used.
- **Cycle Parameters**: Modify default cycles, cooldown time, and delays.

---

## 🚀 Usage Guide

### 📊 Running the Bot
- Start the bot:
  ```bash
  npm start
  ```
- The terminal-based **dashboard** will display:
  - ✅ Balance updates
  - 🔄 Transaction logs
  - ⏳ Swap/Staking status
  - 📊 Progress over cycles
  - 🔄 **Multiple Wallet Processing**

### 🔄 Supported Services
The bot interacts with the following services:
- **Transactions**: Send random MON to wallets in wallets.txt, Deploy random smart contract
- **Swapping**: Uniswap, Rubic Swap, Izumi Swap, Bean Swap, Monorail
- **Staking**: Magma Staking, aPriori Staking, Kitsu Staking
- **Token Operations**: Balance checking, automated wrapping/unstaking
- **Multiple Wallets**: Supports running transactions for multiple wallets in a loop.

## 
Last updated: Sun Apr 19 12:55:21 UTC 2026


## 📜 License

This project is licensed under the **ISC License**.
