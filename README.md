# Tata Group Expansion Strategy Analysis

## 📌 Project Overview
This project was completed as part of the **Tata Group Job Simulation on Forage**. The CEO and CMO of a UK-based online retail store are planning an **international expansion strategy**. They needed data-driven insights to understand revenue drivers, customer behavior, product demand, and regional opportunities.

**Objective:** Provide actionable visualizations and analysis to answer key strategic questions about revenue, customers, products, and global expansion opportunities.

---

## 🎯 Key Business Questions Answered

### 1️⃣ Revenue Trend & Seasonality (2011)
**The Question:** What is the monthly revenue trend? Which months saw the biggest increase/decrease? Is there seasonality?

**My Analysis:**
- Built a time series line chart showing monthly revenue for 2011.
- Identified **November as the peak sales month**.
- Used a **Decomposition Tree** to drill into the root cause of November's surge—revealing which country and product contributed most to the increase.

**Key Visuals:**
- Monthly Revenue Line Chart
- Decomposition Tree (Nov Revenue by Country → Product)
![Revenue Trend & Seasonality](https://github.com/sdsajid98-commits/tata_job_simulation_data_analysis_and_visualization/blob/main/dashboard/dashboard-0001.jpg)


---

### 2️⃣ Top 10 Countries (Excluding UK)
**The Question:** Which are the top 10 revenue-generating countries? What is the quantity sold alongside revenue?

**My Analysis:**
- Filtered out the United Kingdom to focus on expansion opportunities.
- Identified the top 10 countries by revenue with quantity as a secondary metric.
- For each top country, determined the **most popular product** to understand local preferences.

**Key Visuals:**
- Top 10 Countries by Revenue (Bar Chart)
- Matrix/Heatmap showing Top Product per Country

![Top 10 Countries](https://github.com/sdsajid98-commits/tata_job_simulation_data_analysis_and_visualization/blob/main/dashboard/dashboard-0002.jpg)
---

### 3️⃣ Top Customers & Revenue Concentration
**The Question:** Who are the top customers? How much do they contribute? Is the business dependent on a few customers or diversified?

**My Analysis:**
- Ranked customers by revenue contribution.
- Analyzed customer concentration risk.
- Calculated **repeat customer rate** and **average time between repeat orders** to understand customer loyalty and engagement.

**Key Visuals:**
- Top 10 Customers (Pareto/Bar Chart)
- Repeat Rate Card Visual
- Histogram of Re-order Time Buckets
![Top 10 Customers](https://github.com/sdsajid98-commits/tata_job_simulation_data_analysis_and_visualization/blob/main/dashboard/dashboard-0003.jpg)
---

### 4️⃣ Global Demand & Expansion Opportunities
**The Question:** Which regions have the greatest demand? Where should the CEO expand?

**My Analysis:**
- Mapped global demand by quantity (excluding UK) to identify high-potential regions.
- Highlighted countries with highest and lowest quantity demand.
- Identified product preferences per region to inform localized expansion strategies.

**Key Visuals:**
- Global Map (Quantity by Country)
- Callout Boxes for Highest/Lowest Demand Countries

![Regional Analysis](https://github.com/sdsajid98-commits/tata_job_simulation_data_analysis_and_visualization/blob/main/dashboard/dashboard-0004.jpg]
---

## 📊 Dashboard Snapshot

| Page | Focus | Key Visuals |
| :--- | :--- | :--- |
| **Page 1** | Revenue & Seasonality | Line Chart + Decomposition Tree |
| **Page 2** | Top Countries & Products | Bar Chart + Matrix Heatmap |
| **Page 3** | Customer Analysis | Pareto Chart + Repeat Rate Cards |
| **Page 4** | Global Demand | Map + High/Low Callouts |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
| :--- | :--- |
| **Power BI Desktop** | Data transformation, visualization, and dashboard creation |
| **Power Query** | Data cleaning and preparation |
| **DAX** | Custom measures and calculated columns (e.g., Order Sequence, Days Since Previous Order, Customer Tiers, Top Products) |
| **Power BI Service** | Dashboard publishing and sharing |

---

## 📁 Dataset

**Source:** Online Retail Dataset (UCI Machine Learning Repository)  
**Time Period:** 2010–2011  
**Key Columns:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**Data Preparation:**
- Removed cancellations and negative quantities
- Filtered to 2011 data where required
- Excluded UK for expansion analysis
- Created calculated tables and measures for repeat customer analysis

 job simulation and is intended for portfolio purposes only. All insights are based on the provided dataset and do not represent actual Tata Group business strategies.*
