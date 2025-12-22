# Historical Automobile Sales Analysis
##### Python Mini Project Report

## Project Objective
The objective of this project is to analyze historical automobile sales data to understand how sales fluctuate over time, how different vehicle types behave during economic recessions, and how factors such as vehicle price and advertising expenditure influence sales performance.

Using Python, Pandas, and Matplotlib, this project aims to extract meaningful insights through data visualization and trend analysis, with a special focus on recession vs non-recession periods.

## Problem Statement
The automobile industry is highly sensitive to economic conditions. During recession periods, consumer purchasing power declines, which impacts vehicle sales, pricing strategies, and advertising investments.
The key problems addressed in this project are:
- How automobile sales change over time
- Whether different vehicle types respond differently during recessions
- How pricing affects sales volume during economic downturns
- How advertising expenditure is distributed between recession and non-recession periods
- Understanding these patterns helps businesses make data-driven decisions related to pricing, marketing, and inventory planning.

## Analysis
### 1. Year-Wise Automobile Sales Trend (Line Chart using Pandas)
- A line chart was created using Pandas’ plotting functionality to visualize total automobile sales year by year.
- The analysis shows clear fluctuations in sales over time.
- Noticeable declines in sales coincide with recession periods, indicating strong economic dependency.

#### Insight:
Automobile sales are cyclical and significantly impacted by economic slowdowns.

![Q1](https://github.com/KumarBoste/Historical_Automobile_Sales/blob/main/Python%20%20Analysis/Q1.png)

### 2. Vehicle Type Sales Trend During Recession (Multiple Line Chart)
-Sales trends for different vehicle categories (e.g., Small cars, Medium cars, SUVs) were plotted on the same graph.
- During recession periods:
  - Sales of luxury and high-priced vehicles declined sharply.
  - Economy and small vehicles showed comparatively stable demand.

#### Insight:
Yes, there is a noticeable difference in sales trends between vehicle types during recessions. Affordable vehicles are more resilient during economic downturns.

![Q2](https://github.com/KumarBoste/Historical_Automobile_Sales/blob/main/Python%20%20Analysis/Q2.png)

### 3. Comparison of Recession vs Non-Recession Sales (Matplotlib Visualization)
- Using Matplotlib, sales trends per vehicle type were compared between:
  - Recession periods
  - Non-recession periods
  
Sales volumes were significantly higher during non-recession periods across all vehicle types.

#### Insight:
Economic stability leads to higher consumer confidence and increased automobile sales, especially for premium vehicle categories.

![Q3](https://github.com/KumarBoste/Historical_Automobile_Sales/blob/main/Python%20%20Analysis/Q3.png)

### 4 Correlation Between Vehicle Price and Sales Volume (Scatter Plot)
- A scatter plot was created to study the relationship between:
  - Average vehicle price
  - Sales volume during recessions
- The plot indicates a negative correlation:
  - As vehicle prices increase, sales volume decreases during recessions.

#### Insight:
During recessions, consumers are more price-sensitive, leading to reduced sales of expensive vehicles.

![Q4](https://github.com/KumarBoste/Historical_Automobile_Sales/blob/main/Python%20%20Analysis/Q4.png)

### 5 Advertising Expenditure Distribution (Pie Chart)
- A pie chart was used to visualize advertising expenditure during:
  - Recession periods
  - Non-recession periods
- The chart shows lower advertising spending during recessions compared to non-recession periods.

#### Insight:
Companies tend to reduce marketing expenses during recessions to control costs, which may further impact sales.

![Q5](https://github.com/KumarBoste/Historical_Automobile_Sales/blob/main/Python%20%20Analysis/Q5.png)

## Conclusion
This project demonstrates how economic conditions significantly influence automobile sales performance. Through data visualization and analysis:
- Sales decline noticeably during recession periods
- Affordable vehicle types perform better during economic downturns
- Higher vehicle prices negatively affect sales during recessions
- Advertising expenditure is reduced during recessions, impacting market reach
Overall, the project highlights the importance of pricing strategy, vehicle segmentation, and marketing investment in sustaining automobile sales during challenging economic conditions.

## Tools & Technologies Used
- Python
  - Pandas
  - Matplotlib
  - Jupyter Notebook
