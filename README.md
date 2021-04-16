# An Analysis of Kickstarter Campaign Data

The goal of the analysis is to
1.  Help the client plan a successful Kickstarter campaign to fund a theater production. 
2.  Help the client learn about Kickstarter campaigns to fund musicals in Great Britain
3.  Help the client learn more about funding for a set of 5 plays she saw at an Edinburgh festival.  

Data and spreadsheet summary:  
- The dataset contains data for 4,114 Kickstarter campaigns launched from 2009 and 2017.  
- The initial data are in columns A through N of the "Kickstarter" sheet of the spreadsheet.  
- The outcomes of the campaigns (column F) are conditionally formatted (green - successful, failed - red, yellow - canceled, and blue - failed)  
- The date that the campaign was launched (column J) and the deadline of the campaign (column I) are UNIX date stamp.  Columns are converted to deciferable dates in column S (date created conversion) and column T (deadline_conversion).  
- Columns O through U are calculated from the initial data.  
- The "category_statistics", subcategory_statistics", and "outcomes_based_on_Launch_date" sheets are pivot tables / charts  
- The "Great_Britain_musicals_box_plot" sheet displays data pulled from the "Kickstarter" sheet and depends on the filtering on "Kickstarter" sheet.  
- The "failed_US_Kickstart_plays" sheet is data subsetted from the "Kickstarter" sheet and used for statistical analysis.  
- The "Successful_US_Kickstart_plays" sheet is data subsetted from the "Kickstarter" sheet and used for statistical analysis.  
- The "Kickstarter_plays_statistics_US" contains central tendency and spread calculations for both failed and successful US campaigns to fund plays  
- The "Edinburgh_research" sheet contains data for 5 plays subsetted from the "Kickstarter" sheet.  

Results summary:  
In the US, from 2009 to 2017, there were 912 theater campaigns launched.  Of those, 525 campaigns met their goals, 349 failed.  
![US Theater campaign outcome counts](C:\Users\User\Desktop\Analysis_Projects\Crowdfunding_Project\Parent_category_outcomes_theater_only.png)  
Of the theater campaigns, 671 were to fund plays.  Of those, 412 campaigns met their goals, 250 failed.  
Link to plot



