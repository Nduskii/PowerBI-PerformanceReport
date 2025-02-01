# PowerBI-PerformanceReport
A Power BI performance report for a plant-selling company, analyzing sales, quantity, and gross profit trends across countries, time periods, and product categories. Includes treemap, waterfall, line-column, and scatter visualizations for insightful comparisons.
# Power BI Performance Report

## Overview
This Power BI report provides a performance analysis for a plant-selling company. It compares Year-to-Date (YTD) vs. Previous Year-to-Date (PYTD) for sales, quantity, and gross profit trends, focusing on the bottom 10 countries in terms of YTD vs. PYTD performance.

## Data Sources
The report is built using the following datasets:
- **Accounts Data**: Contains customer details, including account IDs and country information.
- **Sales Data**: Tracks sales performance metrics.
- **Product Data**: Provides information on various plants sold.

## Visualizations
### 1. Treemap
- **Category**: Country (Filtered to show the bottom 10 countries)
- **Values**: Year-to-date (YTD) vs. Previous Year-to-Date (PYTD) for Sales, Quantity, and Gross Profit
- **Controls**: Tile slicer to switch between Sales, Quantity, and Gross Profit

### 2. Waterfall Chart (Drill-down Enabled)
- **Y-Axis**: YTD vs. PYTD
- **Drill-down Categories**: Month → Country → Product Type → Product Name

### 3. Line and Stacked Column Chart
- **X-Axis**: Month and Quarter
- **Column Y-Axis**: Value YTD
- **Line Y-Axis**: Value PYTD
- **Legend**: Product Type
- **Controls**: Switch between Sales, Quantity, and Gross Profit

### 4. Scatter Chart (With Zoom Slider)
- **Values**: Account Data (Account Names)
- **X-Axis**: Value YTD
- **Y-Axis**: Gross Profit %

## Interactive Features
- **Slicers**: Allow filtering by Sales, Quantity, and Gross Profit, as well as selecting specific years (2022-2024).
- **Tile Slicer**: Displays selected values for PYTD, YTD vs. PYTD, YTD, and Gross Profit %.

## How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Use slicers to explore different metrics and time periods.
3. Drill down into the waterfall chart for detailed breakdowns.
4. Utilize the zoom feature in the scatter chart for better insights.

## Contact
For any inquiries or contributions, feel free to open an issue or submit a pull request.
![Report Overview]( file:///C:/Users/Other/Pictures/report%20screenshots)



