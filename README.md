# 📊 Website Traffic Trend & 6-Month Forecast (Power BI)

## 📌 Project Overview

This project focuses on analysing historical website traffic trends and applying time series forecasting in Power BI to predict future performance. The goal is to demonstrate how historical data can support data-driven planning and decision-making.

---

## 🎯 Business Problem

An organisation wants to understand whether website traffic is growing and estimate future visits to support marketing planning and resource allocation.

Key questions:

* Is website traffic increasing over time?
* What is the expected traffic in the next few months?
* Can historical trends help predict future performance?

---

## 📂 Dataset Description

The dataset contains monthly website performance metrics:

* **Date** – Time period (monthly)
* **Website_Visits** – Total number of visitors
* **Conversions** – Number of successful user actions
* **Revenue** – Income generated
* **Avg_Session_Duration** – Average time spent on site
* **Bounce_Rate** – % of users leaving without interaction

---

## 🧹 Data Cleaning & Validation

### ✅ Data Preparation Steps (Power Query)

* Split raw data into columns using delimiter
* Promoted first row as headers
* Renamed table to `Web_Analytics_Data`
* Set correct data types:

  * Date → Date format
  * Numeric fields → Whole numbers

### 🔍 Validation Checks (Before Analysis)

* Verified no missing values
* Ensured no duplicate records
* Checked logical ranges:

  * Bounce Rate (0–100)
  * Positive values for visits, conversions, revenue
* Confirmed date sequence is continuous and ordered

### 🔍 Validation Checks (After Analysis)

* Trend consistency checked (no abnormal spikes)
* Forecast reviewed for realistic pattern (no sudden jumps)
* Compared historical trend vs forecast direction

---

## ⚙️ Steps Performed

1. Loaded dataset into Power BI
2. Cleaned and transformed data using Power Query
3. Created a **line chart** for Website Visits over time
4. Applied **Time Series Forecasting**:

   * Forecast length: 6 months
   * Confidence interval: 95%
   * Seasonality: Auto
5. Designed a clean, minimal dashboard layout
6. Added insight text to explain findings

---
## Dashboard



## 📈 Key Insight

* Website traffic shows a **consistent upward trend** over time
* No major fluctuations, indicating stable growth
* Forecast predicts **continued increase in traffic**
* Suggests effective marketing or improved user acquisition strategies

---

## 📊 Conclusion

The analysis indicates a strong and steady growth pattern in website traffic. The forecast suggests that this trend is likely to continue, providing confidence for future planning and decision-making.

---

## 🚀 Tools Used

* Power BI Desktop
* Power Query (Data Transformation)
* Time Series Forecasting (Built-in Analytics)

---

## 🧠 Key Skills Demonstrated

* Data Cleaning & Validation
* Time Series Analysis
* Forecasting
* Data Visualization
* Business Insight Communication

---

## 📌 Note

This project is a **proof-of-concept forecasting model** based on limited historical data. Predictions provide directional insights rather than exact values.

---
