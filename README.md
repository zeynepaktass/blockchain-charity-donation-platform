
 # 🌍 Blockchain-Based Charity Donation Platform

A transparent and secure **Ethereum-based donation system** that allows users to donate to verified charities using **MetaMask** and **smart contracts**.  


---

## 🧾 Project Overview

Traditional charity donation systems often suffer from **lack of transparency and trust**.  
This project leverages **blockchain technology** to provide a decentralized, immutable, and fully trackable donation process.

**Key Technologies:**
- Ethereum (Sepolia Testnet)
- Solidity Smart Contracts
- MetaMask Integration
- HTML, CSS, JavaScript
- Ethers.js & Firebase

---

## 🎯 Objectives

- **Security:** Guarantee safe and immutable donation transactions on Ethereum.  
- **Transparency:** Allow donors to track their donations in real-time.  
- **User-Friendliness:** Provide an intuitive web interface for easy use.  
- **Efficiency:** Automate donation handling and minimize transaction costs.

---


## ⚙️ System Architecture

**Architecture Type:** Three-tier (Presentation, Logic, Data)

- **Frontend:** HTML, CSS, JS  
- **Logic Layer:** Solidity smart contracts, Ethers.js  
- **Data Layer:** Ethereum blockchain + Firebase  

**Workflow:**
1. User selects a charity and clicks **Donate**.
2. **MetaMask** connects the wallet and confirms the transaction.
3. **Smart contract** executes and records the transaction on **Ethereum**.
4. Donor can view history and top donations from **Firebase** data.

---

## 💡 Features

- 🔗 **Blockchain-based transparency:** Each transaction is recorded on-chain.
- 👛 **MetaMask integration:** Easy and secure wallet connection.
- ⏱ **Real-time tracking:** View campaign progress and total donations.
- 📊 **Progress bars:** Dynamic visual updates based on blockchain data.
- 🧾 **Donation history:** Transparent reporting for all transactions.
- 🧠 **Smart contract automation:** Handles donations securely without intermediaries.

---

## 🧱 Smart Contract Overview

Language: **Solidity**  
Network: **Ethereum Sepolia Testnet**

**Main Functions:**
- `donate()` → Processes the donation and emits a `DonationReceived` event  
- `withdraw()` → Allows only the owner to withdraw funds  
- `getTotalDonationsAmount()` → Returns the total amount of donations  

**Security Measures:**
- Owner-only withdrawals  
- Fixed donation amounts for transaction consistency  
- Transparent event logging

---

## 🧩 Tools & Dependencies

| Tool | Purpose |
|------|----------|
| **Remix IDE** | Smart contract development and deployment |
| **MetaMask** | Wallet integration |
| **Ethers.js** | Ethereum blockchain communication |
| **Firebase** | Campaign data management |
| **Visual Studio Code** | Main development environment |

---



