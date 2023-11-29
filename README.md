# Bike-Sales-Analysis-with-excel
In this project, I performed bike sales analysis, by evaluating the bike sales data to understand and determine the factors contributing to the purchase of bike.
I used Microsoft Excel to carry out this analysis, which involves data cleaning, creating of pivot tables and dashboard building.
The dataset was provided by Alex the Analyst and downloaded from Github. The dataset is about the bike sales of an unknown store and it contains 1026 rows and 13 columns. Its content includes data about the customer id, marital status, gender, income, children, education, occupation, homeowners, number of cars, commute, region, age, and purchased status.
 
For this project the steps I took includes:
Data cleaning
I checked and removed 26 duplicates leaving 1000 unique values.
Find and Replace: The Marital status
column has “M” and “s» which were
replaced with “Married” and “single”.
The Gender column has “M” and “F” and
was replaced with “Male” and “Female”, i added
a new column “Age Bracket =IF(L2>55, “Old”, IF(L2>=31,
“Middle Age”, IF(L2< 31, “Youth”.»I made this changes for easier understanding of the visualization.
