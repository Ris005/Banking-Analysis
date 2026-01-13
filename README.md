#  Banking Risk Analytics Dashboard

##  Overview
This repository showcases a **Banking Risk Analytics Dashboard** built in **Power BI**, designed to help financial institutions make smarter lending decisions.  
By combining **data cleaning, exploratory analysis, and interactive dashboards**, the project highlights how banks can reduce risk and improve client engagement.

---

##  Problem Statement
Banks often struggle to identify whether a loan applicant will repay on time.  
This project addresses that challenge by analyzing client and banking data, then visualizing key risk indicators to support **data-driven lending strategies**.

---

##  Solution Highlights
- Built **interactive dashboards** in Power BI for loan, deposit, and client analysis.  
- Applied **EDA techniques** to uncover trends in client income, deposits, and loan repayment behavior.  
- Cleaned and transformed raw banking data with calculated columns and measures.  
- Designed **KPIs** to track loans, deposits, fees, and client engagement.  
- Delivered clear visual insights for decision-makers in the banking sector.

---

##  Dataset
The dataset includes multiple relational tables:
- **Banking Relationship**
- **Client-Banking**
- **Gender**
- **Investment Advisor**
- **Period**

Tables are linked via **primary and foreign keys**, ensuring consistency across dashboards.

---

##  Data Preparation
- Added `Engagement Timeframe` and `Engagement Days` to measure client tenure.  
- Created `Income Band` bins (`Low < 100000`, `Mid < 300000`).  
- Defined `Processing Fees` based on fee structure.  
- Applied calculated functions (`SUM`, `DISTINCTCOUNT`, `SUMX`, `SWITCH`, `DATEDIFF`) for KPIs.  
- Conducted **EDA** to identify outliers, distribution patterns, and correlations between deposits, loans, and fees.

---

##  Key Metrics & KPIs
- **Total Clients** → Distinct count of clients  
- **Total Loan** → Bank Loan + Business Lending + Credit Card Balance  
- **Total Deposit** → Bank Deposit + Savings + Foreign Currency + Checking Accounts  
- **Total Fees** → Loan × Processing Fees  
- **Engagement Length** → Client engagement days  
- **Credit Card Balance** → Outstanding credit card debt  

---

##  Visualizations
- **Home Dashboard** → High-level KPIs  
- **Loan Analysis** → Loan distribution by client, gender, and type  
- **Deposit Analysis** → Deposits across accounts and investors  
- **Summary Dashboard** → Consolidated insights  

---

##  Conclusion
This project demonstrates how **data visualization + EDA** can transform raw banking data into actionable insights.  
The dashboard empowers banks to:
- Assess loan repayment risks  
- Identify client engagement trends  
- Compare deposits and loans across demographics  

---

##  Future Enhancements
- Nationality-based loan comparisons  
- Client acquisition strategies by bank type (private vs public)  
- Advanced predictive models for loan default risk  
- Deeper segmentation of account types and investor profiles  

---

## ⚡ Tech Stack
- **Power BI** → Dashboarding & KPIs  
- **SQL** → Data cleaning & transformations  
- **DAX** → Calculated measures  
- **EDA (Exploratory Data Analysis)** → Trend discovery & anomaly detection  
- **Excel** → Initial data exploration & preprocessing  

---

