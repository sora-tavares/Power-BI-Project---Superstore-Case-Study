# 🛒 Superstore Sales Analysis | Power BI Dashboard

**Project Type:** Data Analysis & Dashboard Design  
**Tools Used:** Power BI, Excel, DAX  
**Dataset:** [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
**Focus Areas:** Exploratory Data Analysis (EDA), RFM Segmentation, Sales & Customer Insights

---

## 📊 Project Overview

This project explores sales performance and customer behaviour for a fictional retail chain using the **Superstore dataset**. Built in Power BI, the dashboard combines clean visuals, slicer interactivity, and segmentation logic to identify actionable opportunities in customer engagement and profitability.

---

## 🔍 Key Questions Explored

- Which regions, segments, and product categories drive the most profit?
- How does customer behavior vary across Recency, Frequency, and Monetary dimensions?
- What customer segments are most valuable — and which are at risk?
- How can we translate insights into data-driven business actions?

---

## 🧠 Analytical Highlights

- **RFM Segmentation** applied to 4,700+ customers using calculated columns in DAX
- Found that **over 60% of customers** were active within the last 30 days
- Identified high-frequency, high-monetary segments ideal for loyalty targeting
- Flagged low-recency, low-value customers as churn risks

---

## 🖼️ Dashboard Previews

### 📌 Sales Overview

![Sales Overview](Assets/sales_overview_screenshot.png)  
*High-level performance metrics with dynamic filters*

The West region generated the highest sales, but had lower profit margins compared to Central. Corporate segment consistently outperformed in profit contribution. Technology drives the most revenue.
![Sales Filters in Action](Assets/sales_overview_filters.gif)
*Switching between customer recency groups reveals that nearly 90% of sales come from customers who purchased within the last 30 days — strong short-term engagement, but with potential long-term retention risks.*
---

### 📌 RFM Segment Analysis

![RFM Segment Analysis](Assets/rfm_analysis_screenshot.png)  
*Customer segments based on Recency, Frequency, and Monetary score combinations*

Over 60% of customers are in the “Recent” group (purchased within 30 days), presenting a strong re-engagement opportunity.
![RFM Interaction](Assets/rfm_segment_interaction.gif)
*Filtering for “Champions” highlights high average order value and consistent sales, while “At Risk” customers make up over 40% of total sales — a critical revenue segment needing reactivation.*
---

### 📌 Recommendations & Action Plan

![Recommendations Tab](Assets/recommendations_tab.png)  
*Summary of strategic actions based on data insights*

---
## 📌 Key Findings

- The West region drives the highest sales, while the Central region achieves stronger profit margins.
- Technology products generate the most revenue; Office Supplies also perform well for upselling.
- Over 89% of sales come from customers active in the last 30 days, indicating strong recent engagement.
- “Champions” customers spend the most on average, while “At Risk” customers contribute over 40% of total revenue — making them a high-stakes segment.
- RFM segmentation enabled targeted strategies, such as loyalty campaigns for Champions and win-back actions for At Risk groups.

---
## 🧗 Challenges Faced

- Fine-tuning RFM segmentation logic to balance insight and simplicity
- Cleaning inconsistent data values (e.g. missing categories, duplicates)
- Designing clear visuals without overcrowding
- Learning DAX for calculated columns and RFM score logic
- Data inconsistency in the date field: To avoid skewed recency analysis, I applied a fixed cutoff date to simulate a consistent snapshot in time for RFM segmentation.
---

## ✅ Key Skills Demonstrated

- Data Cleaning & Preparation (Power Query)
- RFM Analysis & Customer Segmentation
- Dashboard Design & Slicer Interactivity
- DAX for calculated logic
- Visual Storytelling & Business Recommendations

---

## 📂 Resources

- 📦 [Original Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- 🖼️ Screenshots & GIFs: See `Assets/` folder
- 🗂️ Power BI file available in `Sourcecode (PowerBI)/`

---

## 🎯 Final Thoughts

This case study helped sharpen my ability to move beyond charts into **real business storytelling**. By combining RFM with interactivity, I was able to simulate how a retail team might use data to take strategic action — and that’s exactly the kind of work I want to keep doing.
