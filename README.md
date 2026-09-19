# Superstore Enterprise Performance Cockpit

An enterprise-grade, 3-page Power BI executive analytics solution built on the Global Superstore dataset. Designed according to modern financial cockpit design systems ("Executive Slate" dark theme), this dashboard provides strategic visibility across commercial growth, product-level margin dilution, and end-to-end logistics fulfillment velocity.

---

## 📊 Live Dashboard Preview

| Page 1: Executive Sales & Financial Overview | Page 2: Product & Profitability Intelligence | Page 3: Supply Chain & Logistics Diagnostics |
| :---: | :---: | :---: |
| ![Page 1](<img width="1026" height="703" alt="Screenshot 2026-09-19 223746" src="https://github.com/user-attachments/assets/caad62e4-c218-43ad-8f5c-bf9910a89acc" />
) | ![Page 2](<img width="995" height="810" alt="Screenshot 2026-09-19 223829" src="https://github.com/user-attachments/assets/c27f9958-8f66-40c9-900b-b8490d95b42f" />
) | ![Page 3](<img width="1023" height="706" alt="Screenshot 2026-09-19 224037" src="https://github.com/user-attachments/assets/bb37c149-5d9f-4c8b-9033-22ee22b88c27" />
) |

---

## 🎯 Executive Summary & Page Architecture

### Page 1: Executive Sales & Financial Overview
Designed for C-suite decision-makers to track top-line velocity and regional profitability health.
* **Top KPI Band:** Total Sales ($2.30M), Total Net Profit ($286.41K), Net Margin % (12.47%), Total Orders (5,009), and Sales YoY Growth % (46.9%).
* **Macro Revenue Trajectory:** Dual-axis monthly revenue versus prior-year (Sales PY) benchmark with trend deviation tracking.
* **Segment Contribution:** Donut breakdown highlighting customer segment dependencies (Consumer 50.6%, Corporate 30.7%, Home Office 18.7%).
* **Geospatial Profitability:** US State fill/bubble density map isolating profit-surplus markets from loss-making territories.

### Page 2: Product & Profitability Intelligence
Focused on identifying profit leaks, margin erosion, and promotional pricing inefficiencies.
* **Operational Profit Metrics:** Sub-Category count, Loss-Making Sub-Categories alert (3), Average Portfolio Discount (15.6%), and Category Contribution ($145.45K Tech Profit).
* **SKU Bleed Diagnostic:** Automated ranking of the top 10 loss-bleeding individual products by net negative profit dollar impact.
* **Discount Sensitivity Matrix:** Scatter analysis evaluating discount depth (%) against realized profit margin (%) to uncover promotional destruction points.
* **Category Volume vs. Net Return:** Clustered horizontal comparison of Sub-Category revenue versus bottom-line profit generation.

### Page 3: Supply Chain & Logistics Diagnostics
Delivers visibility into carrier service levels, delivery friction points, and warehouse dispatch performance.
* **Fulfillment Benchmarks:** Average dispatch velocity (3.9 days), total shipped volume, standard tier concentration (59.8%), and SLA delivery breach incidents (>5 days).
* **Carrier SLA Analysis:** Shipping velocity by service mode (Same Day, First Class, Second Class, Standard Class) benchmarked against fulfillment SLA expectations.
* **Latency Drift:** Monthly fulfillment cycle tracking with a 4.0-day SLA reference line to identify seasonal bottleneck trends.
* **Regional Logistics Scorecard:** State-level matrix diagnosing order volume, dispatch latency, transit SLA breaches, and overall shipping margin impact.

---

## 🎨 Design System: "Executive Slate"

Built strictly with an enterprise dark design language optimized for high readability, minimal eye strain, and clear visual hierarchy:

* **Canvas Background:** `#12161F` (Deep Slate / Dark Charcoal)
* **Card & Container Background:** `#1E2430` (Muted Slate Navy)
* **Container Borders:** `#2E384D` (`1 px`, `8 px` border radius)
* **Text & Typography:** Segoe UI (Titles `#FFFFFF`, Subtitles/Labels `#94A3B8`)

---


---

## 🛠️ Tech Stack & Modeling

* **BI Platform:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema (`Dim_Date` calendar dimension with bidirectional relationship filtering to `Superstore_Full_Cleaned` fact table)
* **Data Transformation:** Power Query (type enforcement, date parsing, calculated transit duration, null value handling)
* **Calculations:** DAX (Time Intelligence, Dynamic Status Alerts, Aggregations)

---

## 👤 Author

* **Name:** Mohd Aayan
* **Role:** Data Analyst & Business Intelligence Developer
* **LinkedIn:** [Mohd Aayan](www.linkedin.com/in/aayan-mansoori-a47a03362) 
* **GitHub:** [@mdayaanmansoori4-dev](https://github.com/mdayaanmansoori4-dev)

---

## 📄 License

* **License Type:** This project is open-source and available under the [MIT License](LICENSE).
