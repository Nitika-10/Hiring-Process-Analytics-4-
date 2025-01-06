![Bar chart](https://github.com/user-attachments/assets/8f71744a-0cfe-4347-b7db-e3a17d24fde6)![image](https://github.com/user-attachments/assets/8faae640-6d15-4e13-ba3b-aba6efcf2ade)# Hiring-Process-Analytics-4-
This project analyzes hiring process data to optimize recruitment strategies, identify bottlenecks, and improve candidate experience. It provides actionable insights for efficient talent acquisition. (Pipeline Analysis, Metrics Tracking, Bottleneck Identification, Visualization, Actionable Insight).s

Hiring Process Analytics

Project Description:

The project aims to analyse the hiring process of a company and provide insights. The analysis will be done using Excel and statistical techniques such as regression analysis and hypothesis testing.

Approach :

First of all I have removed the missing data ( there was only one row containing missing data).

Secondly, I performed outlier analysis where I found there were 3 rows with very high salary and 2 rows with very low salary, so I deleted these 5 rows.

Then started analysing and answering questions.

Tech Stack used:

MS Excel
INSIGHTS :

A - Hiring:

To filter rows on the basis of gender that are hired, we can use COUNTIFS function in MS Excel.

Male : = COUNTIFS( D2:D7165,"Male",C2:C7165,"Hired")

Result : 2560

Female : = COUNTIFS( D2:D7165,"Female",C2:C7165,"Hired")

Result : 1856

B - Average Salary :

To find the average salary we can use AVERAGE function in MS Excel :

Average Salary : =AVERAGE(G2:G7163)

Result : 49892.13

C - Class Intervals :

We can directly make a class interval table using the data analysis tools present in MS Excel. To acces this tool -

Data > Analyze > Data Analysis > Histogram

Bin	Frequency
10000	676
---	---
20000	732
30000	711
40000	710
50000	781
60000	750
70000	698
80000	734
90000	711
100000	659
D - Charts and Plots:

We can make the required chart using pivot charts.

But first we have to make Pivot table that shows the count of employees in each department –

Department	Count of Department
Finance Department	288
---	---
General Management	172
Human Resource Department	97
Marketing Department	325
Operations Department	2771
Production Department	380
Purchase Department	333
Sales Department	746
Service Department	2055
Now we can insert bar chart and pie charts.

Bar Chart

![Bar chart](https://github.com/user-attachments/assets/1597828f-21bd-4ef4-9491-758693c2d8c2)


Pie chart

![pie chart](https://github.com/user-attachments/assets/0f98d779-461a-4c0c-be4f-de9c65b4e8bf)


E - Charts:

I have prepared a chart that shows average salary offered to each post tier.

![last chart](https://github.com/user-attachments/assets/34f4faca-6915-4c7e-867c-ab9c7cbc5572)


Results –

I have learned how to manipulate data in MS Excel, along with functions, pivot tables and charts & graphs.

This will help me for analyzing and performing EDA in MS Excel.
