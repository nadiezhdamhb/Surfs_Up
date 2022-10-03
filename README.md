### Module 9: Surf's Up with Advanced Data Storage and Retrieval
<p align="center" width="100%">
    <img width="66%" src="https://github.com/nadiezhdamhb/Surfs_Up/blob/main/Resources/Surfboards_Pic.jpg">

## Overview

*Background and Purpose:*
W. Avy is planning to open a surf and ice cream shop in Hawaii but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.* 

By retrieving the data from the SQLite file, the Oahu temperatures for the months of June and December can be analyzed using summary statistics. Comparing the differences between these two datasets will help develop the analysis further. 

# Results

**Methods used for Deliverables**
    
1. Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the `Measurements` table in the `hawaii.sqlite` database to retrieve the temperatures for the month of June and December. 
2. Additionally, I converted the temperatures to a list and then created a DataFrame. 
3. Finally, I generated the summary statistics for June and December temperatures DataFrames. 

**Deliverable 1: Determine the Summary Statistics for June**

![](https://github.com/nadiezhdamhb/Surfs_Up/blob/main/Resources/June_Temperatures_Final.JPG)



![](https://github.com/nadiezhdamhb/Surfs_Up/blob/main/Resources/June_stats.png)



**Deliverable 2: Determine the Summary Statistics for December**

![](https://github.com/nadiezhdamhb/Surfs_Up/blob/main/Resources/December_Temperatures_Final.png)



![](https://github.com/nadiezhdamhb/Surfs_Up/blob/main/Resources/Dec_stats.png)


3. Summary statistics for June and December 

- The maximum temperatures are very similar: with June's max being 85 and December's being 83.  

- June's minimum temp. is 64 and December's minimum is 56. There is a big difference in min temp. 

- The means compare similarly to the maximums: with June's at 75 and December's at 71. 


# Summary 

The data and statistics analysis show that the temperatures between June and December are quite similar indicating that the ice cream shop could succeed in both the summer as well as the winter. An additional way to look at the summary statistics is to compare the standard deviations. Both June and Decemmber stats show a standard devation of 3.25 and 3.75 respectively. This means that the temperature does not spread very far apart. This is another promising indicator that sales could be steady throughout the year due to the continous warmer weather year-round.

My recommendation is that further analysis is necessary to include other factors that could affect the ice cream business. One factor would be to add the amount of tourist visiting the island every month to see which months could potentially have higher sales. 
Another factor could be the fact that the island is in a tropical climate, therefore it is very important to factor in the amount of precipitation, duration and frequency througout the year since people don't really go out or visit the beach when is raining and this could affect the business profit. 
