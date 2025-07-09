# 📊 Personal Loan Campaign Analysis – Thera Bank

## 🧾 Project Overview

This project focuses on analyzing customer data from **Thera Bank** to improve the targeting strategy for personal loan marketing campaigns. The goal is to identify patterns in customer demographics and banking behavior that influence loan acceptance, enabling the bank to increase conversion rates while minimizing marketing spend.

---

## 📁 Data Description

The dataset `Bank.xls` contains information on **5,000 customers**, including:

- **Demographic Features**: Age, Income, Family, Education
- **Banking Relationship**: Mortgage, Securities Account, Online Banking, Credit Card
- **Target Variable**: `Personal Loan` – indicates if a customer accepted the personal loan offer

Only **480 customers (9.6%)** accepted the loan, which makes this an **imbalanced classification problem**.

---

## 🎯 Project Objective

To analyze customer behavior and derive actionable insights that can help:

- Improve customer segmentation
- Increase the success rate of future personal loan campaigns
- Optimize targeting strategies using data-driven decision-making

---

## 🔄 Workflow & Analysis Steps

### 1. Data Import & Basic Inspection
- Loaded the dataset and examined its structure
- Checked for missing values, invalid entries, and data skewness

### 2. Age-wise Loan Acceptance Analysis
- Customers **over 55** and **under 23** were less likely to accept loans
- Cleaned negative or invalid age entries

### 3. Income-Based Segmentation
- Analyzed how income influences loan acceptance
- Segmented customers by income range for loan eligibility insights

### 4. Family Size & Education Analysis
- Studied the relationship between family size, education level, and loan decisions
- Compared education vs. income to detect patterns

### 5. Experience Column Fix
- Found **negative experience values** and handled outliers
- Visualized experience distribution to assess reliability

### 6. Correlation & Feature Selection
- Identified **strong correlation between Age and Experience**
- Dropped `Experience` to avoid redundancy and noise

### 7. Additional Feature Insights
- Analyzed impact of:
  - **Credit Card ownership**
  - **Securities Account**
  - **Online Banking usage**
  - **Account Type**
  
### 8. Handling Skewness
- Applied:
  - **Log Normal Transformation**
  - **Power Transformer**
- Used to normalize skewed variables and improve model performance

---

## ✅ Outcome

This analysis helped identify key customer segments more likely to respond to personal loan campaigns. It provides **targeted insights** that can guide **cost-efficient marketing efforts** and improve customer conversion rates.

---

## 🔧 Tools & Technologies Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **Microsoft Excel**
- **Jupyter Notebook**

---

## 📌 Key Skills Demonstrated

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering & Selection  
- Statistical Analysis  
- Data Transformation Techniques  
- Customer Segmentation  
- Business Insight Generation  
- Visualization & Reporting  

---

## 📍 Author

**Shivangi Yadav**  
[LinkedIn Profile](https://www.linkedin.com/in/shivi829)  
Email: yadavshivangi555@gmail.com

