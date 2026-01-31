# Retail Sales Forecasting & Pricing Analytics (BI-Focused)

![Status](https://img.shields.io/badge/Status-Complete-success)
![Focus](https://img.shields.io/badge/Role-Business%20Intelligence-yellow)
![Dashboards](https://img.shields.io/badge/Deliverable-Power%20BI-blue)
![Forecasting](https://img.shields.io/badge/Analytics-Forecasting-green)

**Business Intelligence analysis delivering reliable sales forecasts, pricing insights, and executive dashboards to support inventory planning, margin protection, and regional performance management.**

---

## Executive Summary

Business Intelligence teams help leaders understand **what is happening, why it is happening, and what actions to take next**.

This project delivers an end-to-end **BI solution** using historical retail transaction data to support:

- Sales forecasting and demand planning  
- Discount and pricing performance analysis  
- Regional and category-level performance monitoring  
- Executive reporting through interactive Power BI dashboards  

The analysis progresses from **foundational diagnostic analysis** to **validated forecasting models** and **decision-ready dashboards**, mirroring how BI work is delivered in real organizations.

**Outcome:** Forecast reliability improved from a weak baseline (23% variance explained) to a robust model (~70% variance explained), enabling leadership to plan inventory, pricing, and regional investment with greater confidence.

---

## BI Use Case & Stakeholder Value

This analysis is designed to support:

- **Executives** – high-level performance visibility and forward-looking insights  
- **Regional Managers** – demand planning and performance tracking  
- **Merchandising & Pricing Teams** – discount effectiveness and margin protection  
- **Operations & Supply Chain** – inventory planning and stock allocation  

**BI Objective:** Transform raw transactional data into **trusted metrics, forecasts, and dashboards** that directly support business decisions.

---

## Business Questions Addressed

1. What factors most strongly influence sales performance?  
2. How reliable are baseline forecasting methods used in reporting today?  
3. Can forecasting accuracy be improved to support planning decisions?  
4. How do discounts affect both revenue and profitability?  
5. Which regions and categories show sustained, actionable growth?  

---

## Data Overview

- **Source:** Superstore retail transactions (Kaggle)  
- **Volume:** ~10,000 orders  
- **Dimensions:** Region, Category, Sub-Category, Segment, Time  
- **Measures:** Sales, Profit, Quantity, Discount  

The dataset is representative of a mid-sized retail operation and well-suited for BI reporting, trend analysis, and forecasting.

---

## BI & Analytical Approach

### 1. Diagnostic Analysis (Reporting Foundation)

Initial analysis focused on validating key relationships and identifying reporting risks.

**Key findings:**
- Sales and profit are positively correlated, but excessive discounting creates loss-making outliers  
- Discount practices vary significantly by category, reducing pricing consistency  
- Regional performance is uneven, requiring targeted reporting rather than aggregate views  

A **Linear Regression baseline** explained ~23% of sales variance, highlighting the limitations of simple forecasting methods often relied on in reporting.

---

### 2. Forecasting & Trend Analysis (Decision Support)

A **Random Forest forecasting model** was introduced to capture non-linear interactions common in retail data.

**Results:**
- ~70% variance explained  
- Strong alignment between predicted and actual sales (r ≈ 0.83)  
- Material improvement over baseline forecasting  

Rolling **moving averages** were applied to smooth volatility and surface sustained regional trends, particularly strong growth in the West region.

---

## Key BI Insights

- Sales performance depends on interacting drivers (discounts, quantity, category, region), not single metrics  
- Moderate discounting supports sales growth while preserving margins  
- Deep discounting produces diminishing returns and margin risk  
- The West region demonstrates consistent, trend-backed growth  

---

## Power BI Deliverables

This project includes **executive-ready Power BI dashboards** designed for routine business use:

- Sales and profit overview with regional breakdowns  
- Category and sub-category performance analysis  
- Discount impact visualization (sales vs. margin trade-offs)  
- Rolling trend and forecast views with confidence ranges  

Dashboards are structured to support:
- Monthly executive reviews  
- Regional performance check-ins  
- Pricing and inventory planning discussions  

---

## Recommendations

1. **Standardize Discount Reporting**  
   Establish consistent discount thresholds by category to reduce margin leakage and improve comparability.

2. **Adopt Forecast-Backed Planning**  
   Use predictive forecasts rather than historical averages for inventory and staffing decisions.

3. **Focus on Sustained Growth Regions**  
   Prioritize regions with trend-backed growth signals rather than reacting to short-term volatility.

4. **Embed Trend Monitoring in Reviews**  
   Incorporate rolling averages and forecast deltas into monthly reporting to enable proactive decisions.

---

## Tools & BI Stack

- **Power BI Desktop** – executive dashboards and forecasting visuals    
- **Random Forest & Linear Regression** – forecasting comparison  
- **Orange Data Mining** – visual workflow validation  

---

## Why This Matters for a BI Analyst Role

This project demonstrates the ability to:

- Translate business questions into metrics and dashboards  
- Validate and challenge baseline reporting assumptions  
- Improve forecast reliability used in planning discussions  
- Communicate insights clearly to non-technical stakeholders  
- Balance analytical rigor with usability and trust  

---

## Notes

This repository reflects **how BI work is delivered inside organizations**—from data exploration and validation to dashboards, forecasts, and executive-ready insights.

While the dataset is simulated, the BI framework and decision-support approach are directly transferable to real-world retail, e-commerce, and consumer data environments.

---

### ⭐ Portfolio Signal

This project demonstrates **Business Intelligence thinking**, showing how data becomes insight and insight becomes action.
