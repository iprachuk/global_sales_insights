# Global Sales Insights

## 📋 Project Description

This project provides a comprehensive analysis of a global retail company's sales data using Python and Jupyter Notebook.

The analysis combines sales transactions, product information, and geographic data to explore customer behavior, product performance, regional trends, and logistics efficiency. The project aims to uncover actionable business insights and support data-driven decision-making.

---

# 🎯 Project Objectives

The project focuses on answering several business questions:

* Which product categories generate the highest revenue and profit?
* Which countries and regions are the most profitable?
* How do sales change over time?
* What is the relationship between delivery time and profitability?
* Which sales channels perform better?
* Are there seasonal sales patterns?
* Which product categories dominate different markets?
* How can the business improve profitability and growth?

---

# 🛠️ Technology Stack

* **Python 3.x**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly Express**
* **Google Colab**

---

# 📂 Project Structure

```
Global-Sales-Insights/
├── README.md
├── global_sales_insights.ipynb
├── events.csv
├── products.csv
└── countries.csv
```

---

# 📊 Data Sources

The project combines three datasets:

## Events Table

Contains transaction and order information:

* Order ID
* Product ID
* Country Code
* Order Date
* Ship Date
* Units Sold
* Unit Price
* Unit Cost
* Sales Channel

---

## Products Table

Contains product information:

* Product ID
* Product Category

---

## Countries Table

Contains geographic information:

* Country Name
* Country Code
* Region
* Sub-region

---

# 🧹 Data Preparation

Several preprocessing steps were performed:

## Data Cleaning

* Missing values analysis;
* Country code imputation;
* Invalid records removal;
* Data consistency checks.

## Data Type Conversion

* Date columns converted to datetime;
* Numeric fields corrected;
* Text normalization.

## Duplicate Detection

* Duplicate records checked and removed.

## Data Integration

Three datasets were merged into a single analytical dataset using foreign keys.

---

# 📈 Feature Engineering

Additional business metrics were calculated:

* Revenue;
* Total Cost;
* Profit;
* Delivery Time;
* Month;
* Year;
* Day of Week.

---

# 📊 Exploratory Data Analysis

## Main Business Metrics

The project calculates:

* Total revenue;
* Total profit;
* Total cost;
* Total orders;
* Total units sold;
* Number of active countries.

---

## Product Analysis

* Revenue by category;
* Cost by category;
* Profitability comparison;
* Category sales trends;
* Monthly category performance.

---

## Geographic Analysis

* Top profitable countries;
* Regional sales performance;
* Country contribution to revenue;
* Regional sales dynamics.

---

## Sales Channel Analysis

* Profit by sales channel;
* Monthly channel performance;
* Channel profitability trends.

---

## Time Series Analysis

* Sales by month;
* Sales by weekday;
* Sales by year;
* Seasonal trends;
* Revenue dynamics.

---

## Logistics Analysis

A separate section investigates delivery efficiency:

* Delivery time distribution;
* Average delivery time by product category;
* Delivery time by country;
* Delivery time by region;
* Delivery trends over time.

---

## Profit vs Delivery Time

The project explores whether longer delivery periods affect profitability.

The analysis includes:

* Scatter plots;
* Profit distribution;
* Order count comparison;
* Delivery time segmentation;
* Business interpretation.

---

## Long-Term Sales Trends

The notebook studies:

* Sales by region and year;
* Sales by country;
* Product category dynamics;
* Top-performing markets;
* Historical growth patterns.

---

# 📉 Data Visualization

The project contains numerous visualizations:

* Bar charts;
* Line charts;
* Heatmaps;
* Scatter plots;
* Histograms;
* Comparative category charts;
* Regional trend analysis.

---

# 💡 Key Business Insights

The analysis identifies:

* Most profitable product categories;
* Best-performing countries and regions;
* Sales channel effectiveness;
* Seasonal demand patterns;
* Delivery efficiency trends;
* Revenue growth opportunities;
* Market expansion potential.

---

# 🚀 Business Recommendations

Based on the analysis, several strategic recommendations are proposed:

* Expand into new geographic markets;
* Focus investment on top-performing product categories;
* Improve logistics efficiency;
* Strengthen successful sales channels;
* Increase marketing efforts in growing regions;
* Optimize inventory planning based on seasonal demand.

---

# 📌 Project Highlights

This project demonstrates practical skills in:

* Data cleaning;
* Data merging;
* Feature engineering;
* Exploratory Data Analysis (EDA);
* Business analytics;
* Time-series analysis;
* Logistics analysis;
* Data visualization;
* Business storytelling;
* Strategic recommendations.

---

# 🎓 Conclusion

Global Sales Insights is a complete end-to-end data analytics project that transforms raw business data into actionable insights.

The project showcases the ability to work with multiple datasets, perform advanced exploratory analysis, create meaningful visualizations, and provide practical business recommendations for improving sales performance and operational efficiency.
