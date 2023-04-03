Hiring Process Analytics

Project Description:

The project aims to analyse the hiring process of a company and provide insights. The analysis will be done using Excel and statistical techniques such as regression analysis and hypothesis testing.

Approach :

First of all I have removed the missing data ( there was only one row containing missing data).

Secondly, I performed outlier analysis where I found there were 3 rows with very high salary and 2 rows with very low salary, so I deleted these 5 rows.

Then started analysing and answering questions.

Tech Stack used:

1. MS Excel

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

Data \> Analyze \> Data Analysis \> Histogram

| _Bin_ | _Frequency_ |
| --- | --- |
| 10000 | 676 |
| --- | --- |
| 20000 | 732 |
| 30000 | 711 |
| 40000 | 710 |
| 50000 | 781 |
| 60000 | 750 |
| 70000 | 698 |
| 80000 | 734 |
| 90000 | 711 |
| 100000 | 659 |

D - Charts and Plots:

We can make the required chart using pivot charts.

But first we have to make Pivot table that shows the _count_ of employees in each department –

| **Department** | **Count of Department** |
| --- | --- |
| Finance Department | 288 |
| --- | --- |
| General Management | 172 |
| Human Resource Department | 97 |
| Marketing Department | 325 |
| Operations Department | 2771 |
| Production Department | 380 |
| Purchase Department | 333 |
| Sales Department | 746 |
| Service Department | 2055 |

Now we can insert bar chart and pie charts.

![alt text](https://github.com/hashimali179/Trainity-Projects/blob/main/4%20-%20Hiring%20Process%20Analytics/bar%20chart.png)


Bar Chart

![alt text](https://github.com/hashimali179/Trainity-Projects/blob/main/4%20-%20Hiring%20Process%20Analytics/pie%20chart.png)


Pie chart

E - Charts:

I have prepared a chart that shows average salary offered to each post tier.

![alt text](https://github.com/hashimali179/Trainity-Projects/blob/main/4%20-%20Hiring%20Process%20Analytics/last%20chart.png)


Results –

I have learned how to manipulate data in MS Excel, along with functions, pivot tables and charts & graphs.

This will help me for analyzing and performing EDA in MS Excel.
