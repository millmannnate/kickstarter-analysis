# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
The kickstarter project was done to analyze different fundraising campaigns. Louise wanted to know how previous campaigns differed in launch dates and funding goals. Using the kickstarter data, elements were pulled to compare the campaigns on their successfulness. The resulting tables and graphs help Louise to make the best decision regarding her campaign endeavors.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
To look at the outcomes based on launch date, I created a pivot table using the kickstarter data. I filtered the data to only use the theater category that Louise was looking at. The pivot table I created used months and outcomes to display the data. The values were a count of the outcomes that satisfy each constraint. I then created a line chart for the pivot table that showed the relationship between the launch date months and the number of campaigns of each outcome. 

The goal-based analysis used the COUNTIFS() function to pull data from the kickstarter data. The table created contained the number of successful, failed, and canceled campaigns for each goal step. Total projects were calculated in each goal step using the SUM() function. Using the total projects, I was able to calculate the percentages for successful, failed, and canceled campaigns. I created a line chart using that table to display the percentages for each goal step.

I found it to be challenging using the long COUNTIF() functions in the "outcomes based on goals" analysis. I had to go through those a few times to get the exact filter that I needed for each cell.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
