# MyToken (MTK)

## 📌 Overview

MyToken (MTK) is a simple ERC-20 compatible token built on the Ethereum blockchain using Solidity.  
It is created purely for learning and educational purposes to understand how ERC-20 tokens work.

This token follows the standard ERC-20 implementation, including transfers, approvals, allowances, and events.

---

## 📊 Token Details

| Property       | Value                     |
| -------------- | ------------------------- |
| _Name_         | MyToken                   |
| _Symbol_       | MTK                       |
| _Decimals_     | 18                        |
| _Total Supply_ | 1,000,000 MTK (1 million) |

All tokens are minted to the deployer address upon contract deployment.

---

## ✨ Features

- ✔ Fully ERC-20 compatible
- ✔ Transfer tokens between addresses
- ✔ Approve other accounts to spend tokens
- ✔ transferFrom functionality
- ✔ Emits Transfer and Approval events
- ✔ Tracks balances and allowances
- ✔ Easy to deploy using RemixIDE

---

## 🚀 How to Deploy (Using Remix IDE)

1. Open **https://remix.ethereum.org/**
2. Create a new file called _MyToken.sol_
3. Paste your token contract code
4. Go to _Solidity Compiler_ → select version _0.8.x_
5. Click _Compile MyToken.sol_
6. Go to _Deploy & Run Transactions_
7. Select environment: _JavaScript VM_
8. In constructor field, enter total supply (for 1,000,000 tokens with 18 decimals):
