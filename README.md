# 🏦 Simple Blockchain Banking System

A **Python-based Blockchain Banking Application** that demonstrates how blockchain can be applied to banking and financial transactions.  
This project provides a simple console-based simulation of a **secure, decentralized banking system** where all transactions are stored in a blockchain ledger.

---

## 📖 About

This project is designed for learning purposes to showcase:  
- How **blockchain** works in a simplified way  
- How deposits, transfers, and balances can be securely managed  
- The role of **mining** in confirming and recording transactions  

It does not use real cryptocurrency but instead simulates the concept of blockchain in a **banking use case**.

---

## ✨ Features

- **Create Accounts** → Register new users in the banking system.  
- **Deposit Money** → Add funds to an account (stored as pending transactions).  
- **Transfer Funds** → Transfer money between accounts, with balance checks.  
- **Mine Blocks** → Confirm and record all pending transactions into the blockchain.  
- **Check Balances** → View real-time balances of all accounts.  
- **View Blockchain** → Display the entire blockchain ledger with all blocks and transactions.  

---

## ⚙️ How It Works

1. **Transaction Creation**  
   - Deposits and transfers are first added to the *pending transactions list*.  

2. **Mining**  
   - Mining validates all pending transactions and stores them permanently in a new block.  
   - Each block contains:  
     - Timestamp  
     - List of transactions  
     - Previous block hash  
     - Current block hash  

3. **Balances**  
   - Account balances are calculated based on confirmed transactions in the blockchain.  
   - Pending transactions do not update balances until mining is done.  

This ensures **immutability**, **transparency**, and **security** in the system.

---

## 🛠️ Technologies Used

- **Python 3** (Core language)  
- **hashlib** → Generates unique cryptographic hashes for each block  
- **json** → Manages block and transaction data in structured format  
- **time** → Adds timestamps to each block for proper sequencing  

👉 No external dependencies required — only Python’s standard library.  


