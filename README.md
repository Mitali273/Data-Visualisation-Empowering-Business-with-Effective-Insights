📊 Online Retail Data Visualization — Empowering Business with Effective Insights

A data analytics project simulating a real-world consulting engagement: cleaning a UK-based online retailer's transaction data and building Tableau visualizations to answer key business questions from the CEO and CMO.


This project was completed as part of the Tata Group (Tata iQ) Data Visualization Job Simulation, hosted on Forage.




🧾 Project Overview

An online retail store hired a data consultant to analyze its sales data and uncover insights that would help leadership plan for the upcoming year. The CEO and CMO had specific, distinct priorities:


The CEO wanted to understand revenue trends and where to expand geographically.

The CMO wanted to understand top-performing markets and high-value customers, to guide marketing strategy.


This project covers the full workflow — from raw, messy transaction data to a clean dataset, to four polished Tableau visualizations answering each leadership question.


📁 The Dataset

DetailValueRecords~541,909 transactionsColumns8 (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country)Time Period2010–2011Business TypeUK-based online retailer


🧹 Data Cleaning Approach

Rather than applying one blanket cleaning rule to the entire dataset, cleaning was tailored to each business question — preserving as much valid data as possible for charts that didn't need every column.

StepRule AppliedReasonQuantity CheckRemoved rows where Quantity < 1These were returns, cancellations, or data entry errorsUnit Price CheckRemoved rows where UnitPrice < $0Negative prices are data errorsCustomer IDKept blank CustomerID rows for country/time-based charts; excluded them only for the customer-level chartRevenue can't be attributed to an unknown customer, but other charts don't need this column


❓ Business Questions & Key Insights

1️⃣ Monthly Revenue Trend (2011) — Asked by the CEO

Question: What does the monthly revenue trend look like, and what seasonal patterns can inform next year's forecast?

Insight: Revenue stayed steady from January–August, then surged from September onward, peaking in November at $1.51M — nearly double the typical month. This points to strong holiday-season demand.

2️⃣ Top 10 Countries by Revenue & Quantity (Excluding UK) — Asked by the CMO

Question: Which countries generate the highest revenue outside the UK, and how does quantity sold compare?

Insight: The Netherlands and Ireland are nearly tied for the top spot, with Germany and France close behind — together, these four markets drive the majority of non-UK revenue.

3️⃣ Top 10 Customers by Revenue — Asked by the CMO

Question: Who are the highest revenue-generating customers, and how should the business prioritize retention?

Insight: Two customers generate significantly more revenue than the rest of the top 10 combined — highlighting a customer concentration risk worth addressing with a dedicated retention strategy.

4️⃣ Product Demand by Region (Excluding UK) — Asked by the CEO

Question: Which regions show the strongest product demand, to guide expansion planning?

Insight: Beyond the established European base, Sweden, the Channel Islands, and Australia show standout demand — flagging them as strong candidates for expansion.


🛠️ Tools & Skills Used


Excel — data exploration, validation checks, and cleaning
Tableau — data visualization and dashboard building
Data Storytelling — translating raw numbers into business recommendations
Stakeholder-Focused Analysis — tailoring cleaning and visuals to each decision-maker's actual question



💡 Recommendations Delivered


Prepare inventory and marketing earlier (around August) ahead of the Sept–Nov seasonal peak
Protect the core four markets (Netherlands, EIRE, Germany, France) while piloting expansion in Sweden, the Channel Islands, and Australia
Build a key-account retention program for top revenue-generating customers
Improve Customer ID capture at checkout to enable deeper future segmentation
