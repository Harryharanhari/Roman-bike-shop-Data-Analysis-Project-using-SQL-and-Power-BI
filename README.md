# 🚲 Roman Bike Shop Data Analysis Dashboard

## 📌 Project Overview
This project focuses on analyzing bike-sharing business performance using **SQL** for data preparation and **Power BI** for interactive visualization. The goal is to uncover revenue patterns, profitability trends, rider behavior, and pricing insights to support data-driven decision-making.

The analysis consolidates multi-year bike share data, calculates revenue and profit metrics, and presents insights through a clean, business-ready Power BI dashboard.

---

## 🛠️ Tools & Technologies
- **SQL Server** – Data cleaning, transformation, and metric calculations  
- **Power BI** – Interactive dashboard design and KPI visualization  
- **Excel / CSV** – Source datasets  

---

## 🗂️ Dataset Description
The dataset includes:
- Ride date and hour (`dteday`, `hr`)
- Season and weekday
- Rider type (`casual`, `registered`)
- Total riders
- Pricing and cost data
- Revenue and profit (derived)

Multiple yearly tables were combined using SQL and enriched with cost data.

---

## 🧮 SQL Data Processing
Key SQL operations performed:
- Merged multi-year datasets using `UNION ALL`
- Joined cost tables to calculate **COGS**
- Derived business metrics:
  - `Revenue = riders × price`
  - `Profit = revenue − COGS`
- Prepared a clean analytical dataset for Power BI

---

## 📊 Power BI Dashboard Features
The dashboard provides:
- **Hourly Revenue Analysis** – Identifies peak earning hours
- **Monthly KPI Trends** – Revenue, profit, and rider growth over time
- **Seasonal Revenue Breakdown** – Performance across seasons
- **Rider Demographics** – Casual vs registered users
- **Key KPIs** – Total revenue, profit, riders, and profit margin

According to the dashboard insights, revenue peaks during **midday to early evening hours (10–15)**, with **Wednesday and Friday** consistently outperforming other days :contentReference[oaicite:0]{index=0}.

---

## 💡 Business Insights
- Midday and evening hours are the most profitable
- Registered riders contribute the majority of revenue
- Seasonal demand strongly influences total revenue
- Pricing adjustments can be tested with minimal risk using a phased approach

---

## 📈 Pricing Recommendation
Based on profit and demand trends:
- A **10–15% price increase** is recommended to test market sensitivity
- Incremental pricing helps avoid demand drop-offs
- Segmented pricing for casual vs registered riders can improve retention

---

## 🚀 How to Use This Project
1. Run the SQL scripts to prepare the analytical dataset
2. Open the Power BI file
3. Explore KPIs using slicers for year, season, and rider type
4. Use insights to guide pricing and operational decisions

---

## 📌 Conclusion
This project demonstrates how **SQL-driven data modeling** combined with **Power BI storytelling** can deliver actionable business insights. It reflects real-world analytics workflows used in data analyst roles.

⭐ If you find this project useful, feel free to star the repository!
