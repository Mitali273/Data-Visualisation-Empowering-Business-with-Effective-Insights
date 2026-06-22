# 📊 Online Retail Data Visualization — Empowering Business with Effective Insights

A data analytics project simulating a real-world consulting engagement: cleaning a UK-based online retailer's transaction data and building Tableau visualizations to answer key business questions from the CEO and CMO.

> This project was completed as part of the **Tata Group (Tata iQ) Data Visualization Job Simulation**, hosted on Forage.

---

## 🧾 Project Overview

An online retail store hired a data consultant to analyze its sales data and uncover insights that would help leadership plan for the upcoming year. The CEO and CMO had specific, distinct priorities:

- The **CEO** wanted to understand revenue trends and where to expand geographically.
- The **CMO** wanted to understand top-performing markets and high-value customers, to guide marketing strategy.

This project covers the full workflow — from raw, messy transaction data to a clean dataset, to four polished Tableau visualizations answering each leadership question.

---

## 📁 The Dataset

- **Records:** ~541,909 transactions
- **Columns:** 8 (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country)
- **Time Period:** 2010–2011
- **Business Type:** UK-based online retailer

---

## 🧹 Data Cleaning Approach

Rather than applying one blanket cleaning rule to the entire dataset, cleaning was tailored to each business question — preserving as much valid data as possible for charts that didn't need every column.

- **Quantity Check** — Removed rows where `Quantity < 1`. These were returns, cancellations, or data entry errors.
- **Unit Price Check** — Removed rows where `UnitPrice < $0`. A negative price is always a data error.
- **Customer ID** — Kept blank `CustomerID` rows for the country- and time-based charts, since they don't depend on customer identity. Excluded them only for the customer-level chart, since revenue can't be attributed to an unknown customer.

---

## ❓ Business Questions & Key Insights

### 1️⃣ Monthly Revenue Trend (2011) — *Asked by the CEO*
**Question:** What does the monthly revenue trend look like, and what seasonal patterns can inform next year's forecast?

**Insight:** Revenue stayed steady from January–August, then surged from September onward, peaking in November at **$1.51M** — nearly double the typical month. This points to strong holiday-season demand.

### 2️⃣ Top 10 Countries by Revenue & Quantity (Excluding UK) — *Asked by the CMO*
**Question:** Which countries generate the highest revenue outside the UK, and how does quantity sold compare?

**Insight:** The Netherlands and Ireland are nearly tied for the top spot, with Germany and France close behind — together, these four markets drive the majority of non-UK revenue.

### 3️⃣ Top 10 Customers by Revenue — *Asked by the CMO*
**Question:** Who are the highest revenue-generating customers, and how should the business prioritize retention?

**Insight:** Two customers generate significantly more revenue than the rest of the top 10 combined — highlighting a customer concentration risk worth addressing with a dedicated retention strategy.

### 4️⃣ Product Demand by Region (Excluding UK) — *Asked by the CEO*
**Question:** Which regions show the strongest product demand, to guide expansion planning?

**Insight:** Beyond the established European base, Sweden, the Channel Islands, and Australia show standout demand — flagging them as strong candidates for expansion.

---

## 🛠️ Tools & Skills Used

- **Excel** — data exploration, validation checks, and cleaning
- **Tableau** — data visualization and dashboard building
- **Data Storytelling** — translating raw numbers into business recommendations
- **Stakeholder-Focused Analysis** — tailoring cleaning and visuals to each decision-maker's actual question

---

## 💡 Recommendations Delivered

1. Prepare inventory and marketing earlier (around August) ahead of the Sept–Nov seasonal peak
2. Protect the core four markets (Netherlands, EIRE, Germany, France) while piloting expansion in Sweden, the Channel Islands, and Australia
3. Build a key-account retention program for top revenue-generating customers
4. Improve Customer ID capture at checkout to enable deeper future segmentation

---




Build a key-account retention program for top revenue-generating customers
Improve Customer ID capture at checkout to enable deeper future segmentation
