# Synthetic Retail Banking Transactions Dataset

## Overview
This project provides a **privacy-preserving synthetic banking dataset** designed for
machine learning, analytics, and fraud detection research.

The dataset simulates realistic customer behavior and transaction patterns
commonly found in retail banking systems, while containing **no real personal data**.

---

## Dataset Description

### Customers Table (`customers.csv`)
- `customer_id` — Unique customer identifier
- `age` — Customer age
- `gender` — Gender
- `country` — Country of residence
- `account_type` — Savings / Current
- `account_balance` — Current account balance
- `credit_score` — Creditworthiness score
- `join_date` — Account creation date

### Transactions Table (`transactions.csv`)
- `transaction_id` — Unique transaction identifier
- `customer_id` — Linked customer
- `transaction_date` — Timestamp of transaction
- `amount` — Transaction amount
- `transaction_type` — Transfer / Payment / Withdrawal
- `channel` — ATM / Online / POS
- `merchant_category` — Merchant category
- `is_fraud` — Fraud label (0 = normal, 1 = suspicious)

---

## Key Features
- Realistic behavioral patterns (day/night activity cycles)
- Statistically consistent transaction amounts
- Rare but meaningful fraud events (≈1–3%)
- Ready-to-use features for ML training
- Fully synthetic and GDPR-safe

---

## Use Cases
- Fraud Detection Model Training
- Risk Analysis & Simulation
- Data Science Education
- Privacy-Safe Prototyping

---

## Data Generation
The dataset was generated using Python with controlled probabilistic logic to
ensure statistical realism while avoiding data leakage.

Libraries used:
- NumPy
- Pandas
- Faker

---

## Disclaimer
This dataset is **entirely synthetic** and does not represent real customers,
accounts, or transactions.
