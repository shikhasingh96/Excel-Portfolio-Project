## Project Title: Bike Buyer Analysis Dashboard

## Objective:
This portfolio project aims to analyze the characteristics of bike buyers using pivot tables in Excel. The goal is to identify patterns and insights related to bike purchases, focusing on factors such as commuting distance, income, and age brackets. The findings will help inform targeted marketing strategies and product offerings.

## Dataset:
The dataset includes the following columns:

Gender
Income,
Children,
Education,
Occupation,
Home Owner,
Cars,
Commute Distance,
Region,
Age,
Age Brackets,
Purchased Bike.

## Analysis Goals:

- Commuting Distance Analysis:

Investigate whether commuting distance influences bike purchasing decisions.
Determine if people living closer to work (one mile away) are more likely to buy bikes compared to those living further away (10-20 miles away).

- Income and Bike Purchase Correlation:

Examine if income levels affect the likelihood of purchasing a bike.
Identify if higher income individuals are more likely to buy bikes, which can inform pricing strategies and target demographics.

- Age Brackets and Bike Purchases:

Analyze bike purchases across different age groups.
Identify which age brackets are more likely to purchase bikes, aiding in the development of age-specific marketing strategies.

## Steps and Methodology:

- Step 1: Data Preparation and Cleaning
1. Load the Dataset:

Open the dataset in Excel.

2. Remove Duplicates:

Select the entire dataset.
Go to the Data tab and click on Remove Duplicates.
Ensure all columns are checked to find duplicates across the entire dataset.

3. Standardize Marital Status:

Identify the column containing marital status.
Replace all variations of married status with "Married" and single status with "Single".

4. Standardize Gender:

Identify the column containing gender.
Replace 'M' with 'Male' and 'F' with 'Female'.

5. Add Age Brackets Column:

Insert a new column next to the Age column and name it "Age Brackets".
Used the following formula to create age brackets based on age:
excel

=IF(L2>54, "Old Age",IF(L2>=31, "Middle Age", IF(L2<31,"Adolesent","Incalid")))


## Pivot Tables for Each Analysis

- Analysis 1: Commuting Distance and Bike Purchase

Set Up the Pivot Table:

Rows: Drag Commute Distance to the Rows area.
Values: Drag Purchased Bike to the Values area.
Filter: Add Purchased Bike to the Filters area to differentiate between those who purchased and those who didn't.

- Analysis 2: Income and Bike Purchase Correlation

Set Up the Pivot Table:

Rows: Drag Income to the Rows area.
Columns: Drag Purchased Bike to the Columns area.
Values: Drag Purchased Bike to the Values area (it should default to Count of Purchased Bike).

- Analysis 3: Age Brackets and Bike Purchases

Set Up the Pivot Table:

Rows: Drag Age Brackets to the Rows area.
Values: Drag Purchased Bike to the Values area (it should default to Count of Purchased Bike).

## Dashboard Creation:

- Combine the Pivot Tables: Create a new worksheet to serve as the dashboard.

- Add Visualizations: Use Excel charts to visualize the pivot table data for easier interpretation.

- Slicers and Filters: Add slicers and filters to the dashboard for interactive data exploration.
- ![Screenshot 2024-06-15 150637](https://github.com/shikhasingh96/Excel-Portfolio-ProjectBike-Buyer-Analysis-Dashboard/assets/136284820/f7fc131d-ccce-4654-817a-9682e9fd982a)


## Conclusion:
This project utilizes Excel pivot tables to analyze bike purchase behavior, focusing on commuting distance, income levels, and age brackets. The insights gained will help tailor marketing efforts and product offerings to better meet the needs and preferences of potential bike buyers. By presenting the findings in a dashboard, stakeholders can easily explore and interpret the data to make informed business decisions.


