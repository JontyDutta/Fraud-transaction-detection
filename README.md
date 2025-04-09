# Fraud-transaction-detection

![image](https://github.com/user-attachments/assets/a7e5f9f9-d013-4519-a94c-07d92ed657b3)

# Problem Statement

This project aims to analyze and detect fraudulent financial transactions using a large-scale dataset provided by a financial company. The dataset contains over 1 million transaction records with detailed information such as transaction type, amount, origin and destination accounts, account balances before and after the transaction, and indicators for whether a transaction was fraudulent or flagged as suspicious

Data Description:-

Total Records: 1,048,576 transactions
Columns: 11 features

* step: Hourly time step of the transaction.
* type: Type of transaction (e.g., PAYMENT, TRANSFER, CASH_OUT).
* amount: Transaction amount.
* nameOrig and nameDest: Origin and destination customer IDs.
* oldbalanceOrg / newbalanceOrig: Sender’s balance before and after transaction.
* oldbalanceDest / newbalanceDest: Receiver’s balance before and after transaction.
* isFraud: Indicator (1 or 0) whether the transaction is fraudulent.
* isFlaggedFraud: Indicator for flagged fraud (by system rules).
* newbalanceOrig
* nameDest

# 💾 Project Files Description

* Jupyter NoteBook
* Question and answer

# Data Source:

* [Dataset](https://drive.google.com/file/d/1wJfhrKPmeCh4KindHTNaM2iyU7UY1N5s/view?usp=sharing)
  
# Summary

* The primary goal was to identify the patterns and behaviors that differentiate fraudulent activities from legitimate ones.
* To deepen the understanding, machine learning techniques were applied to identify the most influential features contributing to fraud prediction.
* The project proposed a series of infrastructure-level fraud prevention strategies, including real-time fraud detection, behavioral anomaly tracking, strict balance simulations, and enhanced user authentication for risky transaction types.
