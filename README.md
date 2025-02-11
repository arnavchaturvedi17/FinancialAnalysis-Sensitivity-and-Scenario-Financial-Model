# Financial Analysis: Sensitivity & Scenario Analysis Financial-Model
## Portfolio Project Overview:
A new start-up retail business is seeking to analyze its financials to explore effects of price changes and forecasts of revenue. As a financial analyst, I created this sensitivity & scenario financial model for this retail company. 
In this financial analysis, following financial concepts were explored:
* Sensitivity table to see what different price changes affect the business.
* Scenario analysis to see how different forecasts affect the bottom line.
* Use of “Goal Seek” and “Solver” features to see how much we need to sell to reach our financial goals.

![image](https://github.com/user-attachments/assets/915416ea-01fc-46cd-9d75-99dbf9d84236)
![image](https://github.com/user-attachments/assets/915416ea-01fc-46cd-9d75-99dbf9d84236)

## Business Problem Scenarios, Objectives and KPIs:
The finance manager in this retail company would like to explore effects of price changes and forecasts of revenue.  
He/she would like to know few questions such as…
* How many sales do we need to generate to make a million dollars?
* How different revenue and cost forecast will affect profitability? (base, best, and worst-case scenario)

## Target Stakeholders:
This financial analysis tool will be used for the following job roles to increase their productivity and achieve business goals:
* Finance Manager
* Chief Finance Officer (CFO)
* Financial Analysts
* Business Analysts
* Financial Auditors

## Skills and Applications used: 
* Microsoft Excel 
  * Knowledge of formulae and functions to be used in any typical financial data analytical solutions.
  * Manipulations of Excel’s Table component to create Sensitivity Table, Scenario analysis, Goal Seek and Solver. 

* SME (Subject Matter Expertise)
  * Business requirement gathering skill and techniques.
  * Finance knowledge and expertise.

A "Sensitivity and Scenario Analysis" financial model is a tool used to assess how changes in key input variables, like sales volume or costs, affect the overall financial outcome of a project or business by systematically altering their values within a specified range, allowing for the evaluation of various potential scenarios and their impact on the results, essentially answering "what-if" questions to understand the level of risk involved. 

In financial modeling, sensitivity analysis and scenario analysis are ways to test how changes to inputs impact a model's output. 
Sensitivity analysis 
* Involves changing one input variable at a time
* Shows how sensitive the model is to changes in that variable
* Helps identify which variables are most important to the model
Scenario analysis 
* Involves changing the value of multiple inputs at once
* Provides a broader view of potential outcomes
* Helps visualize best, base, and worst-case situations

## Solution Approach and Process to build this project:
For this financial modelling, I created 3 worksheets in attached Excel file (i) Goal Seek/Solver (ii) Sensitivity Table (iii) Scenario Analysis. 

1.	Goal Seek / Solver: using goal seek, we can find an input to reach our desired output. For example, how many sales do we need to generate to make a million dollars. Excel Solver is the advanced version of this, where we can choose multiple inputs and set constraints to reach our desired output. 
2.	Sensitivity Analysis: using a sensitivity analysis table we can evaluate how changing a set of inputs will affect our profitability. The inputs we change are the price range and the quantity sold range. This is one of the functions on the What-If-Analysis section under the data tab of Excel. 
3.	Scenario Analysis: using a scenario analysis, we can see how different revenue and cost forecast will affect our profitability. For this we create a base, best, and worst-case scenario, and use the choose formula to create a dynamic model.

### For Goal Seek: 
Used Advanced feature in MS-Excel ( Data  What-If-Analysis  Goal Seek ). Goal: 100K in Net Income

### For Solver: 
Used Advanced feature in MS-Excel  (‘Solver’ Add-in).

![image](https://github.com/user-attachments/assets/40aa615e-3650-4638-8ac6-cca42cc135b3)
![image](https://github.com/user-attachments/assets/40aa615e-3650-4638-8ac6-cca42cc135b3)


### For Sensitivity Analysis:
One of the limiting factors with Goal Seek as well as Solver is that we only had one final output, so we had one price per unit as well as one quantity sold. But now it would be nice to have a whole range. So, what if the price increased by one (or what if it decreased by one) then what would happen to out net income?
All these things we can do using the sensitivity analysis. 
In Sensitivity table… 
* I defined ranges for Price per unit and Quantity Sold. 
* Dynamically linked table to Net Income (Loss) constraint value.
* Used Advanced feature in MS-Excel (Data  What-If-Analysis  Data Table). Linked this to Unit Sold and Price per Unit to populate sensitivity table. Now, this sensitivity table show us how Net Income is changing (or sensitive to) based on selected Quantity Sold and Price per Unit values.
* Sensitivity analysis is very common in stock market’s share price analysis i.e. share price movement and how it might be affected by different growth rates, different discount rates and other factors that that.
![image](https://github.com/user-attachments/assets/790b7517-2e36-460d-a12f-db1c73f37c74)
![image](https://github.com/user-attachments/assets/790b7517-2e36-460d-a12f-db1c73f37c74)

### For Scenario Analysis:
This is most useful for forecasting. For example, our startup business is very new to we really don’t know what our revenues going to look like in future, what our costs going to look like in future. These questions can be answered by scenario analysis.
* I created 3 different scenarios: A Best Case, A Base case, A Worst Case.
* Used Excel’s CHOOSE() formula to define revenue and cost values for selected scenario,
* Used Data  Data Validation feature to constraints scenario selection within our defined values only (i.e. drop-down list).
* Used Formula  Trace Precedents feature which shows links visually i.e. where formula is linked in sheet. This is very helpful to understand/trace financial formulas used and resolve any issues.
* Used Group and Ungroup rows in Excel sheet to show or hide few rows if our Excel sheet is too big to show data on screen.

![image](https://github.com/user-attachments/assets/6f551d5a-538e-42b2-b160-fafb5540d366)
![image](https://github.com/user-attachments/assets/6f551d5a-538e-42b2-b160-fafb5540d366)

![image](https://github.com/user-attachments/assets/680060d3-342f-4cef-9cf3-caf86baa09e6)
![image](https://github.com/user-attachments/assets/680060d3-342f-4cef-9cf3-caf86baa09e6)

![image](https://github.com/user-attachments/assets/65368450-732b-42c9-a0b8-c9ddef351c87)
![image](https://github.com/user-attachments/assets/65368450-732b-42c9-a0b8-c9ddef351c87)


### Portfolio Project Documentation (Final Conclusion):
Documentation: 
•	ReadMe-Financial-Analysis-Sensitivity-Scenario-Analysis-Excel

### Output File:
•	Financial_Analysis_Scenario_Sensitivity.xlsx








