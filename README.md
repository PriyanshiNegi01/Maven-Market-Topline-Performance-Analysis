# Maven Market Topline Performance Analysis using Power BI

## Overview
Maven Market is a multi-national grocery chain with locations in Canada, Mexico, and the United States. The objective of this project was to analyze their 1997-1998 sales data to uncover valuable insights using **Power BI**. The dataset spans multiple years and includes key sales and business data, enabling the analysis of transactions, revenue, profitability, and customer behavior.

### Key Objectives:
- Analyze the sales performance, profitability, and trends across the stores and product brands.
- Visualize total transactions, profit margins, return rates, and other topline metrics.
- Build a relational data model, shape the data, and create a comprehensive interactive report.
- Leverage Power BI to design insights and answer key business questions related to Maven Market’s performance.

### Tools and Technologies Used:
- **Power BI Desktop**
- Data Modeling
- DAX (Data Analysis Expressions)
- Data Cleaning & Shaping
- Visualization techniques like matrix visuals, maps, KPI cards, stacked column charts, and treemaps.

---

## Project Files

- **Data**: Contains the raw CSV files used in this analysis.
    - **MavenMarket_Calendar.csv**
    - **MavenMarket_Customers.csv**
    - **MavenMarket_Products.csv**
    - **MavenMarket_Regions.csv**
    - **MavenMarket_Returns_1997–1998.csv**
    - **MavenMarket_Stores.csv**
    - **MavenMarket_Transactions_1997.csv**
    - **MavenMarket_Transactions_1998.csv**

- **MavenMarketAnalysis_PriyanshiNegi.pbix**: Contains the Power BI project file with built reports.

- **Images**: Includes visual representations from the Power BI report.
    - **MavenMarketLogo.png**: Logo of Maven Market used in the report.
    - **PowerBIDashboardScreenshots.png**: Screenshots of the Power BI report visuals.

---

## Features & Insights

### Data Modeling:
- Established relationships between various data tables, including **Customers**, **Transactions**, **Products**, **Stores**, etc.
- Created calculated columns and DAX measures to compute **Total Transactions**, **Total Profit**, **Profit Margin**, **Return Rate**, and other business KPIs.
- Integrated slicers, map visuals, and KPI cards to enable interactive filtering and drill-down functionality.

### Key Visualizations:
1. **Matrix Visuals**: Showed total transactions, profit, margin, and return rate by **Product_Brand**.
2. **Map Visual**: Displayed total transactions by **store city**, with slicers to filter data by country.
3. **KPI Cards**: Displayed performance metrics such as **Current Month Transactions**, **Total Profit**, and **Total Returns** vs. **Last Month** values.
4. **Treemap Visual**: Helped break down transactions by **store country**, with drill-up and drill-down features.
5. **Stacked Column Chart**: Analyzed **Weekly Revenue Trending**.
6. **Top N Filter**: Applied to show the top 30 **Product_Brands** sorted by **Total Transactions**.

### Insights Derived:
- Identified top-performing **Product Brands**.
- Tracked performance by **region** and **store city**.
- Highlighted trends in **Total Revenue**, **Profit**, and **Return Rate** across **1997-1998**.

---

## How to Use

1. Download all files in this repository.
2. Open the **MavenMarketAnalysis_PriyanshiNegi.pbix** file in **Power BI Desktop**.
3. Interact with the visuals and explore different filters, slicers, and drill-down functionalities.
4. Review the data and analysis by exploring the included CSV files.

---

## Contact

For any inquiries or further questions, feel free to reach out to me via [LinkedIn](https://www.linkedin.com/in/priyanshinegi01).
