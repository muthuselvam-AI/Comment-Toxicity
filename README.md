# 📱 PhonePe Pulse Dashboard

A Streamlit-based interactive dashboard built on PhonePe Pulse open data, visualizing India's digital payment trends across states, districts, and time periods.

Project Architecture:

PhonePe Pulse Dataset
        ↓
Data Extraction (Python)
        ↓
Data Cleaning & Transformation
        ↓
SQL Database Storage
        ↓
SQL Data Analysis
        ↓
Python Visualization
        ↓
Streamlit Interactive Dashboard

Data Processing Workflow

Step 1 – Data Extraction

Clone the PhonePe Pulse repository and extract JSON files.

Step 2 – Data Transformation

Convert JSON data into structured DataFrames using Python.

Step 3 – Database Storage

Create SQL tables and store processed data.

Step 4 – Data Analysis

Use SQL queries to analyze transaction trends.

Step 5 – Visualization

Create charts and graphs to represent insights.

Step 6 – Dashboard

Build a Streamlit dashboard for interactive exploration.


## 📊 Business Scenarios

| Scenario | Description |
|---|---|
| **Transaction Dynamics** | Top states, transaction type breakdown, quarterly trends |
| **Device Analysis** | Brand-wise user counts, market share, growth over time |
| **Insurance Growth** | State and type-wise insurance amounts, quarterly growth |
| **Market Expansion** | District-level transactions, top pincodes, India choropleth map |
| **User Engagement** | Registered users, app opens, engagement trends |

---

## 🗂️ Database Tables

`aggregated_transaction` · `aggregated_user` · `aggregated_insurance`
`map_transaction` · `map_user` · `map_insurance`
`top_transaction` · `top_user` · `top_insurance`

---

## 🔍 Filters

Use the sidebar to filter all charts by **State**, **Year**, and **Quarter**.

---

💡 Key Insights

Example insights from the analysis:

Southern states show higher digital payment adoption.
UPI dominates transaction categories.
Major metropolitan districts contribute a significant share of transactions.
Insurance adoption is increasing steadily across multiple states.

*Built with Streamlit · Data from [PhonePe Pulse](https://github.com/PhonePe/pulse)*
Author - Muthuselvam
