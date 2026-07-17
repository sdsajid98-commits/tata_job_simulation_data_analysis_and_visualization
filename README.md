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

---

## 🧠 Key Insights Delivered

| Insight | Business Implication |
| :--- | :--- |
| **November 2011 was the peak sales month** | The surge was driven primarily by [Country] and [Product]. Replicate this campaign in other regions. |
| **Top 10 countries (excluding UK) represent XX% of international revenue** | Focus expansion efforts on the top 3 countries first. |
| **Top customer concentration risk: Top 5 customers contribute X%** | Diversify the customer base before entering new markets. |
| **Repeat customer rate: XX%** | Launch retention campaigns at Day 45 post-purchase to shorten re-order cycles. |
| **Product preferences vary significantly by region** | Localize inventory and marketing for each expansion target. |

---

## 🚀 How to Use This Repository

1. Clone the Repository:
   git clone https://github.com/yourusername/tata-expansion-strategy.git

2. Open the Power BI File:
   Open Tata_Expansion_Strategy.pbix in Power BI Desktop.

3. Explore the Dashboards:
   Navigate through the 4 pages to see the analysis. Use slicers to filter by country, product, or customer.

4. Review the DAX Measures:
   All custom measures are available in the Measures table within the Power BI model.

---



## 📈 Future Enhancements

- [ ] Add forecasting (ARIMA or Power BI native forecast) to predict 2012 revenue.
- [ ] Incorporate profitability analysis (margins by product/country).
- [ ] Build a cohort analysis to track customer retention over time.
- [ ] Add a "What-If" parameter to simulate revenue impact of entering new countries.

---

## 💬 Acknowledgments

- **Tata Group & Forage** for providing the job simulation and business context.
- **UCI Machine Learning Repository** for the Online Retail dataset.

---

## 👤 Author

**Your Name**  
LinkedIn: https://linkedin.com/in/yourprofile  
GitHub: https://github.com/yourusername  
Data Analyst | Power BI Developer | Business Intelligence Enthusiast

---

*This project was completed as part of a job simulation and is intended for portfolio purposes only. All insights are based on the provided dataset and do not represent actual Tata Group business strategies.*
