# 💳 Loan Default Risk with Business Cost Optimization

## 📌 Overview
This project focuses on predicting loan default risk using machine learning while minimizing financial losses through **cost-sensitive learning**. Instead of only maximizing accuracy, the model is optimized based on real business costs of wrong predictions.

---

## 🎯 Objectives
- Predict probability of loan default
- Reduce financial risk for lending institutions
- Optimize lending decisions using cost-sensitive evaluation
- Improve profitability and reduce bad loans

---

## 📊 Dataset
The dataset includes borrower financial and demographic information such as:
- Income
- Credit history
- Loan amount
- Employment details
- Payment behavior

---

## ⚙️ Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Handling Class Imbalance  
5. Model Training  
6. Cost-Based Evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision & Recall  
- F1-Score  
- ROC-AUC  
- Business Cost Function (False Positive & False Negative impact)

---

## 💰 Business Cost Optimization
The model assigns different penalties to:
- ❌ False Negatives (high cost: approving bad loans)
- ❌ False Positives (lost opportunity cost)

Final model selection is based on **minimum total business cost**, not just accuracy.

---

## 🚀 Installation
```bash
git clone https://github.com/your-username/loan-default-risk.git
cd loan-default-risk
pip install -r requirements.txt
