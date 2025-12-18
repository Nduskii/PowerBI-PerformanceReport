# Project Details: Profitability Performance & Drivers Analysis

## Overview
This project delivers a Power BI dashboard focused on understanding **profitability performance and its underlying drivers**.

Rather than treating Sales or Quantity as standalone KPIs, the analysis positions **Gross Profit and GP% as outcome metrics**, with Sales and Quantity used to diagnose *why* performance changed.


## Data Modeling & Measures
- Built a clean analytical model optimized for time, product, country, and account analysis
- Created DAX measures for:
  - Gross Profit
  - Gross Profit Percentage (GP%)
  - YTD and PYTD calculations
  - YTD vs PYTD variance
- Ensured consistency across all metric selections using a unified measure framework


## Analytical Framework

### 1. Profitability Outcome (Gross Profit & GP%)
Gross Profit increased by **2.43M YTD vs PYTD**, while GP% stabilized at **~39.6%**.

This indicates:
- Profit growth was not driven by uncontrolled volume expansion
- Cost structures and pricing discipline remained effective despite revenue pressure

GP% is intentionally retained across all metric views to anchor analysis on **margin quality**, not volume alone.


### 2. Revenue vs Profit Decoupling (Sales Analysis)
Sales declined by **-512K YoY**, yet Gross Profit increased.

This divergence highlights:
- Improved pricing, product mix, or cost efficiency
- A shift toward higher-margin revenue streams
- Reduced reliance on low-margin sales volume

The **Sales YTD vs PYTD waterfall** explains which months and country–product combinations contributed most to revenue decline, enabling targeted corrective action.


### 3. Volume Contribution (Quantity Analysis)
Quantity increased by **+17.05K units YoY**, supporting profitability even as sales value declined.

This suggests:
- Volume growth was achieved without eroding margins
- Operational efficiency improved
- Certain products or markets delivered scalable, profitable volume

The Quantity waterfall reveals **when and where volume gains offset revenue pressure**, rather than masking margin issues.


### 4. Monthly Performance Decomposition (Waterfall: Month–Country–Product)
The waterfall visuals decompose YTD vs PYTD changes by:
- Month
- Country
- Product type

This structure:
- Explains *how* annual performance was built month by month
- Identifies volatility periods rather than relying on year-end aggregates
- Supports root-cause analysis instead of summary reporting


### 5. Market Performance (Bottom 10 Countries)
Treemap visuals identify countries with the largest negative YTD vs PYTD variance.

This enables:
- Prioritization of underperforming regions
- Differentiation between margin issues vs demand issues
- Focused intervention instead of broad cost-cutting


### 6. Product Mix & Seasonality
Monthly stacked visuals show YTD vs PYTD performance by product type.

This reveals:
- Seasonal demand patterns
- Shifts in product mix affecting margin outcomes
- Which product categories consistently support profitability


### 7. Account Profitability Segmentation (GP% × Value)
Scatter plots segment accounts using:
- GP% on the Y-axis
- Gross Profit / Sales / Quantity on the X-axis

This allows stakeholders to:
- Protect high-value, high-margin accounts
- Optimize pricing for high-revenue but low-margin accounts
- Review low-value, low-margin accounts for strategic fit

This approach supports **portfolio optimization**, not just performance monitoring.


## Business Impact
The dashboard enables decision-makers to:
- Separate growth from quality growth
- Detect margin erosion early
- Understand whether performance is price-, volume-, or mix-driven
- Make targeted commercial, pricing, and market decisions

