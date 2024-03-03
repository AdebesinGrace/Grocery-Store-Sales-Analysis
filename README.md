# Grocery-Store-Sales-Analysis

![Intro Picture](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/28dce9a5-4224-4449-8a29-0c814f56acc3)


## Introduction 
This is an Excel Project on sales analysis. The purpose of this project is to analyze and derive insights to answer crucial questions and help the store make data-driven decisions.


## Data Source
This data was obtained on Kaggle
![Data Source](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/5c2aadc5-890d-405f-84d4-17f933522680)


## Problem Statement
1.	Which product categories contribute the most to our overall sales?
2.	Which regions are generating the highest profits?
3.	What percentage of total sales comes from each region?
4.	How do weekly sales vary throughout the year?
5.	Which combination of category and region is the most profitable?
6.	How are actual sales performing against targets set for different regions?
7.	Which categories or regions are underperforming compared to others?

## Skills/Concept Demonstrated:
- Power Query
- Analysis Toolpak  

## Analysis Process
After downloading the data, I proceeded to load it into the Power Query editor  to transform.
![Power Query](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/be9cfcc4-d6d4-466f-a19b-a99ca026531a)
![Power Query](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/193ea277-7946-43ce-99b4-d7d49aab5973)

Performed summary statistics using Analysis Toolpak and used some lookup functions to derive the region where the maximum profit and the minimum profit falls 
![Statistics   Excel Formula](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/a3ef4ebc-822e-46ad-a493-627db54c837a)
I used the SUMIF formula to find out the sum of sales greater than $1000 and sales lesser than $1000. I also used the COUNTIF formula to get the number of each region.

## Visualization 
We create pivot charts by going to the insert option and clicking on the pivot table or selecting a range of data and using quick analysis. I built 4 pivot tables consisting of 3 column charts and 1 pie chart.
The first column chart visualizes the sales of each category. The egg, meat, and fish category contributed the most to the overall sales performance, which solves our first problem statement while Oil and Masala made the least sales. The Second column chart visualizes the Total profit each region made. West made the highest profit close to $1200000 while North made the least.  The pie chart visualized the percentage of sales each region made. West made 32%, North 0%, South 16%, East 29%, and Central 23%. The last column chart visualizes the average sales made per week and Sunday appears to be a busy day with the highest average sales. I created slicers for easy filtering of the data in the charts and report connections between all the pivot tables. I formatted my charts, copied them to a new worksheet, arranged them, and removed the gridlines using ALT+W+V+G. I labeled my axis and titles. I named my dashboard and I'm done with building the dashboard in Excel.
![Dashboard](https://github.com/AdebesinGrace/Grocery-Store-Sales-Analysis/assets/161143562/fde708d9-c86f-4724-ba03-d6cdbc17afad)


## Conclusion & Recommendation
- West has the highest impact on the sales of the store

### Recommendation
For a deep dive into the analytics, the datasets of the previous years will be required for comparison and data-driven decision-making.
