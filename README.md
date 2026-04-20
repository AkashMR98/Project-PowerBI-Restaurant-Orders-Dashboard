# Project-PowerBI-Restaurant-Orders-Dashboard

> **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling

![Power BI](https://img.shields.io/badge/Tool-PowerBI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)

# Project Overview
This project focuses on analysing restaurant order data by performing data cleaning in Excel and creating interactive dashboards in Power BI. The dataset was processed to remove inconsistencies, standardize formats, and ensure data accuracy before visualization. Power BI is used to present key insights on sales performance, order trends, and menu analysis.

---

# Project Objective
The objective of this project is to analyse restaurant sales data to identify revenue trends, peak order times, and top-performing menu items. By combining Excel for data preparation and Power BI for visualization, the project aims to support data-driven decision-making and improve business performance.

---

# Data Sources
### Sources & Timeline
- Restaurant Orders - Maven Analytics | Build Data Skills, Faster & 2023

---

# 	Problem Statement
- 	To analyse restaurant sales performance to identify revenue trends and overall business growth.
- 	To identify top-performing and low-performing menu items for better menu optimization.
- 	To study peak order times and customer ordering patterns to improve operational efficiency.
- 	To evaluate category-wise performance to understand which food categories generate higher sales.
- 	To understand customer purchasing behaviour to support better marketing and promotional strategies.

---

# Attribute Details
| Attribute Name     | Data Type        | Description                                                                 |
|------------------|------------------|-----------------------------------------------------------------------------|
| order_details_id | Integer          | Unique ID for each order item record (primary key)                         |
| order_id         | Integer          | Unique ID for each order (one order can have multiple items)               |
| order_date       | Date             | Date when the order was placed                                             |
| order_time       | Time             | Time when the order was placed                                             |
| menu_item_id     | Integer          | Unique identifier for each menu item                                       |
| item_name        | Text (String)    | Name of the food item                                                      |
| category         | Text (String)    | Category of the item (e.g., Food, Beverages)                               |
| price            | Decimal / Float  | Price of the item                                                          |

---

# 	Data Pre-Processing (Excel / Power query)
- 	**Data Cleaning & Transformation:** Removed duplicates, handled missing values, standardized formats, and created calculated fields.
-  	**Pivot Tables:** Generated Pivot Tables for data summarization and initial insights.

---

# 	Analysis and Visualizations (Power BI)
- 	**Interactive Dashboard:** Designed with user-friendly navigation, enabling dynamic exploration of restaurant sales and order data across multiple dimensions
- 	**KPI Cards:** Display key metrics such as Total Revenue, Total Orders, Total Items Sold, Growth %, Last Month Sales and Average Order Value (AOV)
- 	**Line Chart:** Shows revenue trends over time (Year, Month, Day), helping identify sales patterns and growth
- 	**Donut Chart:** Represents revenue distribution by category, showing percentage contribution of each category
- 	**Time Analysis Chart:** Analyses order distribution by hour to identify peak ordering time and customer behaviour
- 	**Table:** Top 10 items analysis displays the top 10 menu items ranked based on total revenue, helping identify best-performing products
- 	**Monthly Revenue Analysis:** Calculates total revenue separately for January, February, and March to compare month-wise performance
- 	**Sales Extremes Identification:** Identifies the highest and lowest sales dates along with their corresponding revenue to highlight peak and low-performing days
- 	**Tooltips & Data Labels:** Provide additional insights and clarity on visuals for better understanding

 <img width="1322" height="738" alt="order dashboard" src="https://github.com/user-attachments/assets/5de3fb5f-79bc-40b2-a114-7cf60019e4eb" />


---

  # Insights
- 	Overall revenue reached 161.95K, showing steady growth
- 	Higher number of orders observed during evening hours (peak time)
- 	Top items such as Korean Beef Bowl and Spaghetti contributed significantly to revenue
- 	Italian and Asian categories hold the highest revenue share
- 	March generated the highest revenue among all months
- 	Certain dates showed low sales performance, indicating potential improvement areas

---

  # Conclusions
  The dashboard highlights strong sales performance, clear peak hours, and key   revenue drivers, enabling data-driven decisions to improve business performance and customer engagement.

---
  
# Author

#### Akash MR
Data Analyst 

- Github : [Akash MR](https://github.com/AkashMR98/Project-PowerBI-Restaurant-Orders-Dashboard/blob/main/README.md)
- Email : [Akash MR](akashmr757@gmail.com)

---

Tags 

`#Powerbi` `#DataAnalysis` `#DataVisualization` `#Dax` 

`#SalesAnalysis` `#RestaurantAnalysis`










