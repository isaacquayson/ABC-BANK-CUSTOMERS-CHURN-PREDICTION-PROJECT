# ABC-BANK-CUSTOMERS-CHURN-PREDICTION-PROJECT

## 📌 Client's Problem
We have noticed a worrying trend: many of our long-term customers are leaving the bank for competitors.  
This is hurting revenue because acquiring a new customer costs much more than keeping an existing one.  
Currently, we don’t have a clear way of identifying which customers are at risk of leaving.  
Our retention campaigns are random, wasting resources and often targeting the wrong people.  

**The task**: As a data scientist, help identify at-risk customers and provide actionable solutions.

---

## 🎯 Objectives
- Analyse the historical data to provide decision-driven insights.  
- Investigate the key factors driving customer churn.  
- Build supervised ML models (**XGBoost Classifier** and **Logistic Regression**) to predict churn likelihood.  
- Deliver actionable recommendations for smarter retention strategies.

---

## 📊 Relevant Data Points
Historical dataset includes:
- Customer ID  
- Credit Score  
- Country  
- Gender  
- Age  
- Tenure (years)  
- Account Balance  
- Number of products owned  
- Credit Card (yes/no)  
- Active Member (yes/no)  
- Estimated Salary  
- Churn (yes/no)  

**Dataset Source:**  
[Bank Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)

---

## 🛠️ Tools & Libraries
- **Programming Language**: Python  
- **Visualization**: Power BI  
- **Libraries**: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `flask`, `html/css`, `xgboost`

---

## 🔄 Data Cleaning & Preprocessing
- Handled missing values  
- Corrected data types  
- Label encoding for categorical features  
- Normalized numerical values  
- Outlier detection and removal  

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Correlation Analysis
- Weak relationships between most attributes (close to 0).  
- Notable negative correlation (-0.3) between **account balance** and **number of products**.  
➡️ Customers with higher balances tend to have fewer products.

### 🔹 Credit Score Distribution
- Normally distributed around **600–700**.  
➡️ Customer base has mostly “Fair to Good” credit scores.

### 🔹 Account Balance Distribution
- **Right-skewed** with most balances near **$0**.  
➡️ Few wealthy clients drive the long tail.

### 🔹 Estimated Salary
- **Uniform distribution** (unrealistic for real-world).  
➡️ Likely synthetic/generated feature.

### 🔹 Age Distribution
- Roughly **normal**, centered at **30–50 years**.  
➡️ Middle-aged adults dominate.

### 🔹 Tenure Distribution
- Relatively uniform with slight peak at **10 years**.  
➡️ Suggests consistent acquisition and loyal segment.

### 🔹 Number of Products
- Most customers use only **1–2 products**.  
➡️ Opportunity for **cross-selling and upselling**.

### 🔹 Demographics & Product Adoption
- **France**: 50% of customers  
- **Gender**: ~55% Male, balanced base  
- **Credit Card Ownership**: 70%  
- **Active Members**: 31%  
- **Churn Rate**: 20%  
➡️ Retention is decent but engagement needs improvement.

---









