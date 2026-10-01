## Adidas Sales Analytics Dashboard

**Overview:**
An interactive Power BI dashboard analyzing Adidas sales performance for 2021
across products, regions, states, cities, and retailers.

**Tools:** Power BI Desktop, DAX, Power Query

**Dataset:** Adidas Sales table (Retailer, Region, State, City, Product,
Sales Method, Invoice Date, Price per Unit, Units Sold, Total Sales, Profit).

**Approach:**
1. Loaded and cleaned the sales data in Power Query.
2. Created a dedicated DAX measures table: Total Sales, Total Profit,
   Total Orders, Units Sold, Average Order Value, and Profit Margin %.
3. Designed a dark-themed dashboard with KPI cards, charts, a map, and slicers.

**Techniques & Skills:**
- Data cleaning and modeling
- DAX measures (KPIs)
- Data visualization: bar, line, donut, clustered column, and map charts
- Interactive filtering with Region and Retailer slicers
- Dashboard layout and custom design

**Dashboard Contents:**
- KPIs: Total Orders, Average Order Value, Total Profit, Total Sales,
  Units Sold, Profit Margin %
- Sales by Product
- Monthly Sales Trend
- Sales by State (map)
- Units Sold by Region
- Sales & Profit by Retailer
- Profit by City

**Key Insights:**
- Total sales of about $89.8M with a total profit of about $33.2M.
- Men's Street Footwear is the top-selling product (about $21M).
- West Gear leads retailers in sales (about $24M).
- The West region has the largest share of units sold (27.7%).

![Dashboard](adidas-dashboard.png)
--------------------------------------------------------------------------------------------------------------------------
---

## Kickstarter Analysis Dashboard

**Overview:**
A multi-page Power BI report analyzing 375K Kickstarter projects: how many
succeeded or failed, how much money was pledged, and who backed them,
across categories, subcategories, countries, and years.

**Tools:** Power BI Desktop, DAX, Power Query

**Dashboard Pages:**
1. **Overview:** KPIs (Total Projects, Total Pledged, Total Backers, Sum of
   Goal, Failed vs Successful Projects), Top 5 Projects by Pledged, Top 5
   Countries, Successful vs Failed by Category, Projects by Year, and a
   Category Treemap.
2. **Successful Projects Analysis:** Success rate (35.71%), a decomposition
   tree (Country > Category > Subcategory), Pledged vs Goal by Subcategory,
   and Average Pledged by Country.
3. **Failed Projects Analysis:** Failure rate (52.72%), a decomposition tree,
   Pledged vs Goal by Subcategory, and Failed Project Rate by Year.
4. **Backers Analysis:** Backers by Country, Category, and Subcategory,
   and Backers by project outcome.

**Approach:**
1. Loaded and cleaned the Kickstarter dataset in Power Query.
2. Built DAX measures: Total Projects, Total Pledged, Total Backers,
   Sum of Goal, Successful/Failed Projects, Success Rate, and Failure Rate.
3. Designed a multi-page report with a custom navigation menu and a
   consistent color theme.

**Techniques & Skills:**
- Data cleaning and data modeling
- DAX measures and KPIs
- Decomposition Tree, Treemap, Donut, Line, and Bar charts
- Page navigation buttons
- Comparing outcomes (successful vs failed) across dimensions

**Key Insights:**
- 375K projects raised $3.4bn from 40M backers.
- 35.71% of projects succeeded and 52.72% failed.
- The United States dominates with about 0.29M projects and 33.1M backers.
- Games, Design, and Technology attract the most backers; Games leads with 11.3M.
- Successful projects account for 88.4% of all backers.
- The top pledged project is Pebble Time, with about $20M.
- Projects peaked around 2015 (75K projects).

[View the full report (PDF)](KICKSTARTER.pdf)

