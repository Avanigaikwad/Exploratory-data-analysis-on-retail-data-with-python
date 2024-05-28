# 📄Overview
This project involves a comprehensive analysis of retail data from 2010 to 2011 to understand customer behavior, sales trends, and product performance. The analysis aims to provide actionable insights for strategic decision-making in marketing, inventory management, and sales optimization.

# 🎯Skills Learned
**Data Analysis Skills**
- **Data Cleaning and Preprocessing:**
  - Handled missing values, duplicates, and incorrect data types.
  - Converted date columns to appropriate datetime formats.

- **Data Aggregation and Grouping:**
  - Used .groupby() to aggregate data by customer ID, country, and product descriptions.
  - Calculated summary statistics like total sales, quantities sold, and average prices.

- **Exploratory Data Analysis (EDA):**
  - Analyzed distributions, trends, and outliers in the dataset.
  - Identified top customers, best-selling products, and high-revenue countries.

**Visualization Skills**
- **Matplotlib:**
  - Created bar charts, pie charts, and line plots to visualize data insights.
  - Customized plots with titles, labels, and annotations for clarity.
- **Squarify:**
  - Generated TreeMaps to represent the distribution of transactions by country.

**Statistical Analysis Skills**
- **Descriptive Statistics:**
  - Calculated measures like mean, sum, and count to summarize data attributes.

**Data Manipulation Skills**
- **Pandas:**
  - Utilized Pandas for data manipulation, including merging datasets and sorting data.
  - Employed methods like .nlargest(), .unique(), and .value_counts() for specific analyses.

**Reporting and Communication Skills**
- **Project Documentation:**
  - Summarized the project methodology, findings, and recommendations concisely.
  - Prepared a project summary suitable for professional presentation and GitHub documentation.

**Domain Knowledge**
- **Retail Analytics:**
  - Gained insights into customer behavior, sales trends, and product performance in the retail sector.
  - Developed strategies for inventory management, targeted marketing, and sales optimization.

**Technical Skills**
- **Python:**
  - Leveraged Python for data analysis and visualization tasks.
  - Applied libraries such as Pandas, Matplotlib, and Squarify for comprehensive analysis.
- **Mplcursors:**
  - Used mplcursors for interactive plot annotations, enhancing data presentation.

**Analytical Thinking**
- **Problem-Solving:**
  - Identified key business questions and addressed them through data-driven analysis.
  - Derived actionable insights to support strategic business decisions.


# 📄Project Description
**Objective**

To perform an in-depth analysis of customer behavior, sales trends, and product performance for a retail dataset from 2010 to 2011. The goal is to derive actionable insights to enhance strategic decision-making in marketing, inventory management, and sales optimization.

**Methodology**
1. **Customer Analysis:**
- **Unique Customer Identification:** Used the .unique() method to identify and count 4,372 unique customers.
- **Top Customers:** Grouped data by CustomerID and summed quantities purchased to find top customers. Visualized top 10 customers by purchase quantity.
- **Geographical Distribution:** Analyzed transaction data to map the number of transactions per country, identifying key markets.
2. **Sales Analysis:**
- **Total Sales Calculation:** Calculated total sales (Quantity * UnitPrice) for each country.
- **Revenue Distribution:** Ranked countries by total sales, identifying the United Kingdom as the highest revenue contributor.
- **Seasonal and Weekly Trends:** Extracted and visualized sales data by month and day of the week to identify peak sales periods.
3. **Product Analysis:**
- **Quantities Sold per Product:** Grouped data by product description to sum quantities sold, identifying best and worst-selling products.
- **Top Products Visualization:** Created a pie chart for the top 5 products by sales quantity.
- **Country-wise Demand:** Assessed total quantities purchased per country to understand product demand in different markets.

**Key Findings**
1. **Customer Insights:**
  - **High-Value Customers:** The top 10 customers contributed significantly to overall sales, with the highest purchaser buying 198,263 items.
  - **Market Concentration:** The United Kingdom dominated with 356,728 transactions, indicating a highly concentrated customer base.
2. **Sales Insights:**
  - **Revenue Leaders:** The United Kingdom led in total sales, generating over $7.8 million.
  - **Seasonal Peaks:** November was identified as the busiest sales month, while Thursdays saw the highest sales during the week.
3. **Product Insights:**
  - **Top-Selling Product:** The most popular product was PAPER CRAFT, LITTLE BIRDIE, with 161,990 units sold.
  - **Low-Performing Products:** Multiple products had minimal sales, each selling only 1 unit, suggesting potential for discontinuation.
  - **Demand Distribution:** The United Kingdom also led in product demand, purchasing over 4.5 million units.

**Recommendations**
  - **Inventory Management:** Ensure adequate stock for high-demand products like PAPER CRAFT, LITTLE BIRDIE, and consider discontinuing low-performing items.
  - **Targeted Marketing:** Focus marketing efforts on the United Kingdom and other high-value markets such as the Netherlands and Germany.
  - **Sales Strategies:** Leverage peak sales periods (November and Thursdays) for promotional activities and sales campaigns.
  - **Product Pricing:** Explore premium pricing strategies in markets with higher average unit prices, such as Singapore and Portugal.

**Conclusion**

This analysis provided valuable insights into customer behavior, sales trends, and product performance. The findings support data-driven decision-making for enhancing marketing strategies, optimizing inventory management, and boosting overall sales performance.
