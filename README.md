# Customer Churn Analysis – Telecom Company

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-Insight-orange?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## Project Overview
This project analyzes customer churn for a fictional telecommunications company to identify key factors associated with customer cancellations and revenue loss. The analysis focuses on understanding how contract types, promotional offers, service add-ons, customer tenure, and churn reasons impact customer retention.

**Goal:** Generate actionable, data-driven insights to support customer retention strategies and minimize revenue leakage.

![Project Overview](screenshots/project_overview.png)

---

## Business Problem & Context
Customer churn is a major challenge for telecommunications companies, as retaining existing customers is significantly more cost-effective than acquiring new ones.

**Key Objectives:**
- **Identify Risks:** Pinpoint high-risk customer segments based on behavior and contract type.
- **Analyze Drivers:** Understand the main reasons driving customers to leave (competitors, service quality, etc.).
- **Assess Impact:** Evaluate the financial impact of cancellations on monthly revenue.

---

## Dataset Description
- **Total Records:** 7,044 unique customers.
- **Scope:** Customer activity tracking during a single fiscal quarter.
- **Key Features:**
  - **Demographics:** Age, Gender, Dependents.
  - **Account Info:** Contract Type, Payment Method, Tenure.
  - **Services:** Internet Service, Online Security, Tech Support.
  - **Churn Metrics:** Churn Label, Churn Reason.

---

## Analysis Steps & Key Insights

### 1. Tenure vs. Churn Behavior
We analyzed the relationship between customer longevity (Tenure) and their likelihood to churn.
* **Insight:** Customers on **Month-to-Month contracts** exhibit the highest churn volume.
* **Insight:** **New customers** (low tenure) are at the highest risk of leaving within the first few months.

![Tenure vs Churn](screenshots/Tenure_vs_Churn.png)

### 2. Revenue Loss Analysis
* **Insight:** The majority of revenue loss stems from short-term (month-to-month) customers.
* **Insight:** **"Competitor made better offer"** is a primary stated reason for churn, indicating pricing sensitivity.

![Lost Revenue](screenshots/lost_revenue_by_churn_reason_and_contract.png)

### 3. Service Impact on Retention
* **Insight:** Customers **without Online Security** or Tech Support add-ons are significantly more likely to churn compared to those who subscribe to these services.

![Avg Monthly Revenue](screenshots/avg_monthly_revenue_vs_long_distance.png)

---

## Business Recommendations
1. **Contract Incentives:** Design targeted offers to encourage month-to-month users to switch to 1-year or 2-year contracts.
2. **Onboarding Strategy:** Implement a robust onboarding program for new customers (0-6 months tenure) to reduce early churn.
3. **Value-Added Services:** Aggressively promote **Online Security** and **Tech Support** bundles, as these services act as "sticky" features that improve retention.
4. **Competitive Pricing:** Monitor competitor offers closely and create counter-offers for high-value customers at risk of leaving for better prices.

---

## Tools Used
- **Microsoft Excel:** Data Cleaning, Pivot Tables.
- **Data Visualization:** Interactive Dashboards & Charts.
- **Business Analytics:** Root Cause Analysis, Trend Identification.

---

## Author
**Created by Abdelrahman Diaa** *Aspiring AI & GeoAI Engineer | GIS Student blending Spatial Analysis with Data Science.*

Connect with me on LinkedIn:  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abdelrahman-diaa-080496334/)
