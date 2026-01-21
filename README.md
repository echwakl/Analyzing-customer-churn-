# Analysis of Churn rate of customers

## Object Objective
The stakeholder holders want to create a report to show the number of customers churning and the reasons of caused mainly due to competitors. 

## Data Used
- <a href="https://github.com/echwakl/Analyzing-customer-churn-/commit/bedc018e53500f262b0a529873c3dbb0e70bf285">Dataset</a>

## Questions
- Count of customers who have churned
- Count of customers who have not churned
- Create a new column "Churned" in our Customers table that uses an IF() to convert the values in Churn Label based on the following criteria: "Yes" then 1  "No" then O
-Create a blank PivotTable of the Customers table and place it in a new Worksheet
-Display the total count of customers and number of churned customers.
-Create a new calculation with the header "Churn Rate" that divides churned customers by total customers.
-Format this as a % to two decimal places.
- Analyze the total number of churned customers by Churn Reason
- Order the churn reasons ascending, to the most popular churn reason appears at the bottom .
-Show the Churned Customers as a "% of Grand Total"
-Order the churn reasons ascending, to the most popular churn reason appears at the bottom .
-Show the Churned Customers as a "% of Grand Total"
-Which of the following is part of the top 3 churn reasons?
-Analyze the total number of churned customers as % of grand total by Churn Category and Churn Reason
-Filter the PivotTable to only include highest % of churn is Competitor
-What % of customers churned due to "Competitor made better offer"? Rounded to two decimal places.

  ## Process
  - Verifying data for missing values anamolies and sort out the same
  - Made sure data is consistence and clean wrt to data type, format andvalues used.
  - Created Pivot tables and charts according to the questions asked
  - Merge all Pivot charts into one dashboard and apply slicers to make dynamic
 
    ## Dashboard Interactions
     ![Dashboard](https://github.com/user-attachments/assets/587a9e6d-ecf8-4229-a90c-27193fdf1058)

    ## Project Insights
    Total number of churned customers is 1796. Total churn rate in % is 26.86%. Top 3 churn reasons are. Attitude of support person, Competitor had better device and Competitor had made a better offer. % of customers churned due to "Competitor made better offer" is 37.64 %

