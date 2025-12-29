# Walmart-Retail-Customer-Retention-Analytics
Power BI customer retention analytics project analyzing churn, loyalty, CLV, promotions, and channel performance for Walmart.
# Walmart Retail Customer Retention Analytics (Power BI)

## 📌 Project Overview
This project is a comprehensive Power BI analytics solution built to understand customer churn, retention, repeat purchases, loyalty effectiveness, and lifetime value for Walmart.

The goal is to help Walmart identify high-value customers, reduce churn, improve loyalty engagement, and optimize store and channel strategies.

---

## 🛠 Tools & Skills Used
- Power BI Desktop
- Power Query (ETL & Data Cleaning)
- DAX (Measures & Calculated Columns)
- Data Modeling (Star Schema)
- Interactive Dashboards & Slicers

---

## 📂 Dataset Used
- Customer Demographics
- Customer Transactions
- Store Locations
- Loyalty Program
- Churn Labelled Customers

---

## 🧩 Data Model
- One-to-Many:
  - Customer_Demographics → Transactions, Loyalty_Program, Churn_Labelled_Customers
- Many-to-One:
  - Transactions → Store_Locations

Star schema was used for performance and analytical clarity.

---

## 📊 Key Analysis & DAX Logic

### 1️⃣ Churn & Retention Metrics
- Churn Rate % = (Churned Customers / Total Customers) * 100
- Retention Rate %
- Active Customers

Insights:
- Almost 50% churn observed
- West region and Online channel show highest churn

---

### 2️⃣ Repeat Purchase Analysis
- Customer Segmentation:
  - Low (0–3)
  - Mid (4–8)
  - High (9+)
- Avg Purchase Frequency by Region, Age Group, Loyalty Tier

Insights:
- North & West show strongest repeat behavior
- Older age groups (55+) are more loyal

---

### 3️⃣ Promotion & Loyalty Impact
- % Promo Transactions
- Avg Amount with vs without promotion
- Points Earned vs Redeemed

Insights:
- Promotions do not increase average spend
- Low reward redemption indicates weak loyalty engagement

---

### 4️⃣ Store & Channel Performance
- Avg Transaction Amount by Store Type
- Churn Rate by Store Type
- Retention vs Store Opening Year

Insights:
- Sam’s Club customers have higher spend
- Neighborhood Market has highest churn

---

### 5️⃣ Customer Lifetime Value (CLV)
- CLV = Total Amount Spent / Membership Duration (Years)
- High vs Low CLV segmentation
- CLV vs Days Since Last Purchase

Insights:
- Very few customers generate majority of revenue
- Many high CLV customers are inactive for 200+ days

---

## 📈 Final Business Recommendations
- Prioritize High CLV & Repeat Customers for retention
- Improve Online channel experience
- Simplify reward redemption & personalize offers
- Auto-upgrade high spenders to premium tiers
- Focus on Neighborhood Market experience improvement

----

## 👤 Author
**Saumya Jain**  
Data Analyst | Power BI | Excel | SQL |Pyhton Business & Customer Analytics
