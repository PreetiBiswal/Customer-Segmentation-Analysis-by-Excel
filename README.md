# Customer Segmentation Analysis
 📌 Objective
Segment customers based on purchasing behavior to identify high-value customers, understand retention rates and recognize customer preferences.

 🎯 Outcome
This analysis provides insights into:
- Customer demographics (age, gender, region)
- High-value customers based on spending behavior
- Purchase frequency segmentation
- Revenue contribution by different customer groups

 📂 Dataset Information
The dataset contains 1000 customer records with the following attributes:
| Column Name            | Description |
| Customer ID            | Unique identifier for each customer |
| Gender                 | Male/Female |
| Age Group              | Age range (18-25, 26-35, etc.) |
| Region                 | Customer's location (North, South, etc.) |
| Purchase Frequency     | Low, Medium, High |
| Avg Purchase Value     | Average spend per transaction ($) |
| Total Purchases        | Number of purchases made |
| Total Spent            | Total money spent ($) |
| Customer Type          | New, Returning, Loyal |

 📊 KPIs (Key Performance Indicators)
These KPIs will be used to measure customer segmentation and revenue impact:
1. Total Customers → `COUNT(Customer ID)`
2. Customer Distribution by Region → `COUNTIF(Region, Selected_Region)`
3. Average Purchase Value per Customer → `AVERAGE(Total Spent)`
4. Total Revenue from Customers → `SUM(Total Spent)`
5. Customer Segmentation Breakdown → `COUNTIF(Customer Type, Selected_Type)`
6. Top 5 High-Value Customers → Use `LARGE(Total Spent, {1,2,3,4,5})`
7. Purchase Frequency Analysis → Percentage of customers in Low, Medium, and High-frequency segments.

 📈 Charts for the Interactive Dashboard
To visualize customer segmentation insights effectively, use the following charts:
1. Customer Distribution by Age Group → Pie Chart
2. Customer Spending by Region → Bar Chart
3. Top 5 Customers by Total Spend → Horizontal Bar Chart
4. Customer Type Distribution → Doughnut Chart
5. Purchase Frequency Segmentation → Stacked Column Chart

 🎛️ Slicers for Dashboard Interactivity
Enhance user interaction by adding the following slicers:
✔ Region  
✔ Customer Type (New, Returning, Loyal)  
✔ Age Group  
✔ Purchase Frequency (Low, Medium, High)  

 🚀 How to Use This Analysis
1. Load the dataset into Excel
2. Create Pivot Tables to summarize key metrics
3. Insert Charts based on pivot tables
4. Apply Slicers for dynamic filtering
5. Design an interactive dashboard using Excel's visualization tools

This project helps business analysts and data professionals understand customer segmentation trends and improve retention strategies. Happy analyzing! 📊


