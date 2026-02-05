# ipl_analysis
# Dashboard
<img width="1809" height="747" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/5ab373c2-5432-41d4-87f9-be6d794c1587" />

# 1.Data Collection
n & Understanding
•	Imported raw coffee shop sales data into Excel
•	Reviewed columns such as:
o	Transaction ID
o	Date
o	Product Category
o	City
o	Quantity
o	Revenue
o	Profit
•	Ensured correct data types (dates, numbers, text)

# 2.Data Cleaning & Preparation
•	Removed duplicate and blank records
•	Standardized category and city names
•	Created additional helper columns:
o	Year (from Date)
o	Month (from Date)
o	Weekday (using TEXT(Date,"ddd"))
•	Checked for missing or inconsistent values

# 3.Creating Calculated Fields (KPIs)
Used Excel formulas to calculate key metrics:
•	Total Transactions → COUNT(Transaction ID)
•	Total Quantity Sold → SUM(Quantity)
•	Total Revenue → SUM(Revenue)
•	Total Profit → SUM(Profit)
•	Revenue % by Year → Revenue ÷ Total Revenue

# 4.Building Pivot Tables
Created multiple pivot tables for analysis:
•	Category-wise transaction count
•	Weekday-wise transaction count
•	Monthly transaction trends
•	City-wise revenue distribution
•	Year-wise revenue comparison
Each pivot table was built with:
•	Proper sorting
•	Clear labels
•	Optimized layout for charts

# 5.Creating Pivot Charts
Converted pivot tables into interactive visuals:
•	Bar charts → Category & Monthly Transactions
•	Line chart → Weekday Transaction Trend
•	Donut chart → Yearly Revenue %
•	Pie chart → Revenue % by City
•	Stacked column chart → Monthly Revenue comparison

# 6.Adding Interactivity with Slicers
Inserted slicers for:
•	Year
•	Month
•	City
Connected slicers to all pivot tables to ensure:
•	Cross-filtering
•	Real-time updates across the dashboard

# 7.Designing KPI Cards
•	Created KPI cards using:
o	Shapes
o	Icons
o	Linked cell values
•	Displayed:
o	Total Transactions
o	Total Quantity
o	Total Revenue
o	Total Profit
Focused on:
•	Clear visibility
•	Consistent formatting
•	Executive-style layout

# 8.Dashboard Layout & Formatting
•	Used a coffee-themed color palette
•	Applied consistent fonts and spacing
•	Rounded cards and aligned visuals
•	Removed gridlines for a clean UI
•	Ensured dashboard fits single screen view

# 9.Final Testing & Optimization
•	Tested slicers for accuracy
•	Verified KPI totals across all filters
•	Reduced unnecessary pivot cache usage
•	Optimized performance for smoother interaction

# 10.Final Outcome
An interactive Excel dashboard that:
•	Provides end-to-end sales insights
•	Supports quick decision-making
•	Demonstrates strong Excel, analytics, and visualization skills






