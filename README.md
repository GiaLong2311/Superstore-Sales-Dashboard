# Superstore-Sales-Performance-Dashboard
Interactive Excel dashboard analyzing Superstore sales, profitability, discounts, customer segments, and shipping performance.
## Project Objective
This project aims to analyze the sales performance of a retail superstore business from 2014 to 2017 using Excel.
The dashboard was designed to identify key business drivers affecting:
    + Sales performance
    + Profitability
    + Discount effectiveness
    + Regional performance
    + Customer segments
    + Shipping efficiency
The goal is to transform raw transactional data into actionable business insights through interactive data visualization and dashboard storytelling.
## Dataset Used
- <a href="https://github.com/GiaLong2311/Superstore-Sales-Dashboard/blob/main/Superstore_Raw_Data.csv">Dataset</a>
- Dataset characteristics:
    + Time period: January 2014 – December 2017
    + Geographic scope: United States
    + Granularity: Transaction-level retail sales data
- Main dimensions:
    + Order Date
    + Region
    + Segment
    + Category
    + Sub-Category
    + Ship Mode
- Main metrics:
    + Sales
    + Profit
    + Quantity
    + Discount
## Questions (KPIs)
- What are the overall sales and profit performances?
- Which regions generate the highest profitability?
- Which product categories and sub-categories perform best or worst?
- How do discounts impact profit margin?
- Which customer segments contribute the most revenue and profit?
- Which shipping modes are the most efficient?
- Are there any seasonal sales trends?
## Process
1. Data Cleaning
- Converted and standardized date formats using Power Query
- Removed unnecessary fields such as Country
- Created Shipping Days column
- Handled date inconsistencies and invalid values
2. Data Transformation
Created calculated columns:
- Profit Margin
- AOV
- Discount Bands
- Month-Year
- Built helper tables for customized visualizations
3. Data Modeling & Analysis
Created Pivot Tables for:
- Sales trends
- Category analysis
- Regional performance
- Segment analysis
- Discount impact
- Shipping analysis
4. Dashboard Design
- Designed an interactive dashboard using Excel
- Added slicers and timeline filters
- Applied minimalist and business-focused visual design principles
- Focused on storytelling and executive readability
## Tools Used
- Microsoft Excel
- Power Query
- Power Pivot
- Pivot Tables
- Pivot Charts
- Slicers & Timeline Filters
## Dashboard Preview
<img width="1987" height="907" alt="Dashboard_Preview" src="https://github.com/user-attachments/assets/97872f75-960e-4890-bd65-79939485174a" />

## Key Insights
- Sales peak during September, November, and December, indicating a strong seasonal demand period in Q4.
- West and East regions generate the highest profit margins, making them the most efficient markets.
- Bookcases, Tables, and Supplies generate negative profit despite relatively high sales, indicating pricing, discount, or cost structure issues.
- Technology-related sub-categories such as Phones, Copiers, and Accessories generate the highest profitability.
- Orders without discounts generate the highest profit margins, while discounts above 20% lead to negative margins.
- Consumer segment contributes the largest share of sales and profit but has the lowest AOV, suggesting opportunities for upselling and basket expansion.
- Standard Class delivers the strongest balance between sales volume and profitability, while Same Day shipping performs the weakest financially.
## Recommendations
- Prepare inventory and marketing campaigns ahead of Q4 peak seasons.
- Prioritize customer retention and profitability optimization in West and East regions.
- Review pricing strategies, discount policies, and operational costs for loss-making sub-categories.
- Expand and prioritize high-profit Technology products.
- Implement discount thresholds to prevent margin erosion from excessive discounting.
- Increase Consumer segment AOV through bundles, cross-selling, and loyalty programs.
- Optimize shipping strategies to improve operational efficiency and profitability.

