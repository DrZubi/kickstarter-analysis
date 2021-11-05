# Kickstarting with Excel
### Submission Created By Omar Zu'bi

## Overview of Project

### Purpose

The goal of this challenge assignment is to infer insightful statistical analysis and visualization to help Louise discover how different kickstarter campaigns fared in relation to their launch dates and funding goals. Louise hopes that by doing so, information can be gathered that could potentially be useful to assit her with creating a successful kickstarter campaign. 

### Whats included in this repository

Items found in the repository:
1) Resource folder containing two .png files (Outcomes_vs_Goals.png and Theater_Outcomes_vs_Launch.png)
2) Kickstarter_Challenge.xlsx.zip file
3) README.md

## Analysis and Challenges

### Deliverables included in report

Three deliverables were created to help Louise's search for how different kickstarter campaigns fared in relation to their launch dates and their funding goals: 
1) Outcomes Based on Launch Date [Chart](!https://github.com/DrZubi/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
2) Outcomes Based on Goals [Chart](!https://github.com/DrZubi/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png) 
3) This analysis report

### Analysis of Outcomes Based on Launch Date

A Pivot table was created that displayed the outcomes of the kickstarter projects with their launch dates, filtered by their years and parent category. As seen in figure 1, May is the most sucessful month in which kickstarter projects are most sucessfull (66% sucess rate), closley followed by June.  

![Figure1](https://github.com/DrZubi/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
*Figure 1: Outcomes Based on Launch Date Chart*

The legend of figure 1 displays three categories: the count succeeded, failed, and canceled. One major piece of information that one should keep in mind regarding figure 1 is that the chart only displays the kickstarter projects under the theater parent category. This may lead to some wrong interpretations since we are only interested in the subcateogry of plays (this is further discussed in the next section). 



### Analysis of Outcomes Based on Goals
![Figure2](https://github.com/DrZubi/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
*Figure 2: Outcomes Based on Goal Chart*

The legend of figure 2 displays three categories: percentage successful, percentage failed, and percentage canceled. There are two pieces of information that one should keep in mind regarding figure 2. For one, this chart only displays percentages of the outcomes for kickstarter campaigns that are plays. Second, the chart has no indication of the number of campaigns that were in each goal range. Without these pieces of information, one may assume incorrect conclusions.  
For example, let's take a closer look at the kickstarter campaigns with a goal between 45000 to 49999. According to figure 2, kickstarter campaigns with the goal between 45000 to 49000 were all doomed to fail with a 0% success rate and a 100% fail rate. This however, would need to be further investigated as an outlier; if we were to take a closer look at the kickstarter data table set, one would notice that there is only one kickstarter campaign that fits within that goal range, and failed!

One may notice at a glance that the percentage of canceled projects were 0% for all goal ranges. This is due to the fact that there were no canceled kickstarter plays! There are three points on figure 2 where the percentages of successful kickstarter projects and failed kickstarter projects intersected. 

### Challenges and Difficulties Encountered
For the first weekly challenge, I did not encouter difficulties creating the pivot tables and charts. I would say that it was a bit challenging trying to work on a Macbook (I typically use a Windows operating system when working with excel). I would argue, however, that difficulties and challanges would arise when trying to make insightful statistical inferences for Louise's kickstarter project from the required deliverables; the charts and pivot tables can easily misrepresent data and lead to incorrect conclusions. This is further discussed in the next section. 

## Results

Responses to challange questions:

1) What are two conclusions you can draw about the Outcomes based on Launch Date?
	1) Kickstarter projects launched around the month of May had the highest success rate. I would highly suggest Louise to launch her kickstarter project on the month of May.
	2) Kickstart projects launched around the month of December are likely to have a 1:2 chance of failing or succeeding. I would suggest to Louise to avoid launching her Kickstarter project during this month. 


2) What can you conclude about the Outcomes based on Goals?
	1) Kickstarter projects with higher goals were less successful than projects with lower goals. We can see that projects, on average, 
	2) Kickstarter projects less than 1000 were most successful whereas kickstarter projects greater than 45000 were least successful 


3) What are some limitations of this dataset?

	There are some limitations about the kickstarter dataset given to extrapolate information. One major limitation that comes quick into mind is that the dataset does not refer to how often the campaigns were updated by their original owners; maybe some owners kept giving weekly feedback to their backers whereas others may not had the time to do so.
	There are also some limitations with the pivot tables created for analysis. For the first analysis, the pivot table was filtered to show the parent category 'theater' and their outcomes. This parent category includes plays, musical, and spaces; imformation about two of these categories may not be important for Louise's kickstarter project. In turn, this may lead to some misrepresentation of data that can lead to inaccurate inferences when reading the chart; the month of May may not neccesairly be the month that play kickstarter projects are most successfull. Further filteration of the data must be applied to help resolve this issue
	In the second analysis, as mentioned before, the chart has no indication of the number of campaigns that were in each goal range. Without these pieces of information, one may assume incorrect conclusions; it is not necessairly clear that higher kickstarter goals are less sucessfull than lower ones since there are so few of them to really make proper inferences for. 



4) What are some other possible tables and/or graphs that we could create?

As mentioned above, other possible tables and graphs that I would include to help make better statistical inferences are the following:
1) Another pivot table filtered by the parent category plays and years
2) I would also suggest showing the averages for the charts created to help readers understand where the averages of successful and uncesssful projcets fall. 
3) Possibly make use of a pie chart to show statistical percentages of the number of plays that were sucessful and failed that could be filtered into diffrent important categories; i.e months, years, countries, etc. 







