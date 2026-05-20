# 📊 Executive Financial Dashboard with Interactive KPIs

A Tableau dashboard designed for executive-level financial reporting, enabling FP&A teams to monitor income statement performance, track year-over-year trends, and drill down by business division and region, all in a single interactive view.

---

## 🧭 Overview

This project addresses a common FP&A challenge: consolidating scattered financial metrics into one decision-ready view for leadership. Rather than static reports, the dashboard gives executives a live, filterable interface to interrogate company performance across time, geography, and business unit.

It is built on monthly financial data spanning multiple divisions and regions, and covers the full income statement from Revenue through to Net Income.

---

## ✨ Features

### 🃏 Dynamic KPI Cards
Three margin KPIs are displayed as headline scorecards — Gross Margin, Operating Margin, and Return on Assets — each showing the current value alongside its year-over-year delta. The delta automatically renders as green (improvement) or red (decline), giving leadership an immediate read on directional performance without digging into charts.

### 📈 Year-over-Year Trend Analysis
A dual-line chart compares current-year vs. prior-year monthly performance for any income statement metric. The metric is controlled by a parameter dropdown, so the same chart can be used to analyze Revenue one moment and Net Income the next — without navigating to a different view. Peak and trough points are annotated directly on the lines to surface outliers at a glance.

### 🌊 Waterfall Income Statement
A waterfall chart walks through the full P&L from Revenue to Net Income, making it easy to see exactly where margin is being created or lost at each stage — COGS, Operating Expenses, Interest, and Tax. This gives finance teams a fast way to explain profit bridge movements to non-finance stakeholders.

### 🔍 Show/Hide Filters
Filters for Region and Division can be shown or hidden to keep the dashboard uncluttered during presentations.

---

## 🗃️ Data

The data source is an Excel workbook. Each row represents one month of performance for a specific division and region combination, covering:

- 🏢 **Divisions:** Cloud Services, Hardware Solutions, Professional Services, Software Licensing
- 🌍 **Regions:** APAC, EMEA, LATAM, North America
- 💰 **Metrics:** Revenue, COGS, Gross Profit, Operating Expenses, Operating Income, Interest Expense, Pre-Tax Income, Income Tax, Net Income, and associated margin ratios

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| 📊 Tableau Public / Desktop | Dashboard development and publishing |
| 📂 Microsoft Excel | Data source |

**⚙️ Key Tableau concepts used:**
- Parameters for dynamic metric switching
- Sets for flexible division/region filtering
- Calculated fields for margin ratios, YoY deltas, and waterfall Gantt segments
- Pivoting to reshape income statement columns into waterfall-compatible rows
- Dashboard layout containers for structured, responsive design

---

## 🚀 Getting Started

1. 📥 Download the `.twbx` packaged workbook.
2. 🖥️ Open in **Tableau Desktop** or **Tableau Public** (free).
3. 🗂️ Navigate to the **Dashboard 1** tab to access the full interactive view.
4. 🔄 Use the metric dropdown on the trend chart to switch between income statement line items.
5. 🎛️ Toggle the Region and Division filters to slice performance by segment.

> ⚠️ Requires Tableau Desktop 2022.1+ or the latest version of Tableau Public.

---

## 📁 File Structure

```
├── Executive_Financial_Dashboard.twbx   # Tableau packaged workbook
├── CFO_Level_Financial_Metrics.xlsx     # Source data
└── README.md
```

---
## 👤 Author
 
**Anusha Jaganath Poojary**  
Data Analyst
