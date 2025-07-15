#  Wallet Credit Scoring using ML 

This project builds an unsupervised credit scoring system for blockchain wallets using DeFi transaction data. It leverages the Isolation Forest algorithm to detect risky or anomalous behavior and assigns a normalized credit score between 0–1000 to each wallet.

---

##  Project Overview

###  Goal
To evaluate the financial trustworthiness of DeFi wallet users by analyzing their transaction patterns (borrowing, repaying, liquidation, etc.).

###  Key Features
- Parses raw wallet transaction logs
- Aggregates wallet behavior (e.g., number of borrows, repays)
- Extracts time-based features (days active, time since last activity)
- Applies Isolation Forest to detect anomalies
- Assigns each wallet a credit score from 0 to 1000
- Visualizes the distribution of wallet credit scores
- Outputs credit scoring insights per risk tier

---

