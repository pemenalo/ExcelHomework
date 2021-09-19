# ExcelHomework
Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

Task 1: Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Task 2: Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

![Excel-sheet](Excel-images/excel-1.PNG)

Task 3: Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

Task 4: Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

Task 5: Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

![Excel-sheet2](Excel-images/excel-2.PNG)

Task 6: Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

Task 7: Create a stacked column pivot chart that can be filtered by country based on the table you have created.

![Excel-sheet2](Excel-images/graph-1.PNG)

Task 8: Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

Task 9: Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

![Excel-sheet2](Excel-images/graph-2.PNG)

Task 10: Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

Task 11: Now create a pivot chart line graph that visualizes this new table.

![Excel-sheet2](Excel-images/graph-3.PNG)

Questions Answered: 
1. 3 conclusions from the data:
a.	Theater Kickstarter campaigns are successful more that 60% of the time and more that 50% more successful than other categories. 
b.	Kickstarter campaigns for, plays specifically, are successful in reaching their funding goal approximately two times as much as they are to fail at reaching their goal.  
c.	The most successful Kickstarter campaigns occur during the months of May and June. I would advise anyone interested in hosting a Kickstarter campaign to run it during those months. 
2.	Limitations of the data:
a.	The forms of currency the campaigns used varied, and this can change the significance of the funding levels each campaign reached due to the different currency exchange and value rates. 
b.	Limited information of the campaigns skews the data. Campaigns varied in size and goal level. Certain campaigns may have been less complex and less in need of funding and therefore could reach their goal easier or with less backers and vice versa. 
c.	The data points are not consistent across the board such as campaign run length. The campaigns ran for various lengths of time which could have allowed campaigns more time to reach their goal or less time to reach their goal. 
3.	Other possible tables:
a.	We could create a pie graph to depict the share of pledged amount from backers by category and sub-category. 
b.	We could create a bar graph to depict the average campaign run time by category and sub-category. 
c.	We could create a stacked bar graph to depict the sum of backers per category and filter by state of success or failure. 

Bonus
Task 1: Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data.

Task 2: Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

Task 3: Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

![Excel-sheet2](Excel-images/graph-4.PNG)
