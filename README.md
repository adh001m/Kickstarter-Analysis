# Kickstarting with Excel
  An analysis of Kickstarter Campaigns
## Overview of Project
  Based on given Kickstarter data, filter data (for specific entertainment subcategories) and create two distinct graphs: Fundraising outcomes based on Goal and Fundraising outcomes based on launch date. Analyze the graphs.
### Purpose
  To familiarize oneself with basic excel commands for data filtration and analyzation, pivot tables, and charts. 
## Analysis and Challenges (Instructions)
  -Outcomes based on Launch Date: Create a PivotTable based off Kickstarter data based filtering theater outcomes by launch date and sorting them as a "successful", "failed", or "canceled" theater campaign. Add a line graph to further interpret your data.
  
  -Outcomes based on Goal: Use the "COUNTIFS()" statement to sort through "successful", "failed", and "canceled" play campaigns based off their intended goal range. Add a line graph to further interpret your data.
### Analysis of Outcomes Based on Launch Date
  In the beginning of May there is a spike in theatrical productions as opposed to the end of November. The "Failed" and "Succesful" outcomes move quite uniformely throughout the line graph, on the other hand, the "canceled" productions remain at a low level all throughout the graph. In December, the amount of "successful" productions decreases and intersects an increasing "failed" production line. A possible explanation for this could be from an increase in christmas related productions from higher-end companies and performers, therefore, this would cause the quantity of lower end productions, with fundraising pretenses, to decrease. Switching over to view the "canceled" productions amount, we can assume that most theatrical productions, performed under fundraising pretenses, tend to be enacted disregarding the success or failure when meeting their fundraising goal. 
### Analysis of Outcomes Based on Goals
  The success and failure rate of a play's campaign is directly related to its fundraising goal. Let's begin by disregarding the middle section of the graph because the vastly lower amount of play productions interferes with our percentage data. Disregarding the middle section, we see a high percentage of plays being successful in their fundraising campaign when there is a lower goal. Turning our attention towards the right side of the graph, we view several failed campaigns and very few successful campaigns as the fundraising goal increases.
### Challenges and Difficulties Encountered
Initially I struggled implementing the range for the "Goal Outcome" Chart using COUNTIFS() statements, however, after some research I facilitated my struggle.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1) Theater productions fundraising campaigns are most popular in May.
2) Theater productions, under fundraising pretenses, are rarely canceled and usually enacted despite the inteded goal.

- What can you conclude about the Outcomes based on Goals?

  It is ideal, for play productions, to set low fundraising goals in order to increase the likelihood of achieving their fundraising.

- What are some limitations of this dataset?

  The "outcomes based on goals" data set is limited by the percentage rate. As quantities vastly decrease for "successful", "failed", and "canceled" outcomes, the realize that the lower ratios hold as much power as a higher ratio and therefore doesn't best reflect our data. For instance, a ratio of 1000 successful campaigns to zero failed campaigns is ultimately the same ratio as one failed campaign to zero successful campaigns.

- What are some other possible tables and/or graphs that we could create?

  We could create a bar graph instead in order to view the amount of "successful", "failed", and "canceled" campaigns. This would allow us to avoid the confusion given by ratios by switching to a more organized numeric system. It is better to view the values of each campaign individually rather than as a ratio.
