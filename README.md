# 📊 Sales Performance & Forecasting Analysis

**Excel | Power Query | PivotTables | Forecast.ETS | Forecast Validation | Business Analysis**

An end-to-end Excel analytics project analyzing historical sales performance from 2019–2022 and developing a validated 2023 revenue forecast to support management decision-making.

---

## 📌 Project Overview

This project analyzes historical sales performance to identify revenue and profitability patterns across customers, products, regions, and time periods.

The analysis combines an interactive Excel dashboard with time-series forecasting, forecast validation, and business diagnostics to transform historical sales data into actionable management insights.

---

## 🎯 Business Problem

Management needs greater visibility into:

- Revenue and profitability drivers
- Customer and product performance
- Regional and shipping performance
- Potential profitability risks
- Future revenue expectations
- Forecast reliability for planning

The objective is to move beyond descriptive reporting and provide actionable decision support.

---

## 🔎 Analysis Objectives

- Measure revenue, profit, margin, orders, and average order value
- Analyze customer, product, regional, and shipping performance
- Identify performance gaps and business risks
- Evaluate monthly and quarterly sales trends
- Forecast 2023 monthly revenue
- Validate forecast accuracy through historical backtesting
- Translate findings into management recommendations

---

## 🗃️ Dataset & Analytical Model

The analysis uses transactional sales data covering **January 2019 through December 2022**.

**Dataset Scope**
- **5,009 unique orders**
- Customer and segment data
- Product and category data
- Regional and geographic data
- Sales, profit, quantity, and discount data
- Order and shipping information
- Historical date dimensions

The dataset was prepared using **Power Query** and structured for KPI analysis, PivotTables, PivotCharts, dashboard reporting, and time-series forecasting.

---

## 🛠️ Tools & Technologies

**Microsoft Excel**
- Power Query
- PivotTables & PivotCharts
- Slicers & Timelines
- KPI calculations
- Interactive dashboard design
- Custom number formatting

**Analytics**
- Revenue & profitability analysis
- Customer segmentation
- Product & regional analysis
- Time-series analysis
- FORECAST.ETS
- Forecast backtesting
- MAPE validation

**Business Analysis**
- 6P diagnostic framework
- Root-cause hypotheses
- SWOT analysis
- Corrective actions
- Management decision support

---

## ⚙️ End-to-End Analytical Workflow

**Data Preparation**  
↓  
**KPI Development**  
↓  
**Performance Analysis**  
↓  
**Interactive Dashboard**  
↓  
**Business Diagnostics**  
↓  
**Forecasting**  
↓  
**Forecast Validation**  
↓  
**Recommendations & Decision Support**

---

## 📊 Analysis & Dashboard

### Executive KPIs

| KPI | Result |
|---|---:|
| Total Revenue | **$2.30M** |
| Total Profit | **$286K** |
| Profit Margin | **12.47%** |
| Total Orders | **5,009** |
| Average Order Value | **$459** |

### Analysis Areas

- Monthly and quarterly revenue trends
- Revenue & profit by region
- Revenue & profit by product category
- Revenue & profit by customer segment
- Top 10 strategic accounts
- Average shipping days by region

> 📊 **Dashboard:** See the [`dashboard`](./dashboard/) folder for the complete dashboard output.

---

## 🔮 Forecasting Analysis

Historical monthly revenue from **2019–2022** was used to develop a 12-month **2023 revenue forecast using Excel FORECAST.ETS**.

The forecasting process included:

**Historical Revenue → ETS Forecast → Backtesting → Error Analysis → MAPE → Business Interpretation**

---

## 📈 Forecast Results

| Forecast KPI | Result |
|---|---:|
| 2023 Forecast Revenue | **$860,252** |
| Average Monthly Forecast | **$71,688** |
| Highest Forecast Month | **Nov 2023 — $109,854** |
| Lowest Forecast Month | **Feb 2023 — $42,569** |

---

## ✅ Forecast Validation

The forecasting methodology was validated using a historical holdout test:

**Train:** 2019–2021  
→ **Forecast:** 2022  
→ **Compare:** Forecast vs. Actual  
→ **Measure:** MAPE

### Backtest MAPE: **47.99%**

The result indicates **substantial monthly forecast uncertainty**. Therefore, the 2023 forecast is treated as a **directional planning estimate rather than a precise prediction**.

---

## 🔍 Key Findings & Business Insights

- **Consumer** was the largest customer segment at approximately **$1.16M revenue**.
- **Technology** generated approximately **$836K revenue and $145K profit**.
- **Furniture** generated approximately **$742K revenue but only $18K profit**, highlighting a profitability concern.
- **West** generated the highest regional revenue at approximately **$725K**.
- Regional shipping times were relatively consistent, with **Central averaging approximately 4.06 days**.
- The **47.99% MAPE** demonstrates substantial monthly forecast uncertainty.

---

## 💡 Management Takeaway

**Furniture profitability represents the clearest immediate management concern.**

Customer mix, regional performance, shipping, and forecast uncertainty provide additional areas for monitoring and diagnostic analysis.

The analysis distinguishes between **what the data demonstrates** and **what management should investigate further**.

---

## 🎯 Recommendations & Decision Support

- Investigate Furniture pricing, discounts, costs, and product mix
- Monitor high-value customers and regional performance
- Diagnose shipping drivers before implementing operational changes
- Use forecast scenarios rather than relying solely on point estimates
- Refresh forecasts as new actual results become available
- Monitor forecast error and MAPE over time

**Decision-Support Framework**

**Measure → Diagnose → Prioritize → Act → Monitor → Validate → Adjust**

---

## 📈 Business Analysis Presentation

The business analysis presentation translates the technical analysis into an executive management story covering:

**Business Problem → Evidence → Risk → Root-Cause Hypothesis → Diagnostic Analysis → Corrective Action → Decision Support**

The presentation includes:
- Executive performance overview
- 6P business diagnostic framework
- Business risks and root-cause hypotheses
- Forecasting and validation
- SWOT analysis
- Recommendations and corrective actions
- Management decision-support framework

> 📑 See the [`presentation`](./presentation/) folder for the complete presentation.

---

## 🧠 Skills Demonstrated

**Data Preparation:** Power Query, data cleaning, validation  
**Excel Analytics:** PivotTables, PivotCharts, KPIs, slicers, timelines  
**Business Intelligence:** Interactive dashboard design and performance reporting  
**Forecasting:** FORECAST.ETS, time-series analysis, backtesting, MAPE  
**Business Analysis:** KPI analysis, 6P framework, SWOT, root-cause hypotheses  
**Decision Support:** Business insights, corrective actions, management recommendations

---

## 📂 Repository Structure

```text
sales-performance-forecasting-analysis/
│
├── README.md
│
├── dashboard/
│   ├── README.md
│   └── Sales_Performance_Forecasting_Dashboard_Tina_Vo.pdf
│
├── workbook/
│   ├── README.md
│   └── Sales_Performance_Forecasting_Analysis_Tina_Vo.xlsx
│
├── presentation/
│   ├── README.md
│   └── Sales_Performance_Forecasting_Business_Analysis.pdf
│
└── documentation/
    ├── README.md
    └── Sales_Performance_Forecasting_Worksheet.pdf

````markdown
    └── Sales_Performance_Forecasting_Worksheet.pdf
```

---

## Portfolio Project

**Created and presented by Tina Vo**

This project was developed for educational and professional portfolio demonstration purposes.
