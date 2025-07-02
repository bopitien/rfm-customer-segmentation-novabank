# 📊 Case Study: Enhancing Customer Strategy with RFM Segmentation

## About the Project

This project focuses on improving customer retention and targeting for **NovaPay**, a digital-first consumer finance and payments platform. While NovaPay had a growing customer base and increasing transaction volume, the company lacked visibility into customer engagement patterns — and more importantly, who their most valuable customers really were.

To solve this, I applied **RFM (Recency, Frequency, Monetary)** analysis using Python to segment customers based on their behavior. This segmentation forms the foundation for smarter, personalized marketing and proactive churn management.

---

## 🔍 Business Challenge

NovaPay faced three core challenges:

- **Churn Risk**: Many customers were becoming inactive. Retention efforts were reactive instead of targeted.
- **Lack of Personalization**: All users were treated the same, regardless of value or behavior.
- **Poor Resource Allocation**: Marketing and service budgets were spread evenly, without knowing which customers mattered most.

---

## 🎯 Project Objectives

- Segment NovaPay’s customer base using RFM scoring
- Identify high-value, at-risk, and new customer segments
- Calculate Estimated Customer Lifetime Value (CLV) per segment
- Recommend marketing actions for retention, engagement, and ROI improvement

---

## 📦 Data Description

The dataset includes anonymized transaction records and basic customer demographics. Key fields:

- TransactionID: Unique transaction reference  
- CustomerID: Unique customer identifier  
- TransactionDate: Date of each transaction  
- TransactionAmount: Amount spent  
- TransactionTime: Unix timestamp  
- CustomerDOB, Gender, Location: Customer profile info  
- CustAccountBalance: Current account balance

---

## ⚙️ Tech Stack

- **Language**: Python  
- **Libraries**:  
  - pandas, numpy — data wrangling  
  - matplotlib, seaborn — visualization  
  - datetime — recency calculation

---

## 🔧 Project Approach

### 1. Data Cleaning & EDA
- Checked for duplicates, missing values, and outliers
- Explored transaction behavior trends and distributions

### 2. RFM Scoring
- **Recency**: Days since last transaction  
- **Frequency**: Number of transactions  
- **Monetary**: Total spend  

Each metric was ranked into quintiles (1–5), creating a composite RFM score.

### 3. Segment Definition
Grouped customers into intuitive behavior-based segments like:
- Champions
- Loyal
- At Risk
- Hibernating
- New
- Others

### 4. CLV Estimation
Used a simple CLV formula that factors in average purchase value, frequency, and recency to estimate future value potential per customer.

### 5. Insights & Visualizations
Created heatmaps, pie charts, and CLV bar plots to interpret behavior and value across segments.

---

## 📌 Key Takeaways

- **Champions** and **Big Spenders** are highly valuable and should be prioritized with exclusive perks.
- **Loyal** customers show consistent engagement and form the largest reliable revenue base.
- **At Risk** and **Hibernating** segments have decent spend history but low recency — ripe for reactivation campaigns.
- **New** customers are growing — they require nurturing to increase frequency and loyalty.
- **Others** segment contributes least and should receive low-cost, broad campaigns if any.

---

## 🧠 Skills Demonstrated

- Practical customer segmentation using behavioral metrics
- Business insight generation through CLV modeling
- Real-world application of RFM in customer strategy
- Visual storytelling with Python

---

## ✅ What This Project Shows

This project goes beyond code — it demonstrates how data can shape business decisions. With just transaction data and a few lines of logic, NovaPay now has:

- Clear customer personas
- Tailored marketing strategies
- A roadmap for retention and revenue growth

---

🔗 [LinkedIn](https://linkedin.com/in/pascalbrume) | 🌐 [Portfolio](https://pascalbrume.netlify.app/)
