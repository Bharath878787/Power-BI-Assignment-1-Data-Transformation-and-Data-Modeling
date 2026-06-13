# Power BI Assignment 1 – Data Transformation & Data Modeling  
## E‑Commerce Sales Analysis

## Overview
This repository contains my Power BI assignment focused on analyzing e‑commerce sales data.  
I worked with three datasets:
- List of Orders
- Order Details
- Sales Target

The project demonstrates data transformation, cleaning, aggregation, and modeling in Power Query and Power BI.

## Steps Executed

### Data Transformation
1. Imported “List of Orders.csv” into Power BI.
2. Opened “List of Orders” in Power Query Editor by clicking on ‘Transform’.
3. Imported “Order Details.csv” and “Sales target.csv” into Power Query Editor.
4. Made first column as headers in "List of Orders".
5. Restricted "List of Orders" to 500 rows.
6. Changed datatype of "Order Date" to Date.
7. Changed datatype of “Amount” and “Target” to Fixed Decimal Number.
8. Formatted "CustomerName" into Proper Case.
9. Created "Location" column by merging State and City.
10. Added custom column "Profit Margin" = Profit ÷ Amount.
11. Added conditional column "Profit Status" (Loss, Break‑Even, Profit).

### Merging Data
12. Merged "List of Orders" and "Order Details" into "Orders Data" using Order ID.

### Handling Missing & Duplicate Data
13. Verified no missing values.
14. Removed duplicate rows.

### Sorting & Filtering
15. Sorted orders by Order Date (descending).
16. Duplicated "Orders Data" and filtered for Tamil Nadu.

### Grouping & Aggregating
17. Duplicated "Order Details" and created:
   - Count of each Order ID
   - Average profit by Category
   - Total amount by Sub‑Category
18. Duplicated "Sales Target" and aggregated total target amount by Month of Order Date.

### Data Modeling
19. Established relationship between "List of Orders" and "Order Details" (Order ID).
20. Established relationship between "Order Details" and "Sales Target" (Category) and ensured it is active.

## Files
- `Power BI Assignment Data Transformation & Data Modeling E-Commerce Sales Analysis.pbix` → Power BI file with data model and visuals  
- `README.md` → Documentation of all steps executed  
