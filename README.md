# Kickstarting with Excel

## Overview of Project
Louise used crowdfunding data to launch a campaign to raise 10000 for her play Fever. 
Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose

Analyze trends  based on launch dates and funding goals to give Louise more insights about the data that can be used for future projects.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_launch](https://user-images.githubusercontent.com/102937320/162600229-1e854514-0660-44a1-baa5-5bf02ecf98d5.png)

* Total Numbers of projects launched were higher between May-July, with signicant higher number of successful campaigns in May-Jun. 
* At the beggining and end of the year there were lower number of projects launched with lower successful campaign ratio compared to total projects 
* There is no significant correlation between failed initiatives and Launch date. 


### Analysis of Outcomes Based on Goals


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/102937320/162600238-c1a91eef-afc7-4900-ac77-f25b7f3c266f.png)

From this graph we could interpret the following:

* Campaigns with goals less than 1000 and 1000-4999 were succesful ~75% of the time, followed by campaigns in the 35000-44999 ranges with 67% of success. 

Taking a look at the data in Table below, we can better interpret the results. 

| Goal        | Total Projects |
|-------------|----------------|
| < 1000      | 186            |
| 1000-4999   | 534            |
| 5000-9999   | 169            |
| 10000-14999 | 72             |
| 15000-19999 | 24             |
| 20000-24999 | 20             |
| 25000-29999 | 5              |
| 30000-34999 | 11             |
| 35000-39999 | 6              |
| 40000-44999 | 3              |
| 45000-49999 | 1              |
| > 50000     | 16             |

* Majority of projects (~70%) had goals <5000
* Louise campaign with a  goal of 10.000 had a 50% chance of being succesful based on the goal data.

### Challenges and Difficulties Encountered

-Excel had difficulties handling the file, froze a couple of times. 

>>Some of the challenges that could be experienced:
- Double counting data on formulas 
- Not setting correct statements, not locking cells 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. There is a correlation on succesful campaigns and launch date indicating that around May-Jun there are higher chances of success. 
  2. There is no correlation between failed campaigns and launch date

- What can you conclude about the Outcomes based on Goals?
  
  1. Majority of Campaigns had goals between 1000-4999 and campaigns with goals < 5000 were the most succesful with a 75% rate. 
  2. Higher goals in general will reduce the success rate of the campaigns, except for a few exceptions that could be looked in detail.

- What are some limitations of this dataset?  
  1. There are come inconsistencies in data entry for goal- ( not standardized) -  as some are per person/donation and others are total. Which could impact   analysis 
  2. Data is from 2009-2017 might not reflect current behavior 

- What are some other possible tables and/or graphs that we could create?
  1. US Specific Trends 
  2. Lenght of campaign vs Pledged.
    



## Initial Analysis- From Module 1




![ParentCategories](https://user-images.githubusercontent.com/102937320/162594175-5971f464-bb83-4ddb-9413-de5f3c69edcc.png)

* Theater category for crowdfunding is the most popular category and shows a higher number of successful campaigns. 

![US_Categories](https://user-images.githubusercontent.com/102937320/162594174-6d96d00a-2aa3-47cf-b929-559744dec061.jpg)


* Looking at the US specifically, we can also see Theater is the most common crowdfunding category with a 57% sucess rate vs total projects
* Need to look at more specifics to set the campaign for Fever for sucess 

* There is a significant correlation of succesful  campaigns vs launch date and it follows the trend when looking at theater. This play will potentially benefit if launched between May and June. 


* For Louise Interest on GB Market
1. Based on data for musicals we can see that half of the goals were less than 2000 and amounts pledged averaged ~1000. Furthermore we can see that 4000 is on the outlier range of amount pledged so the recommendation for Lousie is to try to produce for less than 4000.

![GB Box and Whiskers](https://user-images.githubusercontent.com/102937320/162594147-92c7dda5-b609-4d3d-90ea-e5f06f6fabb5.png)
