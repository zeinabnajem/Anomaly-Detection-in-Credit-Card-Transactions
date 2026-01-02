# 💳 Anomaly Detection in Credit Card Transactions

## 📝 Project Overview
**Anomaly Detection in Credit Card Transactions** is an unsupervised machine learning project aimed at identifying potential fraudulent transactions without using labeled data.  
The goal is to **detect rare anomalies** in highly imbalanced datasets, helping to uncover fraudulent activities in credit card transactions.

---

## 🔍 Problem Statement
Detecting fraud in credit card transactions is challenging because:  
- Fraud cases are **extremely rare** compared to normal transactions  
- Labeled data may not always be available  
- Patterns of fraud can be subtle and hidden  

This project explores **unsupervised learning techniques** to automatically flag anomalous transactions.

---

## 💻 Technologies Used
- **Python**  
- **Pandas** & **NumPy** – Data manipulation  
- **Scikit-learn** – Unsupervised models (Isolation Forest, One-Class SVM)    
- **Matplotlib & Seaborn** – Data visualization  

---

## ⚙️ How It Works
1. **Data Exploration:**  
   - Analyze distributions of features such as `Amount` and `Time`  
   - Detect patterns, imbalances, or outliers in the data  

2. **Preprocessing:**  
   - Scale numerical features using `MinMaxScaler`  
   - Optional: Apply dimensionality reduction (PCA) for visualization  

3. **Unsupervised Anomaly Detection:**  
   - Apply algorithm: **Isolation Forest** to detect anomalies   

4. **Evaluation:**  
   - Reveal the hidden `Class` labels for evaluation  
   - Measure performance using **Precision, Recall, and F1-score**  
   - Focus on detecting rare fraud cases accurately  

5. **Insights:**  
   - Identify which types of transactions were flagged as anomalies  
   - Explore patterns in the detected fraudulent transactions  

---

## 📦 Dataset
- **Credit Card Fraud Detection – Kaggle**: [Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
---

## 🛠 Installation

To install the required packages, run:

```bash
pip install -r requirements.txt
