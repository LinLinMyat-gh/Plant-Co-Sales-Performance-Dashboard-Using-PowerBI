# Plant Co. Sales Performance Analysis

This project analyzes sales data from **Plant Co.** to derive insights into sales trends, customer behavior, and product performance. By leveraging data from sales transactions, customer information, and product hierarchy, we aim to identify key drivers of sales, segment customers effectively, and improve overall business performance.

## Objectives

- **Sales Analysis:** 
    - Track sales trends over time (daily, weekly, monthly, yearly).
    - Identify top-selling products and product categories.
    - Analyze profit margins and identify areas for improvement.
    - Forecast future sales based on historical data.
- **Customer Segmentation:** 
    - Segment customers by geography (country, region).
    - Identify high-value customers and analyze their purchasing behavior.
    - Calculate and analyze Customer Lifetime Value (CLTV).
- **Product Performance Evaluation:** 
    - Analyze the performance of different product families, groups, and individual products.
    - Identify underperforming products and explore opportunities for new product development.
    - Evaluate the impact of pricing strategies and promotions on product sales.

## Datasets

### 1. **Plant_FACT.xls**
Contains the sales transactions data with the following columns:
- **Product_id:** Unique identifier for each product.
- **Sales_USD:** Total sales amount in USD.
- **Quantity:** Number of units sold.
- **Price_USD:** Price per unit in USD.
- **COGS_USD:** Cost of goods sold in USD.
- **Date_Time:** Date and time of the transaction.
- **Account_id:** Identifier for the account/customer.

### 2. **Accounts.xls**
Contains customer and account information:
- **country_code:** Country code where the account is based.
- **Account:** The name of the account.
- **Master_id:** Higher-level categorization of the account.
- **Account_id:** Unique identifier for the account.
- **Latitude2, Longitude:** Geographic coordinates of the account.
- **country2:** Full country name.
- **Postal_code, Street_name, Street_number:** Address details.

### 3. **Plant_Hierarchy.xls**
Contains product hierarchy information:
- **Product_Family:** Broad category of the product.
- **Product_Family_Id:** Unique identifier for the product family.
- **Product_Group:** Sub-category within the product family.
- **Product_Group_id:** Unique identifier for the product group.
- **Product_Name:** Specific name of the product.
- **Product_Name_id:** Unique identifier for the product name.
- **Product_Size:** Size category of the product.
- **Product_Type:** Type or application of the product.

## Executive Summary

This analysis combines data from sales transactions, customer information, and product hierarchy to generate insights about **Plant Co.'s** sales trends, customer behaviors, and product performance. The goal is to identify sales drivers, optimize customer segmentation, and make strategic decisions to enhance business performance.

### Key Insights

- **Gross Profit Performance:** Dashboard focused on analyzing the company's profitability, identifying areas for concern, and providing insights into gross profit margins.

![Screenshot 2024-12-30 224437](https://github.com/user-attachments/assets/c3c679de-18a0-4cf2-abf7-214434d32ac6)

  
- **Quantity Performance:** Dashboard showing variations in sales quantity across different months and countries, highlighting a decline in Year-To-Date (YTD) quantity compared to the previous year.

![Screenshot 2024-12-30 224504](https://github.com/user-attachments/assets/b0823b89-6564-4ba2-82b8-796b313051ed)


- **Sales Performance:** Dashboard focused on overall sales revenue, revealing a significant drop in YTD sales compared to the previous year, and identifying countries with the largest sales drops.

![Screenshot 2024-12-30 224535](https://github.com/user-attachments/assets/26336212-e9b4-4597-ba07-e6d319a2e344)


## Dashboard: Key Insights

### 1. **Sales Performance:**
   - Analyze sales trends over time (daily, weekly, monthly, yearly).
   - Identify top-selling products and product categories.
   - Perform gross profit margin analysis.
   - Assess sales performance by region and country.

### 2. **Customer Segmentation:**
   - Segment customers by geography and purchasing behavior.
   - Analyze high-value customers and their purchasing habits.
   - Calculate and evaluate Customer Lifetime Value (CLTV).

### 3. **Product Performance:**
   - Evaluate product performance by family, group, and individual product.
   - Analyze price elasticity.
   - Assess product promotion effectiveness.

## Conclusion: Strategic Focus

Based on the analysis, **Plant Co.** should focus on the following:

- **Improving sales in key regions and customer segments.**
- **Optimizing product mix and pricing strategies.**
- **Developing and launching new products in high-demand categories.**
- **Enhancing customer relationships and loyalty programs.**
- **Improving operational efficiency to reduce costs and increase profitability.**

## Recommendations

- **Optimize Regional Sales Strategies:** 
    - Focus on improving sales in underperforming regions identified through the analysis. Tailor marketing and sales strategies based on regional customer preferences and trends.
    - Target high-potential markets by analyzing historical sales performance and customer segmentation data to increase sales in those regions.

- **Enhance Product Mix and Pricing Strategies:**
    - Assess the performance of different product families and groups. Use this data to adjust product offerings by discontinuing underperforming products and promoting high-demand items.
    - Implement dynamic pricing strategies based on demand, competition, and seasonal trends to improve profit margins.
  
- **Leverage Customer Segmentation for Targeted Marketing:**
    - Utilize the segmentation data to personalize marketing campaigns and create targeted promotions for high-value customers, increasing their lifetime value.
    - Develop customer retention strategies by focusing on the most profitable customer segments and identifying opportunities for upselling or cross-selling products.
  
- **Improve Product Development and Innovation:**
    - Focus on developing new products in high-demand categories based on customer behavior insights and product performance data.
    - Gather feedback from high-value customers to understand unmet needs and opportunities for new product offerings.
  
- **Enhance Operational Efficiency:**
    - Analyze cost structures and identify areas where operational inefficiencies can be reduced. Focus on optimizing inventory management, supply chain, and production costs.
    - Streamline processes to reduce the cost of goods sold (COGS) and increase profitability.

- **Monitor and Adjust Sales and Performance KPIs Regularly:**
    - Continuously track key performance indicators (KPIs) such as gross profit, sales growth, and customer lifetime value. Adjust strategies based on real-time data and performance trends.
    - Set up automated alerts and dashboards for ongoing monitoring of sales and profitability, enabling timely interventions when necessary.

- **Focus on Price Elasticity and Promotions:**
    - Analyze product pricing and customer response to identify the optimal pricing strategy for each product category. This will help maximize revenue without negatively impacting customer demand.
    - Evaluate the effectiveness of promotional campaigns and adjust promotional pricing based on customer feedback and sales results.

- **Data-Driven Decision Making for Growth:**
    - Use the sales performance and customer behavior analysis to forecast future trends and adjust business strategies accordingly.
    - Leverage predictive analytics to identify emerging product categories or customer segments with growth potential and direct resources towards capitalizing on these opportunities.


