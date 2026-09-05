# 📊 Telco Customer Churn Analysis

An end-to-end Exploratory Data Analysis (EDA) project on a telecom customer dataset to identify the key drivers of customer churn and provide business recommendations using Python.

---

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

---

## 📌 Project Overview

Customer churn is a major challenge for telecom companies because losing existing customers directly impacts recurring revenue. This project analyzes customer demographics, subscription details, billing information, and service usage to understand which customer segments are most likely to churn.

**Goal:** Identify churn patterns and generate actionable business insights that can help improve customer retention.

---

## 🎯 Business Objective

- Clean and prepare the telecom customer dataset.
- Analyze customer churn across different customer segments.
- Identify the major factors contributing to churn.
- Understand the revenue impact of churn.
- Provide data-driven business recommendations.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Dataset Information

| Feature | Value |
|--------|------|
| Total Customers | **7,043** |
| Total Features | **21** |
| Target Variable | **Churn** |
| Missing Values | Handled during data cleaning |
| Duplicate Records | **0** |

---

## 📈 Business Questions Solved

1. What percentage of customers have churned?
2. Which contract type has the highest churn rate?
3. Does customer tenure influence churn?
4. Do customers with higher monthly charges churn more?
5. Which payment method has the highest churn rate?
6. Which internet service has the highest churn rate?
7. Which combination of contract type and internet service has the highest churn risk?
8. Are senior citizens more likely to churn?
9. What is the revenue impact of customer churn?
10. Does Total Spending Differ Between Churned and Retained Customers?

---

## 🔍 Key Findings

- **Overall Customer Churn Rate:** **26.54%** of customers have churned, while **73.46%** remain with the company.
- **Contract Type:** Month-to-Month customers have the highest churn rate, whereas Two-Year contracts have the lowest.
- **Customer Tenure:** Customers with shorter tenure are significantly more likely to churn.
- **Monthly Charges:** Churned customers have higher average monthly charges than retained customers.
- **Payment Method:** Customers using **Electronic Check** show the highest churn rate.
- **Internet Service:** **Fiber Optic** customers have the highest churn rate among all internet service types.
- **High-Risk Segment:** Customers with **Month-to-Month contracts + Fiber Optic service** have the highest churn risk.
- **Senior Citizens:** Senior citizens have a churn rate of **41.68%**, compared to **23.61%** for non-senior customers.
- **Revenue Impact:** Churn is concentrated among customers with higher monthly charges, increasing recurring revenue loss.
- **Total Charges:** Retained customers have significantly higher **Total Charges**, indicating greater lifetime revenue, while churned customers generally leave before generating high customer lifetime value.

---

## 💡 Business Recommendations

- **Promote long-term contracts** by offering discounts or bundled plans to Month-to-Month customers, as this segment has the highest churn rate.
- **Improve onboarding and early engagement** for customers with low tenure through welcome offers, proactive support, and personalized communication.
- **Enhance the Fiber Optic customer experience** by reviewing pricing, service quality, and network performance, since Fiber Optic customers show the highest churn risk.
- **Encourage automatic payment methods** by incentivizing customers to switch from Electronic Check to bank transfer or credit card auto-pay.
- **Launch targeted retention campaigns** for high-risk segments, especially **Month-to-Month + Fiber Optic** customers and **Senior Citizens**.
- **Prioritize high-value customer retention** by identifying customers with higher Monthly Charges and Total Charges, as losing them results in greater recurring and lifetime revenue loss.

---

## 📊 Project Outcome

This analysis identifies the most important customer segments driving churn and provides actionable insights that can help telecom companies improve customer retention and reduce revenue loss.

---

### 📁 Repository Contents

- `Telco_Customer_Churn_Analysis.ipynb` — Complete analysis notebook.
- `cleaned_telecom.csv` — Cleaned dataset used for analysis.
- `Dataset/` — Original telecom dataset.
- `images/` — Visualizations used in the project.
- `requirements.txt` — Python libraries required to run the notebook.
