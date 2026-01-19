# 📊 Customer Churn Analysis Dashboard

## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses as it directly impacts revenue and long-term growth.  
This project analyzes customer churn data to identify **high-risk customers**, understand **key churn drivers**, and provide **actionable insights** to improve customer retention.

The project follows an **end-to-end data analytics workflow**, using **Python** for data cleaning and exploratory data analysis (EDA) and **Power BI** for building interactive, business-ready dashboards.

---

## 🎯 Business Problem
The business is experiencing a high customer churn rate. Management wants to understand:
- Why customers are leaving the service  
- Which customer segments are most likely to churn  
- What actions can be taken to reduce churn and improve retention  

---

## 🎯 Objectives
- Calculate overall churn rate and customer risk metrics  
- Identify key factors influencing churn such as contract type, tenure, services, and payment method  
- Segment customers based on churn risk  
- Visualize churn patterns using interactive dashboards  
- Convert data findings into meaningful business insights and recommendations  

---

## 🧰 Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI**: Data modeling, DAX measures, interactive dashboards  
- **Jupyter Notebook**: Data analysis and exploratory data analysis (EDA)  

---

## 📂 Dataset Description
The dataset contains customer-level information including:
- Customer demographics (gender, senior citizen, partner, dependents)  
- Services subscribed (internet service, tech support, online security, device protection)  
- Account information (contract type, tenure, payment method, billing)  
- Churn status (Yes / No)  

Each row represents a single customer and their subscription details.

---

## 🧹 Data Cleaning & Preparation
The following steps were performed using Python:
- Removed or handled missing and inconsistent values  
- Converted categorical variables into appropriate formats  
- Verified numerical columns such as tenure and charges  
- Prepared a clean dataset for analysis and Power BI dashboarding  

---

## 📊 Exploratory Data Analysis (EDA)
EDA was conducted to understand customer behavior and churn patterns:
- Overall churn distribution  
- Churn rate by contract type  
- Churn vs tenure analysis  
- Churn by internet service type  
- Churn by payment method  
- Impact of additional services on churn  

The insights from EDA were later validated and visualized in Power BI dashboards.

---

## 📈 Power BI Dashboards

### 🔹 Churn Dashboard
Provides a high-level overview of churn performance, including:
- Total customers  
- Customers at risk  
- Overall churn rate  
- Monthly and yearly charges  
- Customer demographics and service usage  

### 🔹 Customer Risk Analysis Dashboard
Focuses on identifying high-risk customer segments by analyzing:
- Churn rate by internet service  
- Churn by contract type  
- Churn by tenure duration  
- Revenue contribution from churned customers  
- Impact of payment methods on churn  

---

## 📓 Python Analysis Notebook
- **File:** `Telco_Customer_Churn_Analysis.ipynb`  
- Used for data loading, cleaning, exploratory analysis, and insight generation  
- Serves as the analytical foundation for the Power BI dashboards  

---

## 🔍 Key Insights
- Customers with **month-to-month contracts** have the highest churn rate  
- **Low-tenure customers** are significantly more likely to churn  
- **Fiber optic internet users** show higher churn compared to DSL users  
- **Electronic check** is the most common payment method among churned customers  
- Customers without **Tech Support, Online Security, or Device Protection** churn more frequently  
- Gender has minimal impact on churn, while **senior citizens churn less**  

---

## 💡 Business Recommendations
- Encourage long-term contracts through discounts or loyalty incentives  
- Introduce targeted retention campaigns for low-tenure customers  
- Improve service quality and customer support for fiber optic users  
- Promote value-added services such as tech support and online security  
- Incentivize customers to switch from electronic check to auto-payment methods  

---


