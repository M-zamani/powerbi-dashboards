# powerbi-dashboards

This repository contains business-focused Power BI dashboards built on top of SQL-based data analysis projects.

---

## 📊 Customer Revenue & Retention Dashboard

### Overview
This dashboard provides an executive-level view of customer revenue performance and retention trends.  
It was built using Power BI with a properly modeled date dimension to enable time intelligence metrics.

---

### Key KPIs
- Total Revenue
- Total Orders
- Active Customers
- Average Order Value (AOV)
- Month-over-Month Revenue Growth (%)

---

### Dashboard Preview
![Customer Revenue & Retention Dashboard](./images/customer_revenue_retention_dashboard.png)

---

### Key Insights
- Revenue trends highlight growth and volatility over time
- A small number of customers contribute a large share of revenue
- Month-over-month growth helps identify acceleration and decline periods
- Geographic breakdown supports market-level analysis

---

### Technical Highlights
- Star-schema data model
- Dedicated Date table for time intelligence
- DAX measures for MoM growth using DATEADD
- Interactive filters for date and country

---

### Related Analysis
- SQL analysis powering this dashboard:  
  👉 https://github.com/M-zamani/sql-analytics

---
### 📷 Dashboard Preview
![Dashboard](dashboard1.png)
![Filters](dashboard2.png)

## 👤 Author
**Mahmoud Zamani**  
Data Analyst | SQL | Power BI | Python  
Toronto, Canada
