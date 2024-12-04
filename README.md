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

The **Data Model** is built in Power BI using various tables like **Transactions**, **Products**, and **Stores**. Here's a screenshot of the data model:

![MavenMarket DataModel](https://github.com/user-attachments/assets/91f76060-d747-4519-b7bd-f1e472e78cd5)

### Dashboard

Here’s a screenshot of the interactive **Power BI Dashboard** that provides insights on sales, profit margins, transactions, and more:

![MavenMarket Dashboard](https://github.com/user-attachments/assets/10a0119d-443b-4048-8d56-a96d5346cf20)

### Visualizations and Metrics
The report includes the following visualizations and metrics:

1. **Matrix Visual**: Displays **Total Transactions**, **Total Profit**, **Profit Margin**, and **Return Rate** by **Product Brand**.
   - Conditional formatting is applied to **Total Transactions** using **data bars**, **Profit Margin** using **color scales** (White to Green), and **Return Rate** using **color scales** (White to Red).
   - A **Top N** filter is applied to show the top 30 product brands sorted by **Total Transactions**.

2. **KPI Cards**: Shows **Total Transactions**, **Total Profit**, and **Total Returns** compared to **Last Month** with updated titles and formatting.

3. **Map Visual**: Displays **Total Transactions** by **Store City** with an interactive slicer to filter data by country.

4. **Treemap Visual**: Breaks down **Total Transactions** by **Store Country**, with drill-up and drill-down functionality by **Store State** and **Store City**.

5. **Stacked Column Chart**: Displays **Total Revenue** by **Week**, with a report-level filter applied to show data for the year **1998**.

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


## Conclusion

This Power BI project highlights the **Topline Performance** analysis of **Maven Market's** sales data, focusing on understanding key performance indicators (KPIs) like transactions, profit margins, returns, and revenue trends. The interactive dashboard allows stakeholders to drill down and explore insights across multiple dimensions, providing valuable business insights into Maven Market’s performance.

---


## Contact

For any inquiries or further questions, feel free to reach out to me via [LinkedIn](https://www.linkedin.com/in/priyanshinegi01).
