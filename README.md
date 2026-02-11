# To-Do-Solidity-

# Solidity Todo DApp with Rewards

A decentralized Todo List smart contract that allows users to create tasks, mark them as completed, and earn reward points.  
The contract is controlled by an owner who can update the reward per task.

---

## 🚀 Features

- ✅ Create personal to-do tasks  
- ✅ Mark tasks as completed  
- 🎁 Earn reward points for each completed task  
- 🗑 Delete tasks  
- 🔐 Only the owner can update the reward amount  
- 📡 Events emitted for frontend integration  

---

## 🛠 Tech Stack

- Solidity ^0.8.31  
- Ethereum / EVM compatible networks  
- Remix / Hardhat for deployment  

---

## 📦 Contract Overview

### Ownable Contract
- Stores contract owner  
- Provides `onlyOwner` modifier for admin functions  

### Todo Contract

Ea
