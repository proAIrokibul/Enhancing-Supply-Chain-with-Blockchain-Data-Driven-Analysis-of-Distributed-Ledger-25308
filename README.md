# Enhancing-Supply-Chain-with-Blockchain-Data-Driven-Analysis-of-Distributed-Ledger-25308
## 📌 Project Overview

This project explores the integration of **blockchain technology** with **data-driven analytics** to enhance transparency, traceability, and fraud detection in supply chains. By analyzing over 10,000 transaction records enriched with IoT sensor data and smart contract metadata, we apply machine learning models to detect potential fraudulent activities.

## 📂 Dataset Description

The dataset includes 18 features from blockchain-powered supply chain transactions, such as:

- 📄 **Transaction Info:** Transaction ID, Timestamp, Item ID, Supplier ID, Customer ID  
- 🌍 **Environmental Metrics:** Temperature, Humidity, GPS Coordinates  
- 📦 **Order Metrics:** Order Amount, Quantity Shipped, Time to Delivery, Order Status  
- 🔒 **Blockchain Indicators:** Transaction Hash, Smart Contract Status, Compliance Check  
- 🎯 **Target Variable:** Fraud Indicator (0: Not Fraud, 1: Fraud)

## 🔬 Project Pipeline

1. **Exploratory Data Analysis (EDA)**  
   - Unique visualizations to identify fraud-prone patterns.
   - Detection of order mismatches, contract failures, and anomaly zones.

2. **Data Preprocessing**  
   - Missing values handled.
   - Label encoding and scaling applied.
   - Train-test split: 80% training / 20% testing.

3. **Classification Models**

### 🔎 Logistic Regression

✅ **Accuracy:** 0.4979

```
              precision    recall  f1-score   support

           0       0.50      0.50      0.50      1294
           1       0.50      0.49      0.50      1293

    accuracy                           0.50      2587
   macro avg       0.50      0.50      0.50      2587
weighted avg       0.50      0.50      0.50      2587
```

---

### 🌳 Random Forest

✅ **Accuracy:** 0.5238

```
              precision    recall  f1-score   support

           0       0.52      0.57      0.54      1294
           1       0.53      0.48      0.50      1293

    accuracy                           0.52      2587
   macro avg       0.52      0.52      0.52      2587
weighted avg       0.52      0.52      0.52      2587
```

---

### ⚡ XGBoost

✅ **Accuracy:** 0.5072

```
              precision    recall  f1-score   support

           0       0.51      0.50      0.50      1294
           1       0.51      0.52      0.51      1293

    accuracy                           0.51      2587
   macro avg       0.51      0.51      0.51      2587
weighted avg       0.51      0.51      0.51      2587
```

## 📊 Results Summary

| Model               | Accuracy | F1-Score |
|--------------------|----------|----------|
| Logistic Regression| 0.4979   | 0.50     |
| Random Forest      | 0.5238   | 0.52     |
| XGBoost            | 0.5072   | 0.51     |

Despite relatively balanced results, improvements can be made using advanced techniques like:
- Feature engineering
- SMOTE for class imbalance
- Ensemble stacking

## 📈 Business Impact

- 🔐 **Transparency & Trust:** Immutable blockchain records ensure traceable and tamper-proof transactions.
- 🚨 **Fraud Detection:** ML identifies high-risk transactions by analyzing mismatches, delays, and contract failures.
- 💰 **Cost Reduction:** Reduces losses from shipment discrepancies and payment frauds.
- 📜 **Compliance Monitoring:** Flags non-compliant transactions using real-time contract and location checks.


