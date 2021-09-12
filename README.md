# kickstarter-analysis

## Overview of Project

### Purpose
For this project I was tasked with finding out and analysing theater
kickstarter campaigns and how they faired based on both the date they launched and their goals that they set for themselves. This analysis and data can be used to gauge how laucnh date and initial goals effect the success rate of kickstarter campaigns for theater projects, this will then allow for others to determine their plan based on the findings.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To perform the analysis of outcomes based on a campaigns launch date I first had to convert the date that was given, which was in mm/dd/yyy format, to just give me the year. To do this I created a new column and used the excel 'Year()' to extract just the year from the launch date. After this I created a pivot table filtered by the Parent category, the type of campaign which was filtered to theater, and years. This pivot table allowed me to see the number of failed, successful, or canceled campaigns for every month in particular years or every year. 
### Analysis of Outcomes Based on Goals
For the analysis of outcomes based on goals I first had to create a new worksheet and create a table  to show the number of projects that were successful, failed, or canceled and then show the percentage of those categories based on the range that the initial goal fell into. To fill this new table i used the excel 'COUNTIFS()' function to parse through the data and count the data only if it fell into the specific range and category. I then found the percentag of failed, successful and canceled projects based on the goal ranges.
### Challenges and Difficulties Encountered
During the process of this project and subsequent analysis I luckily ran into a very minimal number of difficulties. The biggest challenge/difficulty I ran into was getting the pivot table for outcomes based on launch dates to display the months in the first column. I was able to overcome this by looking back at previous work I had done. Possible challenges I believe could have been encountered was potentially messing up when writing the the criteria for the 'COUNTIFS()' function as it was a lot of repetition and was very much a place for potential typos that could have messed with the data set.
## Results
### Theater Outcomes Based on Launch Date
One conclusion that I can draw about the Outcomes based on Launch Date is that it seems that while the number of successful campaigns never dipped below the number of failed, the later months of the year, Aug-Dec, seemed to have had the largest decrease of successful campaigns. Another conclusion that can be drawn from this is that it seems the potential for a campaign to be canceled is not that dependent on the month and is probabaly based on external factors not in the dataset. See chart below.

![alt text](https://github.com/Cdonovan87/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Outcomes Based on Goal
Based on the numbers and subsequent line chart I can conclude that as the range of the initial goal number increased there was a subsequent increase in the percentage of failed campaigns and decrease in the percentage for successful campaigns. However there is a point where percent successful goes back ahead of failed but it then quickly reverses which could be from the presence of some outliers. See chart below.

![alt text](https://github.com/Cdonovan87/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Dataset Limitations
One limitation that I gleemed is that The dataset only has data from the years 2014, 2015, and 2016 which could lead to out of date data. Another limitation is that the data doesn't take into account external factors like economy of the certain year, and potential world wide events that could have happened to prevent people from pledgeing to campaigns.
### Other Potential Graphs/Tables
Many different graphs and tables could be made from this data. One graph that could be made is on the numbers of backers for a campaign and how well the campaign did(number/percentage). We could also make graphs based on the average donation for each campaign and how that effected the outcome of the campaign and you could also throw in the number of backers within this graph aswell. 
