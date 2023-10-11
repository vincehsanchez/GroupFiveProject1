# Unemployment and Healthcare

The effects of unemployment on a person's health and wellbeing, specifically heart diease.

### Group Members:

- Davit Mirzoyan
- Valentina Hernandez
- Fesseha Habtiymer
- Vince Sanchez

## Research Questions:
1. How does unemployment affect heart disease?
2. How does the analysis differ based on years?
3. Does the analysis have statistical significance?

## Datasets Used:
- Bureau of Labor Statistics (BLS)
  
  Unemployment datasets from 2014 to 2021
  
- Centers for Disease Control and Prevention (CDC)
  
  Heart disease mortality rates from 2014 to 2021

## Breakdown of Tasks:
- Identify the data that will be used with the timeframe.
- Analyze the data to find trends or lack thereof.
- Create charts to present the findings.
- Implications of findings (what do they mean)
- Identify the limitations of the analysis or data used.

## What did we do?
**Breakdown**

We gathered data between the years of 2005 and 2021 for large enough spread of data to illustrate a trend. 
1. Downloaded U.S. unemployment data from “Employment Situation Summary” off the BLS website between the years of 2004 and 2021.
2. Downloaded U.S. heart disease data from “Heart Disease Mortality by State” off CDC website between 2005 and 2021.

**Cleaning Up**
Initially, we wanted to do 16 points of data, but we came to find out that the CDC omitted data between the years of 2006-2013 for our heart disease data. 
One challenge we faced was attempting to collect data from CDC WONDER to fill in for the omitted years, but we were unable to find the specific criteria for “Heart Disease Mortality by State”. So, we limited our data between the years of 2014-2021 for both mortality total from heart disease and the total number of unemployed. 
Another challenge was working with some unreadable data from our heart_data.csv file which, James Wrenn (our TA), swiftly came to our rescue and shared the realistic takeaways from this exercise. We diagnosed the issue of incorrect totals due hidden quotation marks within the csv file. We confirmed by copying data into a text file and removing quotations, pasting it back into the CSV file, and then fixing it by changing the format of the column to “Numbers” within Excel. Once data was readable, we tidied it up more by adding the mortality total from heart disease of each state per year using groupby and sum.

**What we saw**
We plotted the years and mortality total from heart disease as one line graph and the years versus unemployed total as a line graph.
Afterward, we plotted the line graphs against each other, and it was unremarkable, but we noticed that we were comparing two y values that did not complement each other. So, we made two different y values to better fit and compare our data.
The unemployment number and heart disease mortality total intersected once between 2015-2016, both showed to trend upward from 2019, converging in 2020, and quickly diverging the following year. 

**what predictions did we draw from data?**
Although we are dealing with the thousands for unemployment it was compared to the hundreds of thousands for heart disease mortality, there were still points of intersection so we can suspect an interaction between the two. 
Beginning in 2014 we see unemployment rise while heart disease mortalities decreases and/or stabilizes, so as the years go on heart disease has a significant effect meanwhile unemployment steadily rises indicating the years have significant effect. 
They intersect one another from opposite directions in <input year here> showing us the effects of each passing year. 
Not too long afterward the two lines slowly converge with one another in <input year here> indicating a possible significance since years affect the total number of unemployment and heart disease mortality. 
Immediately after converging they diverge into opposite directions indicating that the y-values have a significant effect.

(what justifications can we present to our predictions?)

**Statistical significance?**
Using the <input what Davit used> we cannot confidently say that the unemployment affects the mortality of heart disease or any development of it. We can almost say that we see the opposite effects of unemployment or that possibly other external factors such as world events independently affect the unemployment numbers and heart disease mortality.

**Data Limitations Disclosure**
We were limited to the criteria for “Heart Disease Mortality by State” from the CDC data and the years provided. If we had more time, we could have made our own criteria too add up all heart disease mortalities for different age groups that have jobs and we could have compared different age groups for each year to see any trends. 


## Works Cited

_The Centers for Disease Control and Prevention_. Heart Disease Mortality by State, https://www.cdc.gov/nchs/pressroom/sosmap/heart_disease_mortality/heart_disease.htm)https://www.cdc.gov/nchs/pressroom/sosmap/heart_disease_mortality/heart_disease.htm. Accessed 02 Oct. 2023.

_U.S. BUREAU OF LABOR STATISTICS. Employment Situation Summary_, https://www.bls.gov/charts/employment-situation/civilian-unemployment.htm. Accessed 02 Oct. 2023.
