# Kickstarting with Excel

## **Overview of Project**
Performing analysis on Kickstarter data to uncover trends
### Purpose
*Utilize a large set of data for global Kickstarter programs to help inform Louise for her upcoming Kickstarter project. Specifically, Analyzing global theater outcomes and the relation of their launch dates to their success. In addition, to analyzing global plays and the relation of their funding goals to the outcome of the projects. 
## **Analysis and Challenges** 
### Analysis of Theater Outcomes Based on Launch Date
*Analysis of theater outcomes based on launch date looked at specifically the data around the Kickstarter parent category Theaters. From there the data was broken out to analyze the outcomes of Theater productions for multiple years on a monthly cadence. The graph illustrates how many Theater productions were successful, failed or were canceled by month.  
![image_name](path/to/image_name.png)
### Analysis of Outcomes Based on Goals
*Analysis of outcomes based on goals looked at specifically the data for Kickstarters subparent category on plays. From there the data was broken out into different goal ranges to highlight how my plays were successful, failed or were canceled within those specific goal ranges. The chart indicates how many plays were successful, failed or were canceled based on their goal amount. 
![image_name](path/to/image_name.png)
### Challenges and Difficulties Encountered 
* A challenge that arose in the outcomes based on goals analysis was figuring out how to create the goal ranges for the COUNTIFS function. I knew that the goal of this function was only to include the range of the goals given in column A. At first, I used greater than symbol and the highest value in column A. When I did that, I was getting all of the goal inputs from 0 to my max number. This was solved by including both ends of the goal range in column A within the COUNTIFS statement in excel. 
*For example, for the range of 1,000 to 4,999, I included both >=1,000 and <=4,999 in the COUNTIFS function.
*By adding this into the function it knew where to start pulling in data from the goals column and where to stop pulling in data from the goal’s column. To double check this work I compared the sum of the columns for the outcomes based on goals chart to the sum of the outputs in for plays in the Kickstarter column. The two sums matched indicating all of the data was included within the outcomes based on goals chart.
## **Results** 
### Conclusions on Theater Outcomes on Launch Date
* In general, summer is when Theaters have been most successful. Between April and August there are more than 60 successful Theater productions. The month that launched the most successful Kickstarter campaigns is May. 
*In terms of failed Theater productions, the average amount of failures per month was relatively consistent. However, in months where there were more Theater productions there was a slight uptick in failures. 
*Theater productions that are canceled are very low. 
### Conclusion on Outcomes Based on Goals
*In the graph we see that the highest cost of a goal is related to the highest percentage of plays failing. *The lower the cost of the goal the higher percentage of being successful. The exception to that is the range of 35,000 to 44,999, that range had the second highest percentage of successful plays.  
*No plays were canceled.
### Limitations and Recommendations for Additional Tables or Graphs 
#### Limitations
*A general limitation of the data set is that it could be incomplete and not account for every single play or theater production that came out in the past couple of years. 
*Digging deeper into the data we used for this analysis, we are using a smaller portion of the overall data to look at trends. By cutting out other factors such as the amount pledged, number of backers, outcome end date, we could be missing other factors that relate to our trends. 
*Additionally, the data set is global and could potentially be pulling in irrelevant information that wouldn’t apply to Louise’s play. A solution of this could be to simplify the pull to just the U.K. and U.S. knowing those are similar markets. 
#### Recommendations for Additional Tables or Graphs
*An additional graph that we could use in this analysis would be a box and whisker graph. This graph would allow us to look for any outliers that may be skewing the data. Additionally, it allows us to see the median and mode for the data sets. 
 
_
