# Coffee Bean Sales Analysis - Power BI Project

## Overview

This Power BI project analyzes the sales data of a coffee bean company to derive insights into sales performance, product trends, customer behavior, and regional analysis. The project focuses on creating interactive visualizations and implementing DAX calculations to measure key metrics such as total sales, top products, customer lifetime value (CLV), and year-over-year growth,GM%, AOV,Total profit.

## Steps in the Project

### 1. Data Preparation
- Imported the **Orders**, **Customers**, and **Products** datasets into Power BI.
- Cleaned and transformed the data to ensure consistency.
- Established relationships between the tables using **Customer ID** and **Product ID** to create a star schema.

### 2. Report Pages

The Power BI report consists of several key pages:

#### a. Sales Overview
- A summary of total sales, profit, and year-over-year sales growth,total sale by coffee type and roast typetotal sale and profit over years.
- Implemented dynamic DAX measures to calculate total sales, Gross margins, and Average order value(AOV).
- **Screenshot:** ![Sales Overview]((https://github.com/user-attachments/assets/983e16cc-c0bd-420c-976e-55bbe7a98466)
)

#### b. Product Analysis
- Displays the top-selling products by revenue , Coffee types and roast types by sales and GM%AND Details of top 20 salling produtcs.
- Includes a breakdown of product categories and types, using DAX to rank products by sales volume and profit.
- **Screenshot:** ![Product Analysis]((https://github.com/user-attachments/assets/21e0226a-2622-4b7d-ba78-0475dd785110)
)

#### c. Customer Analysis
- Segments customers based on total purchases, customer lifetime value (CLV) by year,customer by loyalty card, top customer based on purchase and their dealits report and returning customer by loyalty card.
- DAX calculations were used to compute CLV and retained customer and returning customer.
- **Screenshot:** ![Customer Analysis](![Screenshot 2024-09-18 205106](https://github.com/user-attachments/assets/51e8fa11-742e-4a94-83e0-620f5a0a0e7d)
)

#### d. Regional Performance
- A geographic map visualization showing total revenue across regions,Total sales by country,top 10 city based on sales and customer based on country.
- Includes filters for regional comparison and sales trends by area.
- **Screenshot:** ![Regional Performance](path_to_regional_performance_screenshot)

#### e. Annual Performance
- A decompostion tree visualization of revenue over year, quater, month and products and retained customer over years and quater.
- Utilizes DAX calculations to compare yearly data and highlight growth trends.
- **Screenshot:** ![Annual Performance](![Screenshot 2024-09-18 205229](https://github.com/user-attachments/assets/286ebeb2-27ff-4c6e-bd6b-600e6eda6c13)
)

### 3. DAX Calculations

This project makes extensive use of DAX to:
- Calculate **Total Sales** based on order quantities and product pricing.
- Calculate **Total profit** based on quantities and profit.
- Calculate **Total customer** based on customer ID.
- Calculate **Total order** based on order ID.
- Calculate **AOV** based on total revenue and order.
- Calculate **GM%** based on total profit and total revenue.
- Calculate **CLV** based on purchase frequance and average customer lifespan anf GM%.
- Calculate **Retaine customer** based on order ID.
- Calculate **Returning Customer** based on  DISTINCTCOUNT Customer ID and order.
- Identify **Top Products** by based on sales.
- Measure **Customer Lifetime Value (CLV)** to understand customer purchasing behavior.
- Track **Year-over-Year Growth** to monitor sales trends and performance over time.

 ## Results

The analysis revealed several key insights that can drive business decisions:

### Sales Growth Trends
- The year-over-year growth analysis shows a consistent upward trend, with a notable spike in Q3 sales due to promotional activities.
- **2022 Sales Decline:** A significant drop in both profit and total sales was observed in 2022. Further investigation is needed to understand the factors contributing to this decline.

### Top-Performing Products
- **Dark Roast Coffee Beans:** Emerged as the top-selling product category, accounting for 10.17% GM%.
- **Coffee types sales:**Exc is best salling product with 12.3k.
- **Roast Type D:** Exhibited a higher gross margin percentage but had lower sales. Strategies should be developed to increase the sales volume of this high-margin product.
- **Roast Type L:**Best salling roast type coffee with 17.4k but has the lowest 9.96% GM %.

### Customer Insights
- **High CLV Customers:** The top 10% of customers contributed to 60% of total revenue, highlighting the importance of customer retention and loyalty programs.
- **Frequent Purchasers:** Customers who made more frequent purchases also tended to buy higher-margin products.
- **CLV Drop in 2022:** A noticeable drop in CLV was recorded in 2022, coinciding with the sales decline. Investigate the reasons behind this drop, including potential changes in customer behavior or loyalty program effectiveness.
- **Loyalty Program Observations:** There is a high rate of returning customers who do not hold loyalty cards, suggesting that some customers are returning without utilizing the loyalty program benefits.

### Regional Performance
- **Western Region:** Outperformed other regions, contributing 35% of total sales. Expanding marketing efforts in underperforming regions could help boost overall revenue.
- **US Market:** Both sales revenue and profitability were notably high in the US, indicating a strong market presence.

### Best Performing Year
- **2020:** Identified as the best performing year in terms of revenue and profitability, setting a benchmark for future performance.

## Business Recommendations

1. **Expand Premium Product Line:** Given the profitability of specialty coffee beans and the high gross margin of roast type D, expanding the premium product line could capture more high-margin sales and offset the impact of lower-performing products.
2. **Enhance Customer Loyalty Programs:** Develop targeted loyalty programs to engage high CLV customers and encourage more frequent purchases. Address the issue of returning customers without loyalty cards to maximize program effectiveness.
3. **Region-Specific Marketing:** Invest in marketing and promotional activities in underperforming regions to grow the customer base and increase regional contributions to overall revenue.
4. **Analyze 2022 Decline:** Conduct a detailed analysis of the 2022 sales and profit drop to identify underlying issues and mitigate similar occurrences in the future.

## How to Use

1. Download the `.pbix` file from this repository.
2. Open the file in Power BI Desktop.
3. Explore the interactive dashboards and use slicers to filter data by region, product type, or customer segment.

## Conclusion

This Coffee Bean Sales Analysis provides actionable insights into sales, products, customer behavior, and regional performance. By leveraging Power BI's interactive capabilities and DAX calculations, the project offers a comprehensive look at the business's overall performance.

