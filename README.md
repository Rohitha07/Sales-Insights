# Sales Insight

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZDNlYmJhYzItMDU5Zi00ZWViLWI5ODktNThhMDNhN2JiOTlkIiwidCI6IjliOWFlODAzLWZjZjgtNDlhMi05OTVhLTU1N2ExYTgyYzJlMSJ9

## Problem Statement

The Sales Insight Dashboard provides businesses with a comprehensive view of their sales performance. It enables decision-makers to analyze key sales metrics, identify trends, and uncover insights that can drive strategic business decisions. The dashboard offers an in-depth analysis of total revenue, sales trends over time, top-performing products, regional sales distribution, and customer purchasing behavior.

By leveraging this dashboard, businesses can optimize sales strategies, improve operational efficiency, and enhance customer engagement.


### Steps followed 

- Step 1 : Data Loading

    The dataset was imported into Power BI from a SQL database.

    Data tables include sales transactions, customer details, product information, and regional sales data.
- Step 2 : Data Cleaning and Transformation

    Opened Power Query Editor to inspect data quality.

    Checked "Column Distribution," "Column Quality," and "Column Profile" for missing or inconsistent values.

    Removed duplicate records and handled null values appropriately.

    Created calculated columns and measures using DAX for better analysis.
- Step 3 : Data Modeling

    Established relationships between different tables using primary and foreign keys.

    Optimized data model to enhance report performance.
- Step 4 : Report Design

    Selected an appropriate theme for visual consistency.

    Used slicers for filtering by Date, Region, Product Category, and Customer Segment.

    Designed interactive visuals to enhance user experience.
- Step 5 : Visualizations Used

     - KPI Cards:

       Total Sales Revenue

       Total Number of Transactions

       Average Order Value

     - Line Chart:

       Sales Trends Over Time

     - Bar Chart:

       Top 5 Best-Selling Products

       Sales by Region

     - Pie Chart:

       Customer Segmentation

     - Table Visuals:

       Detailed sales transactions

     - Geo-Map Visualization:

       Sales distribution by geographical location
- Step 6 : DAX Measures

    Total Sales: Total Sales = SUM(Sales[Revenue])

    Average Sales Per Transaction: Avg Sales = AVERAGE(Sales[Revenue])

    Total Transactions Count: Total Transactions = COUNT(Sales[Transaction ID])

    Sales Growth Rate: Sales Growth = (Current Year Sales - Previous Year Sales) / Previous Year Sales * 100
- Step 7 : Publishing the Dashboard
    The report was published to Power BI Service.

    Configured scheduled data refresh for real-time updates.

    Shared access with stakeholders for easy collaboration.

### Insights from the Dashboard

#### Total Sales Performance

- The total revenue generated was $X million.

- The average order value was $Y per transaction.

#### Sales Trends

- Monthly sales showed a Z% increase compared to the previous year.

- Peak sales were observed during the holiday season.

#### Top Performing Products

- The highest-selling product was Product A, generating $X revenue.

- The top 5 products contributed to Y% of total revenue.

#### Regional Sales Distribution

- The highest sales were recorded in Region A, contributing Z% of total revenue.

- Region B showed the lowest sales, indicating potential areas for improvement.

#### Customer Insights

- X% of customers are repeat buyers, indicating strong customer retention.

- Most purchases were made by customers aged Y-Z years.

### Conclusion

The Sales Insight Dashboard provides businesses with key sales metrics, trends, and customer insights to make data-driven decisions. By focusing on high-performing regions and products while improving low-performing areas, businesses can optimize their sales strategy for growth.

### Future Improvements

- Incorporating machine learning models for sales forecasting.

- Adding real-time sales tracking features.

- Expanding customer segmentation for better marketing strategies.
