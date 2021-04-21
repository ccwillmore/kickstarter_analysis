# An Analysis of Kickstarter Campaign Data

## The goal of the analysis  
1.  Help the client plan a successful Kickstarter campaign to fund a theater production. 
2.  Help the client learn about Kickstarter campaigns to fund musicals in Great Britain
3.  Help the client learn more about funding for a set of 5 plays she saw at an Edinburgh festival.  

## Data and spreadsheet summary  
- [Click here to open the analysis spreadsheet](data-1-1-3-StarterBook_analysis.xlsx)
- The dataset contains data for 4,114 Kickstarter campaigns launched from 2009 and 2017.  
- The initial data are in columns A through N of the "Kickstarter" sheet of the spreadsheet.  
- The outcomes of the campaigns (column F) are conditionally formatted (green - successful, failed - red, yellow - canceled, and blue - failed)  
- The date that the campaign was launched (column J) and the deadline of the campaign (column I) are UNIX date stamp.  Columns are converted to deciferable dates in column S (date created conversion) and column T (deadline_conversion).  
- Columns O through U are calculated from the initial data.  
- The "category_statistics", subcategory_statistics", and "outcomes_based_on_Launch_date" sheets are pivot tables / charts  
- The "Great_Britain_musicals_box_plot" sheet displays data pulled from the "Kickstarter" sheet and depends on the filtering on "Kickstarter" sheet.  
- The "US Plays box plot" sheet is tied to the "Kickstarter" sheet and depends on the filtering of the Kickstarter sheet.
- The "failed_US_Kickstart_plays" sheet is data subsetted from the "Kickstarter" sheet and used for statistical analysis.  
- The "Successful_US_Kickstart_plays" sheet is data subsetted from the "Kickstarter" sheet and used for statistical analysis.  
- The "Kickstarter_plays_statistics_US" contains central tendency and spread calculations for both failed and successful US campaigns to fund plays  
- The "Edinburgh_research" sheet contains data for 5 plays subsetted from the "Kickstarter" sheet.  

## Results summary:  
In the US, from 2009 to 2017, there were 912 theater campaigns launched.  Of those, 525 campaigns met their goals, 349 failed.  
![](Parent_category_outcomes_theater_only.png)  
  
Of the theater campaigns, 671 were to fund plays.  Of those, 412 campaigns met their goals, 250 failed.  
![](Subcategory_outcomes_plays_only.png)  
  
Statistics for Kickstarger campaigns to fund plays in the US show the mean for both successful and failed campaigns being higher than the upper quartile.  
This suggests that the means are influenced by outliers.  
  
![text](US_Kickstart_Campaigns_plays_statistics.PNG)  
  
A box and whiskers plot for goals and pledges illustrates the number of outliers.  
  
![](US_plays_goal_pledged_box_plot_full_range.png)  
  
All points above the upper whickers of the plot are outliers.    
There are plays with goals similar to the customer's goal ($12,000) but they are considered to be outliers.  
  
For a better chance of success the customer should decrease the goal of the campaign to closer to $5,000.00  
  
Regardless of the campaign target amount the best months to launch a campaign to fund a play in the US are May, June, July, and august.  
  
![](Outcomes_based_on_launch_date_plays_only.png)  
  
 ## Musicals in Great Britain  
   
The client is interested in learning about campaigns to fund musicals in Great Britain.  She estimates that a future production would require 4,000 pound sterling to put on.  
There were 26 Kickstarter campaigns to fund musicals in Great Britain.  Of those, 10 were successful, 11 failed, and 5 were canceled.  
   
 ![](Subcategory_outcomes_musicals_in_GB.png)  

A box and whisker plot of The statistics suggest that the data have a positive skew from campaigns with high goals.  
  
![](Great_Britain_musicals_goal_pledged_box_plot.png)  
  
![](GB_Kickstart_Campaigns_musicals_statistics.PNG)  
  
Note that the funding received for musicals in Great Britain are lower that the client's proposed goal.  
Decreasing the goal to under 2,000 poounds sterling would help insure a successful campaign.  
  
##Edinburgh festival plays  
  
The client requested information on kickstarter campaigns for 5 plays she saw at an Edinburgh festival.  The data are summarized below.
  
![](Edinmurgh_research.PNG)  
  


