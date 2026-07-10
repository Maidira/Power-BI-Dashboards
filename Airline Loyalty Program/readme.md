# ✈️ Airline Loyalty Program Analytics Dashboard

---

# 📌 Project Overview

This project transforms raw airline customer and flight data into an interactive business intelligence solution.

---

# 🎯 Business Objectives

- Monitor customer growth and loyalty program adoption
- Track active members and customer churn
- Analyze flight activity and reward redemption
- Measure Customer Lifetime Value (CLV)
- Compare current performance against previous periods
- Identify high-value customer segments
- Enable data-driven business decisions through interactive dashboards

---

# 📊 Dashboard Pages

## 1️⃣ Executive Dashboard

Provides a high-level summary of overall business performance.

### KPIs

- Total Customers
- Active Members
- Total Flights
- Average Customer Lifetime Value
- Redemption Rate
- YoY Flight Growth

### Visuals

- Flight Trend
- Reward Points Trend
- Customer Distribution by Loyalty Tier
- Customer Distribution by Province
- Customer Distribution by City
- Customer Lifetime Value by Loyalty Tier

---

## 2️⃣ Customer & Loyalty Analysis

Focuses on customer demographics and segmentation.

### KPIs

- Total Customers
- Average CLV
- Average Salary
- Average Flights
- Average Distance Travelled

### Visuals

- Customers by Education
- Customers by Gender
- Average CLV by Province
- Average CLV by Loyalty Tier
- Flights by Loyalty Tier
- Salary vs Customer Lifetime Value (Scatter Plot)

---

## 3️⃣ Loyalty Program Performance

Analyzes enrollment, retention, and customer loyalty.

### KPIs

- New Enrollments
- Cancellations
- Points Redeemed
- Net Growth
- Churn Rate

### Visuals

- Monthly Enrollments
- Enrollments by Type
- Points Redeemed by Loyalty Tier
- Monthly Cancellations
- Cancellations by Loyalty Tier
- Churn Rate by Province

---

## 4️⃣ Time Intelligence Dashboard

Compares historical performance using DAX Time Intelligence.

### KPIs

- Flights Last Year
- Flights YoY %
- Flights YTD
- Flights QTD
- Reward Cost

### Visuals

- Monthly Flights vs Previous Year
- Monthly Flight Growth (YoY)
- Monthly Reward Redemption Cost
- Flight Volume Trend
- Reward Points Redeemed vs Previous Year
- Reward Cost (YTD vs Previous Year)

---

# 🛠 Data Model

The solution follows a **Star Schema** design.

### Fact Tables

- Customer Flight Activity

### Dimension Tables

- Customer Loyalty History
- Calendar

The Calendar table was created dynamically and includes:

- Year
- Quarter
- Month
- Month Short
- Month Number
- Year Month
- Start of Month
- Start of Quarter
- Start of Year

---

# 📌 Key Business Insights

- Monitor customer retention over time
- Identify provinces with the highest customer concentration
- Compare loyalty tiers based on customer lifetime value
- Analyze reward redemption trends
- Track monthly enrollment and cancellation patterns
- Evaluate year-over-year flight performance
- Measure overall loyalty program effectiveness

---

# 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Star Schema
- Time Intelligence
