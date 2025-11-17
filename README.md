📘 Sales Dataset – README

The folder describes the data cleaning steps, the structure of the final dataset, and the Pivot Tables created after removing duplicate records.

📌 1. Project Overview
This project focuses on processing and cleaning a sales dataset extracted from an Excel file.
After removing duplicate entries and validating the data, several Pivot Tables were created to support reporting and analysis.

🧹 2. Data Cleaning Steps
✔️ Duplicate Removal
All duplicate rows were removed based on all columns to ensure that each sales transaction appears only once.
✔️ Data Validation
Verified that numeric fields such as Order_Quantity, Unit_Cost, and Unit_Price do not contain missing or invalid values.
Removed the unused column “Unnamed: 15” from the dataset.

📊 3. Final Dataset Structure
The cleaned dataset now contains the following fields:
Column	Description
Date	Date of the sales transaction
Day	Day of the month
Month	Month
Year	Year
Customer_Age	Customer’s age
Age_Group	Age category (Youth, Adults, Seniors, etc.)
Customer_Gender	Gender of the customer (M/F)
Country	Country of the sale
State	State/Region
Product_Category	Main product category
Sub_Category	Product subcategory
Product	Product name
Order_Quantity	Quantity sold
Unit_Cost	Cost per unit
Unit_Price	Selling price per unit
Cost	Total cost of the sale
Revenue	Total revenue
Profit	Profit of the transaction

Financial formulas used:
Cost = Order_Quantity × Unit_Cost
Revenue = Order_Quantity × Unit_Price
Profit = Revenue – Cost

📈 4. Pivot Tables Created
🔹 1. Sales by Country
Rows: Country
Values: Sum of Revenue, Sum of Profit
🔹 2. Sales by Age Group and Gender
Rows: Age_Group
Columns: Customer_Gender
Values: Sum of Order_Quantity
🔹 3. Profit by Category and Sub-Category
Rows: Product_Category
Columns: Sub_Category
Values: Sum of Profit
These Pivot Tables simplify analysis and help identify performance trends.

📁 5. How to Use the File
This dataset is ready to be used for:
Data analysis (Excel, Power BI, Tableau)
Building dashboards
Sales performance reporting
Machine Learning preparation (Forecasting, Classification)

🚀 6. Notes
All calculations were reviewed and corrected where needed.
The dataset is clean, structured, and ready for advanced analytics or visualization.