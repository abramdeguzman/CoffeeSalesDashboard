# ☕ Coffee Sales Dashboard (Power BI)

An interactive Power BI dashboard built to analyse coffee shop sales performance, customer purchasing behaviour, and product/location trends. This project focuses on clean data modelling, practical DAX measures, and clear storytelling through visuals.

---

## 📌 Overview

This dashboard transforms transactional coffee sales data into insights that support smarter decisions such as:
- Identifying peak trading hours and strongest revenue days
- Understanding product mix and basket behaviour
- Benchmarking store locations to find growth opportunities
- Tracking performance over time with proper time intelligence

---

## 🎯 Key Questions Answered

- How much revenue are we generating and how is it trending?
- What is the **Average Transaction Value (ATV)** and how does it change over time?
- How many items do customers buy per visit?
- Which products drive the most **revenue** vs **volume**?
- Which store locations perform best — and where are the opportunities?
- When are we busiest (hourly patterns) and which days perform best (weekday vs weekend)?

---

## 🧱 Data Model

The model is designed around a transaction-level grain:

- **Transaction ID** = backbone of the analysis (one receipt = one customer visit)
- **Transaction Quantity** = items purchased per transaction
- **Revenue** = performance metric used across the dashboard
- **Calendar table** = enables time intelligence (MoM growth, trends, comparisons)

---

## 📊 Measures & Metrics (DAX)

Core measures used in the report include:

- **Total Revenue**
- **Total Transactions**
- **Average Transaction Value (ATV)**
- **Average Items per Transaction**
- **Month-on-Month (MoM) Revenue Growth**
- **Weekday vs Weekend Performance**
- **Hourly Sales Patterns**

---

## 🔍 Insights Highlights

- 🌅 **Morning hours are the busiest**
- 🗓️ **Weekdays generate most revenue**, with weekends still performing well
- ☕ **Coffee & tea lead sales**, while 🥐 bakery items help increase basket size
- 📍 **Store performance varies by location**, showing why context matters

---

## 🛠 Tools & Skills Used

- **Power BI** (reporting + modelling)
- **Power Query** (data cleaning / transformations)
- **DAX** (KPIs + time intelligence)
- **Data Modelling** (star-schema approach)
- **UI/UX** (clean, coffee-themed dashboard design)

---

## 📁 Project Files

Suggested structure (edit to match your repo):

- `/pbix` — Power BI report file  
- `/data` — source dataset (optional)  
- `/images` — dashboard screenshots  
- `/docs` — notes, data dictionary, or measure definitions  

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop**
3. If needed, update the data source path:
   - `Transform data` → `Data source settings` → update file location
4. Refresh the report to load data and interact with visuals

---

## 🖼 Dashboard Preview

<img width="2607" height="1465" alt="Coffee Sales Dashboard" src="https://github.com/user-attachments/assets/3a36bd3b-b178-4b16-a5e0-e16205b3dd40" />

---

## 🙌 Acknowledgements

Thanks to **Chris Dutton** and **Maven Analytics** for the learning resources and inspiration behind this project.

---

## 📬 Feedback

If you have suggestions on the design, measures, or insights, feel free to open an issue or share feedback!
