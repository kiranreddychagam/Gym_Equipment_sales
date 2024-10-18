# Gym_Equipment_Sales_Analysis
The project Gym_Equipment_Sales_Analysis is structured into four distinct sheets, each serving a unique analytical purpose, which provides insights into suppliers, brands, product categories, and financial performance. Here’s a detailed breakdown of the project’s structure:
![image](https://github.com/user-attachments/assets/f9a65651-1b2f-4229-bbdf-8bb93f787bfc)
![image](https://github.com/user-attachments/assets/88f421e5-9b06-4ab9-ba4d-b5082ba76f92)

* Supplier and Brand Segregation
Objective: Organize and map suppliers to the brands they supply.
Details:
Identified 3 suppliers and their corresponding 9 brands.
Segregated the products for each brand into three categories:
Rowing Machine
Airbike
Treadmill
This segregation allows you to understand which suppliers are providing specific brands and categories of equipment, making it easier to manage inventory and supplier relationships.
![image](https://github.com/user-attachments/assets/24fc7006-d4e8-4146-b16d-dfcae4374b07)

* Year-on-Year Profit Analysis
Objective: Analyze the profit trends over the past 5 years for each brand.
Details:
Used a Pivot Table to calculate the year-on-year profit for the brands.
Data points such as profit_for_each_month were utilized as values to generate the pivot table.
Applied conditional formatting to visually highlight trends in profit across different years.
This visualization helps in identifying growth patterns, profitability, and possible dips in revenue for brands over the 5-year period.
![image](https://github.com/user-attachments/assets/a845c0e6-557b-4d83-94f1-86e1ce6797d4)

* Market Share Visualization
Objective: Visualize the market share of each brand over the last 6 years.
Details:
Created a line chart to track the market share changes for each brand.
Added slicers for categories (Rowing Machine, Airbike, Treadmill), enabling you to filter the chart based on specific product categories.
This dynamic visualization allows quick insights into how each brand is performing across different product types over the years.
![image](https://github.com/user-attachments/assets/1a2c5296-2a34-479d-88e9-81dcc577909a)

* Profit and Moving Annual Total
Objective: Calculate and showcase the profit trends and moving annual totals.
Details:
Used the SUMIF() function to create a column called profit year to date (YTD), summarizing the total profits up to the latest period for each brand.
Introduced a Moving Annual Total (MAT) column for each brand respective to their category.
MAT helps smooth out fluctuations and showcases overall profitability trends over a rolling 12-month period.
A Pivot Table was created to display the moving annual total for each brand for the latest month.
This provides a clear overview of which brands are sustaining strong profits and which may require attention.
![image](https://github.com/user-attachments/assets/4287e214-57cd-49c9-99e4-6fb6ca6dd3ea)

Insights:
* Supplier and Brand Mapping provides clarity on inventory and supplier management.
* Year-on-Year Profit Analysis highlights the financial trends for better decision-making on brand partnerships.
* Market Share Visualization offers a clear perspective of brand competitiveness in the market.
* Moving Annual Totals allow continuous performance monitoring, ensuring long-term profitability management.

This structure efficiently combines data segmentation, trend analysis, and financial tracking for a comprehensive understanding of the Gym_Equipment_Sales business.
