# User behavior and card usage analysis

## Project Overview
This project analyzes **user demographics, card ownership, and transaction behavior** using **DuckDB** inside a **Jupyter Notebook**, with interactive dashboards built in **Looker Studio**.   
The dataset consists of three main tables:
- **Users** → demographic & financial information  
- **Cards** → card portfolio (brand, type, credit limit, expiry, security features)  
- **Transactions** → transaction-level data (amount, channel, merchant, MCC)  

Goals:
- Understand user profiles and demographics
- Analyze card portfolio by brand/type
- Explore transaction patterns across channels, card types, and user segments
- Identify inactive users
- Present insights interactively via Looker Studio

---
## Key Analyses & Insights

### Users
- User Count by Gender  
- User Count by Age Group  
- Credit Score Distribution  
- User Geographic Distribution  

### Cards
- Card Brand by Card Type  
- Card Count by Card Type and Card Brand  
- Card Count by Card Type  

### Transactions
- Transaction Count and Total Amount by Use Chip  
- Top 10 MCC by Transaction Count  
- Top 10 MCC by Total Amount  
- Transaction Count and Total Amount by Card Type × Channel (Use Chip)  
- Transactions by Gender, Card Type, and Use Chip  
- Transaction Count and Total Amount by Card Type × Brand  
- Transaction Count and Total Amount by Gender × Card Type  
- Users Without Transactions / Inactive Users  

---

## Tech Stack
- **Database**: Duckdb 
- **Visualization**: Looker Studio 
- **ETL & Cleaning**: Python (Pandas)  

---


## Looker Dashboard link 
[Dashboard](https://lookerstudio.google.com/reporting/38079583-f287-4f24-8211-5dd536514516)