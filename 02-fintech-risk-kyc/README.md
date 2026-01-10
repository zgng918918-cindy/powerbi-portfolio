FinTech Risk & KYC Monitoring Dashboard

This project simulates a real-world FinTech / Banking Transaction Monitoring system used by Risk, Fraud and Compliance teams to detect suspicious activities such as money laundering, fraud and sanctions breaches.

The dashboard is built using Power BI on top of a multi-table transactional data model representing customers, merchants, payments and AML/Fraud alerts.

Business Questions Answered

This dashboard helps answer:

- How many transactions are being processed?
- How many are flagged for AML or Fraud?
- Is the alert volume increasing or decreasing over time?
- Which countries have the highest financial risk exposure?
- Which industries have the most blocked funds?
- What types of alerts (AML vs Fraud) dominate operational workload?
- Which transactions are currently under investigation?

Data Model

The model follows a **bank-grade star schema**:

| Fact Tables | Dimension Tables |
|------------|------------------|
| Transactions | Customers |
| Alerts | Merchants |
|  | Calendar |

Two different date contexts are handled using **active and inactive relationships**:
- Transaction Date (payments)
- Alert Date (compliance investigations)

This allows accurate trend analysis for both payments and alerts.

Key KPIs

- Total Transactions  
- Alert Count  
- Alert Rate %  
- High Risk %  
- Average Risk Score  
- Blocked Amount  

Visuals

- Alerts Trend by Month  
- AML vs Fraud workload  
- Risk Exposure by Country  
- Blocked Funds by Industry  
- Alert Table (case-level investigation)

Skills Demonstrated

- Power BI Data Modeling  
- Time Intelligence (USERELATIONSHIP)  
- DAX Measures  
- Risk & Compliance Analytics  
- FinTech Transaction Monitoring  
- Dashboard UX Design  

Files

- `Risk_KYC_Dashboard.pbix` – Interactive Power BI report  
- `Overview.png` – Dashboard overview  
- `Risk Exposure.png` – Risk exposure by country  
- `Alert Table.png` – Investigation-level detail  


This project demonstrates how FinTech and Banking teams monitor financial crime risk, customer exposure and compliance operations using modern BI tools.
