# Customer RFM Segmentation & Value Analysis

An end-to-end customer segmentation project using Python, RFM analysis, and Power BI to understand customer behaviour, identify high-value customers, and find opportunities for customer retention and re-engagement.

---

## 1. Project Objective

The objective of this project is to understand customer purchasing behaviour and identify different customer groups based on their **Recency, Frequency, and Monetary (RFM)** behaviour.

The analysis helps answer questions such as:

- Who are the highest-value customers?
- Which customers purchase frequently?
- Which customers have not purchased recently?
- Which customers have potential for further engagement?
- How is revenue distributed across different customer segments?

The final goal is to turn transaction data into **customer-level insights that can support retention and marketing decisions.**

---

## 2. Key Insights

The final Power BI dashboard provided the following insights:

- The analysis covers **5,878 customers** with total customer revenue of approximately **£17.37M**.
- **Champions** are the largest value-driving segment, with **1,297 customers** generating approximately **£11.86M** in revenue.
- Champions have an average purchase frequency of **17.1** and average recency of around **20 days**, showing strong and recent purchasing activity.
- **At Risk** customers include **1,067 customers**, with an average recency of around **380 days** and approximately **£1.92M** in revenue.
- **Inactive / Low Value** customers account for **1,280 customers**, with an average recency of around **467 days** and average purchase frequency of only **1.2**.
- **Potential Customers** have relatively recent activity, with average recency of around **28 days**, but their average purchase frequency is only **1.5**.
- Revenue is highly concentrated among the **Champions** segment, while At Risk and Inactive customers highlight opportunities for retention and re-engagement.

---

## 3. Tech Stack

| Tool | Purpose |
|---|---|
| **Python** | Data cleaning, preparation, analysis and RFM calculation |
| **Pandas** | Data manipulation and customer-level aggregation |
| **NumPy** | Numerical calculations and data processing |
| **Matplotlib** | Exploratory data visualization |
| **Jupyter Notebook** | Developing and documenting the analysis |
| **Power BI** | Building the interactive dashboard and presenting business insights |
| **DAX** | Creating KPIs and calculated measures |

### Why these tools?

**Python** was used to clean the transaction data and calculate customer-level RFM metrics.

**Pandas and NumPy** helped with data manipulation, aggregation and calculations.

**Matplotlib** was used during exploratory data analysis to understand patterns in the data.

**Power BI** was used to convert the analysis into an interactive dashboard that can be used to explore customer segments, revenue and purchasing behaviour.

**DAX** was used to create measures such as total customers, total revenue, average customer spend, average recency and average frequency.

---

## 4. Dashboard Purpose & Features

### Business Problem

A business can have thousands of customers with very different purchasing behaviours. Looking only at total sales does not show which customers are valuable, loyal, inactive or at risk of being lost.

The purpose of this dashboard is to provide a clear view of **customer value, purchasing behaviour and engagement**.

### Dashboard Goal

The dashboard uses RFM segmentation to help the business:

- Identify high-value customers
- Understand customer purchasing behaviour
- Identify customers who may need re-engagement
- Compare revenue contribution across customer segments
- Understand customer recency, frequency and monetary behaviour
- Support customer retention and marketing strategies

### Dashboard Pages

#### Page 1: Executive Overview

Provides a high-level view of the customer base through:

- Total Customers
- Total Revenue
- Average Customer Spend
- Average Purchase Frequency
- Average Recency
- Customer distribution by RFM segment
- Revenue contribution by segment
- RFM performance by segment
- Average customer spend by segment

#### Page 2: RFM Customer Segmentation

Provides a detailed comparison of the six customer segments:

- Champions
- Loyal Customers
- At Risk
- Potential Customers
- Regular / Mid-Value
- Inactive / Low Value

The page compares customer count, revenue, recency, frequency and monetary value across segments.

#### Page 3: Customer & Revenue Insights

Focuses on deeper customer behaviour and RFM patterns through:

- Customer distribution by RFM score
- Average recency by segment
- RFM score components by segment
- Key business insights from the analysis

---

## 5. Dataset Origin

The dataset used in this project is **Online Retail II**, obtained from the **UCI Machine Learning Repository**.

The dataset contains **1,067,371 transaction records** from a UK-based non-store online retailer. The transactions cover the period from **December 2009 to December 2011** and mainly contain giftware-related purchases.

Important fields include:

- Invoice Number
- Product Code
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The raw transaction data was cleaned and transformed into a customer-level RFM dataset containing **5,878 customers**, which was then used to build the Power BI dashboard.

**Dataset Source:**  
[UCI Machine Learning Repository - Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

**Dataset:** Online Retail II  
**Creator:** Daqing Chen  
**DOI:** 10.24432/C5CG6D  
**License:** CC BY 4.0

---
