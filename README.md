# Order-Data-analysis-
Developed an interactive Power BI dashboard analyzing product orders across Indian states and cities in 2018. The report offers key insights into revenue, profit, category performance, and regional trends.

## Questions (KPIs)
-What was the total revenue and profit generated in 2018?
-Which product category was the most profitable?
-Which state contributed the highest profit?
-Which city generated the most profit?
-What is the profit trend across months in 2018?
-Which product category had the lowest profit?
-What was the average profit per order?
-How many total orders were received in 2018?
-What is the total cost vs revenue breakdown by product category?
-Which month recorded the highest and lowest profit?

## Process 
-Imported Data:
 Loaded Excel file containing fields like Order ID, Date, Customer, State, City, Category, Order Total, and Product Cost.
-Verified Data Integrity:
 Checked for missing values, duplicates, and anomalies. Ensured data types and formats (e.g., dates) were consistent.
-Cleaned & Transformed Data (Power Query):
 Corrected data types (dates, numbers)
 Removed blanks and errors
 Standardized categories (State, City, Category)
 Created a new column: Profit = Order Total − Product Cost
-Created Pivot Tables & DAX Measures:
 Answered key questions like:
 Total revenue and profit
 Monthly profit trends
 Profit by category, state, and city
 Average profit per order
-Built Visuals:
 Bar/column charts for category and state
 Line chart for monthly trends
 KPI cards for total orders, revenue, and profit
-Designed Dashboard:
 Combined visuals into a clean, single-page layout with slicers for:
 Date
 State
 City
 Category
-Published Report:
 Exported the dashboard as a .pbix file and PDF for sharing and presentation.
