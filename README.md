# 📊 SuperStore IT Audit & Sales Analytics Dashboard

> **Academic Project** — Data Analytics & IT Audit Course Submission

---

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `dashboard.html` | Interactive Sales & IT Audit Dashboard (open in any browser) |
| `SuperStore_Orders.csv` | Source dataset — 51,290 global order records (2011–2014) |
| `IT_Audit_Report.docx` | Full IT Audit Report with findings & recommendations |
| `README.md` | This documentation file |

---

## 📌 Project Overview

This project involves a **Data Analytics-driven IT Audit** of SuperStore's global order management system. The dataset contains **51,290 transactional records** spanning 4 years, 13 regions, and 3 product categories.

### Key Metrics
- **Total Sales:** $12.64 Million
- **Total Profit:** $1.47 Million (11.62% margin)
- **Total Orders:** 25,035
- **Total Quantity:** 178,312 units

---

## 🔍 IT Audit Findings Summary

| ID | Finding | Severity |
|----|---------|----------|
| F-01 | Excessive Discount Controls — 6,961 orders (13.6%) with >40% discount | 🔴 Critical |
| F-02 | Profit Floor Validation Missing — Negative profit orders processed | 🟠 High |
| F-03 | Data Input Sanitisation — Whitespace in numeric fields | 🟠 High |
| F-04 | Segment Data Segregation — No row-level security evidence | 🟡 Medium |
| F-05 | Furniture Profitability Risk — 7.0% margin vs 11.62% average | 🟡 Medium |

---

## 📊 Dashboard Features

The interactive HTML dashboard includes:
- **KPI Cards** — Sales, Profit, Quantity, High-Discount Orders
- **Year-over-Year Trend** — Sales & Profit 2011–2014
- **Category Breakdown** — Technology, Furniture, Office Supplies
- **Regional Analysis** — Top 5 regions by revenue
- **Discount Distribution** — Audit risk visualisation
- **Order Priority Mix** — Operational insight
- **Audit Findings Register** — Risk-rated control checklist
- **Evidence Tables** — Category profitability & YoY growth

### How to Open the Dashboard
Simply open `dashboard.html` in any modern web browser (Chrome, Firefox, Edge). No server or installation required.

---

## 🛠️ Tools & Technologies

- **Data Analysis:** Python (csv, collections)
- **Visualisation:** Chart.js, HTML5, CSS3
- **Report:** Microsoft Word (.docx)
- **Dataset:** SuperStore_Orders.csv (Global Superstore)

---

## 📁 Dataset Description

| Column | Description |
|--------|-------------|
| order_id | Unique order identifier |
| order_date | Date order was placed |
| ship_date | Date order was shipped |
| ship_mode | Shipping method used |
| customer_name | Customer full name |
| segment | Consumer / Corporate / Home Office |
| state, country | Geographic location |
| market, region | Market and region classification |
| category | Product category |
| sub_category | Product sub-category |
| sales | Order sales amount ($) |
| quantity | Units ordered |
| discount | Discount applied (0–1 scale) |
| profit | Net profit ($) |
| shipping_cost | Shipping cost ($) |
| order_priority | Critical / High / Medium / Low |
| year | Order year |

---

## 🎓 Academic Information

- **Course:** Data Analytics & IT Audit
- **Submission Type:** Practical Component
- **Mentor:** [Prof. Shanmugaraju S](https://www.linkedin.com/in/shanmugaraju-s/)

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/shanmugaraju-s/)

> #RPA #ITAudit #DataAnalytics #Dashboard #LearningByDoing
