# Sales Insights Dashboard
[ Download Dashboard](https://app.powerbi.com/groups/me/reports/1828f77f-2cee-41c3-a90e-fb369575c7c2/ReportSection?experience=power-bi)

### Goal and Description
Project Goal :- To create a visual representation of key sales metrics and trends to help sales managers and executives track performance, identify areas for improvement, and make data-driven decisions.

Description :-
The Sales Insights Dashboard is a data visualization tool providing a comprehensive overview of a company's sales performance. By offering easy-to-understand visualizations of key sales metrics, the dashboard includes various charts and graphs tracking metrics like revenue, sales quantity, customer revenue, regional revenue, and revenue trends. Users can drill down into specific data points for more detailed information.

The project involves data analysis using SQL and Power BI. In SQL, the focus is on filtering, table joins, and generating insights, such as finding total revenue in 2020. The project includes ETL operations, emphasizing data modeling, implementing star schema, and establishing table relationships. Power Query handles data transformation, addressing issues like duplicate values, ensuring a clean dataset for Power BI dashboard creation. The resulting dashboard showcases insightful charts, meticulous revenue tracking, especially focusing on the top five customers and products.

### Purpose
The primary purpose of the Sales Insights Dashboard is to provide sales managers and executives with the information needed to make data-driven decisions. The dashboard enables tracking progress towards sales goals, identifying areas of underperformance, and developing improvement strategies. Additionally, it aids in identifying trends and patterns in sales data for informed decisions about pricing, marketing, and product development.

I selected this analysis project because I believe that sales data is one of the most valuable assets a company has. Understanding sales performance allows companies to make data-driven decisions that can improve their bottom line.


### Dashboard Link
https://app.powerbi.com/groups/me/reports/1828f77f-2cee-41c3-a90e-fb369575c7c2/ReportSection?experience=power-bi


### Table of contents
- [Goal and Description](#goal-and-description)
- [Purpose](#purpose)
- [Dashboard Link](#dashboard-link)
- [Business Understanding](#business-understanding)
- [Key Features](#key-features)
- [Setup Instructions](#setup-instructions)
- [Technologies](#technologies)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Recommendations for Stakeholders](#recommendations-for-stakeholders)
- [Challenges](#challenges)
- [Future Enhancements](#future-enhancements)
- [Status](#status)
- [References](#references)


### Business understanding
This dashboard provides a high-level overview of a company's sales performance across regions, product categories, and time periods. It aims to identify trends and patterns for informed decision-making on resource allocation and sales improvement.

This information can be used to make data-driven decisions about :-

- Resource Allocation :- Optimize resource allocation by focusing on high-performing regions, product categories, and customers for maximum return on investment.
- Targeted Marketing :- Tailor marketing campaigns to specific customer segments and product categories.
- Pricing Strategy :-  Inform pricing decisions based on customer revenue and sales quantity.
- Inventory Management :- Optimize inventory levels by tracking sales trends to prevent stockouts and overstocking.
- Regional Focus :- Highlight top-performing regions like Delhi NCR and Mumbai for potential expansion or focused resource allocation.
- Product Category Focus :- Identify strong-selling product categories such as Bectricalslytical SEM and Electricalsara Stores to inform product development, marketing, and inventory management.
- Sales Team Optimization :- Recognize top-performing sales representatives for incentives, mentorship, and training.
- Trend Identification :- Track sales trends to reveal seasonal patterns, assess marketing campaign impact, and measure the effectiveness of pricing strategies for future optimization.


### Key Features 
- Revenue Overview :- Displays total revenue generated over time, along with breakdowns by year, month, and region.
- Sales Quantity chart :- Tracks the number of units sold, providing insights into product popularity and sales effectiveness.
- Customer Revenue chart :- Highlights the top-performing customers and identifies potential areas for growth.
- Regional Revenue chart :- Breaks down revenue by region, allowing for targeted sales and marketing efforts.
- Revenue Trend chart :- Visualizes the overall trend in revenue growth, helping identify areas of strength and weakness.
- Sales Funnel Analysis :- Provides insights into the sales pipeline, enabling sales teams to optimize conversion rates.
- Top Customers :- Identifies the company's most valuable customers and provides insights into their buying behavior.
- Drill-Down Capabilities :- Allows users to explore the data in more detail by filtering and segmenting information.
  
![3](https://github.com/M-Ullas/Sales-Insights-Dashboard/assets/142295090/2bc945e6-10cf-40d0-910b-668d29c0350f)


### Setup Instructions
SQL Data Analysis :-
- Ensure you have a SQL environment installed (e.g., MySQL Workbench, pgAdmin) for database interaction.
- [Download the dataset](https://codebasics.io/resources/sales-insights-data-analysis-project)
- Run SQL queries to analyze data, filter, and join tables.
- Utilize the exported CSV for further insights.

Power BI Data Cleaning and ETL :-
- Download and install Power BI, a free Microsoft product.
- Launch Power BI Connect Power BI to your MySQL database.
- Employ Power Query for data transformation, data cleaning and ETL operations.
- Use Power Query Editor to clean data: filter, convert currencies, and create custom/conditional columns.

Power BI Dashboard Building and Analysis Section :-
- Understand the data model and star schema concept.
- Establish relationships between tables manually if needed.
- Create base measures for revenue and sales quantity.
- Address duplicate transactions, especially in the currency column.
- Apply filters using Power Query Editor to enhance data quality
- Visualize data with bar charts, sales quantity charts, revenue charts and customize charts for an optimized dashboard layout.
- Utilize slicers for year and month selection.
- Apply formatting techniques for a polished dashboard.

Interactive Dashboard Customization :-
- customize charts, adjust sizes, and remove unnecessary elements.
- Explore Power BI's interactive capabilities.
- Track top customers and products based on revenue contributions.
- Understand the significance of cleaning data for accurate analysis.


### Technologies
List all of the technologies used to complete the project
- Excel - Data Cleaning
- SQL - Data Analysis
- PowerBI - Creating reports


### Exploratory Data Analysis
EDA involved exploring the data to answer key questions, such as :-
- Which customers are driving the most revenue for the company?
- In which regions is the company performing the best?
- How has the company's revenue trended over time?
- Which customers are buying the most units of product?
- Who are the top customers by revenue and by quantity?
- What is the average order value for each customer segment?
- What is the conversion rate from lead to customer for each marketing channel?

Here are some of the key takeaways from the dashboard :-

- Electricalsara Stores is the top customer, generating 43.89M in revenue, followed by Premium Stores at 49.12M and Electricalsopedia Stores at 49.64M. These three customers together account for over 23% of the company's total revenue.
- Delhi NCR is the top region, generating 520M in revenue, followed by Mumbai at 150M and Ahmedabad at 132M. These three regions together account for over 52% of the company's total revenue.
- The company's total revenue for the period shown is Rs. 984.81 million.
- The company's revenue has been trending upwards over the past three years. There is a slight dip in revenue in June 2019, but it quickly recovers in July and August.
- The top five customers by revenue are Electricalsara Stores, Premium Stores, Excel Stores, Surge Stores, and Nixon.
- The top five regions by revenue are Delhi NCR, Mumbai, Ahmedabad, Chennai, and Kolkata.

The dashboard also includes a number of filters that allow users to drill down into the data and see more detailed information.

### Recommendations for stakeholders

- Sustain Sales Growth :- Maintain the company's steady revenue growth by continuing to uphold the current sales momentum.
- Prioritize Key Customers and Regions :- Focus efforts on top-performing customers such as Electricalsara Stores and Premium Stores, as well as high-revenue regions like Delhi NCR and Mumbai.
- Explore New Product Categories :- Consider expanding into new product categories or sub-categories to capitalize on opportunities, building on the success of existing top categories like Customer-specific Sales Quantity and Electricalsara Stores.
- Invest in Marketing and Sales :- Foster sales growth by investing in marketing and sales initiatives, encompassing strategies like online advertising, social media marketing, and comprehensive sales training.
- Track Sales Funnel and Conversion Rates :- Incorporate information on the sales funnel and conversion rates to identify bottlenecks in the sales process, enhancing overall efficiency.
- Set Clear Goals and Adjust Strategies :- Establish clear sales goals and consistently monitor progress, making necessary adjustments to strategies for continuous improvement.

### Challenges
Some potential challenges faced while creating this dashboard includes :-
- Aligning with business goals :- Ensuring that the dashboard is aligned with the company's overall business goals can be important.
- Interactivity :- Adding interactive features to a dashboard can make it more useful, but it can also add complexity to the development process.
- User interface :- The dashboard needs to be easy to use for all stakeholders. The designer needs to make sure that the layout is intuitive and that the user can easily find the information they need.
- Data cleaning - removing unwanted data & null values, filling blank values, formating and converting currency changed values.
- Data accuracy :- Ensuring the accuracy and completeness of the data was crucial for reliable analysis.
- Data Visualization :- Choosing the right charts and graphs to effectively represent complex data and avoid overwhelming the user can be difficult.

### Future enhancements

- Metrics Expansion :- Expand the dashboard by including additional metrics like profit margin, conversion rate, and customer churn rate for a more holistic view of sales performance.
- Customization Feature :- Enable users to customize the dashboard, focusing on specific data points or timeframes based on individual preferences or stakeholder needs.
- Sales Comparisons :- Introduce the ability to compare sales performance across different time periods or against set targets, providing valuable insights for sales teams.
- Visual Appeal Improvement :- Enhance the visual appeal by adopting a modern design and incorporating more colors to make the dashboard visually engaging and user-friendly.

### Status
Completed

### References
[codebasics]( https://codebasics.io/resources/sales...)

