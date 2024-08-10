# Business-Insight-Analysis-1
# AdventureWorks Business Intelligence Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNGQ4NjEzMDYtYjMyZC00MGFiLTgyMGUtMzY2OGQ1ZTZjMzU0IiwidCI6ImJkZWE3ZTBkLWMwYmYtNDhkNS04MDU0LTdhN2QzMDM5OTE5YiJ9&embedImagePlaceholder=true

## Overview:

In this project, I acted as a Business Intelligence Analyst for AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories. The management team required a comprehensive solution to track key performance indicators (KPIs) including sales, revenue, profit, and returns, as well as compare regional performance, analyze product-level trends, and identify high-value customers. Utilizing Power BI Desktop, I developed an interactive dashboard to meet these business needs.



## Objectives:

Connect and transform raw data from multiple CSV files containing transaction, return, product, customer, and sales territory information.
Build a relational data model to structure the data effectively.
Create calculated columns and measures using DAX (Data Analysis Expressions) to derive insights.
Design an interactive dashboard to visualize the data and enable management to track KPIs, analyze trends, and make informed decisions.

## Tools & Technologies:

- Data Visualization: Power BI Desktop
- Data Modeling: Power BI, DAX
- Data Source: CSV files (transactions, returns, products, customers, sales territories)
- Key Insights & Metrics:
- Average Product Cost: $413.66
- Number of Product Colors: 10
- Distinct Customers: 18,480
- Maximum Annual Customer Income: $170,000

## Methodology:

### Data Transformation & Modeling:

Connected and cleaned raw data files using Power BI's Query Editor.
Added calculated columns such as Month Name, Month Number, Start of Year, and Year to the Calendar Table.
Established a star schema for efficient querying and analysis by relating Sales, Calendar, Customer, Product, and Territory tables.
Created a snowflake schema connecting Product, Subcategory, and Category tables.

### DAX Calculations:

Created measures for distinct customer count, return rates, total bike returns, and bike return rates.
Implemented advanced time intelligence functions such as previous month returns, orders, profit, and 90-day rolling profit.

### Dashboard Design:

Divided the dashboard into four key sections: Executive Dashboard, Maps, Customer Details, and Product Details.
Incorporated visuals like line charts for weekly revenue, KPI cards for monthly performance, and matrix visuals for detailed analysis.
Developed interactive map visuals with drill-up and drill-down features for geographic analysis.
Utilized gauge charts to compare monthly orders against targets with conditional formatting to indicate performance.

### Challenges & Solutions:

1) Challenge: Identifying and resolving relationships between multiple tables to ensure accurate data representation.
- Solution: Deleted all existing relationships and restructured them into a star schema, improving data query efficiency and accuracy.
2) Challenge: Calculating complex measures such as return rates and total costs while maintaining performance.
- Solution: Leveraged DAX functions like CALCULATE and DIVIDE to create optimized measures.

### Results:

- Improved Decision-Making: The dashboard provided clear insights into product performance, customer behavior, and regional sales trends, enabling management to make data-driven decisions.
- Identified High-Value Customers: The analysis highlighted key customers contributing significantly to revenue, aiding in targeted marketing efforts.
- Visualized Regional Performance: Maps and drill-down features allowed for a granular view of sales performance across different regions.


## Snapshot of Dashboard (Power BI Service)

## KPIs

### Report Snapshot

![Screenshot 2024-08-11 050228](https://github.com/user-attachments/assets/e6612f48-f3f1-4f80-874a-5b4eaa4cd2bf)

![Screenshot 2024-08-11 050255](https://github.com/user-attachments/assets/0ea16100-ec66-4b87-bd3f-8a4d9f246c72)


### Customer Overview

- Top Customer
![Screenshot 2024-08-11 050332](https://github.com/user-attachments/assets/29cee8c3-a6e5-4b31-ac38-128fe09c70e8)

![Screenshot 2024-08-11 050343](https://github.com/user-attachments/assets/939296a5-e11f-4445-8483-ccd14bd8c1f9)

### Product Overview

![Screenshot 2024-08-11 050243](https://github.com/user-attachments/assets/7292f1ed-3b94-4241-a88c-3cc2f093041f)

- Product related KPIs
![Screenshot 2024-08-11 050312](https://github.com/user-attachments/assets/df0467d1-f6c8-408d-be47-d769c34024b7)

# Insights

A four page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;


 ### [1] Business Insights
 
- Overall All Revenue = ₹24.9 M

- Overall All Profit = ₹10.5 M
 
- Overall Orders = ₹ 25.2k

- Overall Return Rate = 2.2 %

- Derived Top 10 Most Ordered Products

- Also created a KPI of the Most Ordered Product Type & Most Returned Product Type  


### [2] Map Dashboard page 
  
    Were able to bifercate area/ country wise distribution of overall revenue. And can select multiple countries at the same time.
         

### [3] Product Dashboard page

In line with the monthly target, I analyzed whether the set goals for orders, profit, and revenue were met, using product metrics based on the selected product.
  
  These numbers will change if different product filters will be applied accordingly. 



### [4] Customer dashboard page


   Total Number of Customers = 17.4k

   Revenue per Customer = ₹ 1,431/- 

   Top Customer by Revenue = Mr. Maurice Shan

   Bifercated orders by Income Level & by Occupation

   List of Top 100 customer by Revenue to analyse business insights regarding revenues and orders per customer

  

           thus, number of various insights were derived from this Customer dashboard page


### Key Takeaways:

This project enhanced my skills in data transformation, DAX, and Power BI's advanced visualization techniques. It also demonstrated the importance of a well-structured data model in facilitating accurate analysis and reporting.
