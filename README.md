# Kickstarter Analysis for Louise

## Overview of Project
As you well know, we worked together to plan the kickstarter for your play *Fever*. After witnessing the outcome of that kickstarter you asked that I do some comparison analysis for theater kickstarter.
### Purpose
Specifically, this analysis looks at the correlation between launch date and kickstarter outcome as well as the goal amount and kickstarter outcome.

## Analysis and Challenges
Using the same data previously used for determining the kickstarter goals for *Fever*, I created new pivot tables and formulas within Excel to determine how **Theater** and **Plays** fared in relation to launch dates and funding goals.    
### Analysis of Outcomes Based on Launch Date
The study sample included data from 2009 to 2017. Launch dates of **Theater** kickstarters were grouped by months and a pivot table was used to find totals by month of successful, failed, and canceled kickstarters.
### Analysis of Outcomes Based on Goals
For outcomes based on goals, the same data set was used however I focused on **Plays**, which is a subset of **Theater**. was divided into groups based on the goal value. Different currencies were treated as equal values. Groupings started with less than 1000 and then 5000 increments till 50,000 and greater. Using Excel formulas a table and graph were created showing percentages of the total for each value increment.
### Challenges and Difficulties Encountered
It wasn't until I was creating the graphs that I realized that the values of the goals were in different currencies, therefore the goal axes could not be labeled *Dollars* or *Pounds*. This adds a possible inconsistency in the data depending on the currency exchange rates at the time of the kickstarter.

## Results
* As shown in graph *Theater Outcomes Based on Launch Date* (below), **Theater** kickstarters launched in May and June have a greater chance of reaching their goal in comparison to other months. This advantage does not, however, appear to be extreme. The spike shown on the graph is partly a result of May and June have the largest number of kickstarters.
In addition to December having the least number of kickstarters launching, it also has the smallest percentage of successful percentages. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100614690/161425333-88cb4a55-d306-4566-811e-3765f54d3208.png)


* The graph *Outcomes Based on Goal* (below) shows an analysis of **Plays** kickstarters. No **Plays** kickstarters were cancelled, therefore, the line graph of successful and failed are mirror images of each other along the 50% horizontal. Based solely on goals, setting a goal of less than 1000 or 1000 to 4999 offers the greatest chance of meeting the goal with 76% and 73% sucessful respectfully.
* 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100614690/161425365-bccbd73f-fe43-4126-a5f3-13c18dda09f4.png)


### Limitations and Future Analysis
* The greatest limitation of the dataset used in this analysis was the small number of data points for larger goal kickstarters. 
* Available data for the month of December appears lower than statistically expected. It is not clear if December truly has less kickstarter launches or there is missing data for that month.

* In order to truly compare the results of the *Fever* kickstarter, the analysis based on launch date should have been limited to the **Plays** subset. 

* Further tables could include the number of days of kickstarters, primarily to see if duration affected success. It could also go a step further to add month of launch or season if lumping is needed to have a large enough data set.

* Country of origin should also be added. Are **Plays** kickstarters more likely to succeed in the US or GB? However, if the data set is not large enough, this may not be feasible.




