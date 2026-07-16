# Aviation Business Intelligence System (ABIS)

## 🚀 Project Overview
A comprehensive, enterprise-grade Power BI dashboard engineered to transform raw, disconnected airline operations and passenger transactional data into highly actionable executive insights. This end-to-end solution bridges the gap between financial performance, payment risks, flight operations, and customer behavior across four dedicated analytical layers.

---

## 📊 Key Insights & Business Value Delivered

### 1. Financial Performance Analysis
* **Core Metrics:** Managed a total revenue of **$42.39M** with a net profit of **$3.27M**, maintaining a strategic **7.71%** net profit margin.
* **Top Drivers:** Isolated Kuwait Airways and Saudia as the primary profit-driving carriers.
* **Strategic Recommendation:** Maintain current carrier partnerships while re-evaluating the pricing structures of lower-performing airlines to protect and optimize the net profit margin.

### 2. Payment & Revenue Leakage Analysis
* **Leakage Tracking:** Successfully tracked **$7.61M** in total refunds and **$10.09M** in partial payments.
* **Root Cause Analysis:** Identified "COVID restrictions" and "Personal reasons" as the leading causes for booking cancellations.
* **Strategic Recommendation:** Implement stricter booking deposit rules and optimized cancellation penalty windows for "Corporate" and "Online" channels to minimize total refund leakages.

### 3. Route & Flight Operations Analysis
* **Segment Efficiency:** Discovered that direct flights command **70.38%** of total segments revenue ($36.9M).
* **Geographic Insights:** Identified the GCC as the most profitable passenger home region, driving **$1.92M** in profits.
* **Strategic Recommendation:** Shift and allocate more marketing budget and flight capacity toward direct routes within the GCC region to maximize operational efficiency.

### 4. Customer Segmentation Analysis
* **The Loyalty Mine:** Proved that while loyalty members comprise **50.6%** of total passengers, they contribute a massive **60.2%** of overall profits (**$3.1M** vs **$2.05M**).
* **Strategic Recommendation:** Launch a data-driven retention and acquisition campaign targeting non-loyalty passengers (the remaining **49.4%**), as data proves loyalty members are inherently **10%** more profitable.

---

## 🛠️ Technical Stack & Data Engineering Applied
* **Data Modeling (Star Schema):** Designed a robust database schema connecting transactional tables with optimized relationships.
* **Advanced DAX & Filter Context:** Wrote complex measures using `CALCULATE`, `DIVIDE`, and implemented `CROSSFILTER` to bypass bidirectional filtering limitations between passenger and booking granularities.
* **UI/UX Best Practices:** Created a streamlined executive interface utilizing a consistent corporate color palette, custom dynamic grouping (Age Bins), and an integrated native **Page Navigator** for a frictionless web-app user experience.
