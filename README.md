# excel-bike-sales-analysis
📊 Excel Project: Bike Sales Dashboard
🔍 Project Overview
The goal of this project is to analyze bike sales data by creating a dynamic and interactive Excel dashboard. This includes cleaning the data, applying formulas, creating pivot tables, and integrating slicers for user-driven insights.

✅ Project Objectives
Create a structured dataset with dashboards and pivot tables.
Clean and prepare the raw data.
Categorize age brackets using formulas.
Build analytical pivot tables for different queries.
Design an interactive dashboard with slicers for filtering.

🛠️ Steps to Complete the Project
Step 1: Create the Working Sheet
Prepare a clean data sheet.
Format the table according to need.
Plan columns like Name, Age, Income, Bought_Bike, etc.

Step 2: Data Cleaning
Remove duplicate data:
→ Select data > Data tab > Remove Duplicates
Use Ctrl + H to replace unwanted values or find specific data entries.

Step 3: Create Age Brackets Using IF Formula
* Use conditional logic to classify people by age:
=IF(L2<31, "Adolescent", "Invalid")

Then improve it using nested IF formulas:
=IF(L2<31, "Adolescent", IF(L2<55, "Middle Age", "Old Age"))
This helps categorize users into:
Adolescent (< 31)
Middle Age (31–54)
Old Age (55+)

Step 4: Create Pivot Tables
Select the entire dataset:
→ Click the first cell, then press Ctrl + A
Insert a Pivot Table from the Insert tab

Now create three key Pivot Tables:

📌 Pivot Table 1:
Query: Average income of people who bought or didn’t buy a bike.
Fields: Bought_Bike, Average Income

📌 Pivot Table 2:
Query: Bike purchase behavior based on Customer Commute Type
Fields: Commute, Bought_Bike, etc.

📌 Pivot Table 3:
Query: Count of people by Age Bracket
Fields: Age Bracket, Count

Step 5: Design the Dashboard
Create a separate sheet titled "Bike Sales Dashboard"

Arrange your pivot tables visually:

  ┌────────────┐   ┌────────────┐
  │ 1st Pivot  │   │ 2nd Pivot  │
  └────────────┘   └────────────┘
         ↓
     ┌────────────┐
     │ 3rd Pivot  │
     └────────────┘
Add headings, colors, borders for clarity.

Step 6: Add Slicers

Click on any pivot table → Go to Insert > Slicer
Add slicers for fields like Age Bracket, Commute, or Bought_Bike

Connect all slicers to all pivot tables for interactivity:
→ Right-click slicer > Report Connections

📝 Summary
This Excel project provides hands-on experience in:
Data cleaning
Conditional formulas
Pivot table creation
Dashboard design
Slicer integration
