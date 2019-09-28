# **Module 1: An Analysis of Kickstarter Campaigns**

To access the first part of the anlaysis we did as we went through the module, please go here: https://github.com/jbtrahin/kickstarter-analysis

### **Challenge 1**

You can download excel spreadhseet here: https://github.com/jbtrahin/Module1-Challenge/raw/master/Module%201%20Challenge.xlsx

#### A) Introduction
In this analysis, we're trying to answer 2 questions:
1. How many other Kickstarter campaigns were able to come close to there goals in a short amount of time?
2. Does the length of the campaign contribute to the success/failure of a campaign?
	
Let's define the different data points further:
  - A _Kickstarter campaign_ can be identified as one row in the spreadsheet with a unique ID and a set of data points.
  - _Coming close to a goal_ means that the Percentage Funded is equal or higher than 90%.
  - _Short amount of time_ means that the Length of the campaign is lower than the 1st quartile of the sample.
  - _Length_ of a campaign is the difference in time between the Date Ended Conversion and the Date Created Conversion.
  - _Success_ means that the Percentage Funded is equal or superior to 100.
  - _Failure means_ that the Percentage Funded is below 100.

#### B) Analysis

#### PART 1: Analyzing Outcomes Based on Goals for Plays Subcategory
On the line graph below, you can visualize the percentage of successful/failed campaigns based on their fundraising goals.
![alt text](https://github.com/jbtrahin/Module1-Challenge/blob/master/Outcomes%20Based%20on%20Goals.png)

**Observations:**
- We observe that 84% of the Plays campaigns have a goal of less than $10,000.
- We observe that 75.81% of the Plays campaigns with a fundraising goal of less than $1,000 are successful.
- We observe that 72.66% of the Plays campaigns with a fundraising goal between $1,000 and $4,999 are successful.
- We observe that the majority of successful campaigns for Plays (76%) have a fundraising goals of $4,999 or below.
- We observe in the dataset that you are more likely to fail (49.5%) if your fundraising goal is $5,000 and above, than if it's below (26.5%). 
- While we observe other high percentages of successful campaigns in higher goal brackets, we have established that the data is skewed and that these numbers are not significant.
- It's interesting to note that there aren't any canceled campaigns in the Plays subcategory.

**Recommendations:**
- Louise should keep her fundraising goal below $4,999 to increase her chances of being successful.


#### PART 2: Analyzing Outcomes Based on Launch Date for Theater Parent Category
On the line graph below, you can visualize the percentage of successful/failed campaigns based on their fundraising goals.
![alt text](https://github.com/jbtrahin/Module1-Challenge/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

**Observations:**
- We observe that May (166) and June (153) are the two months with the most Theater campaigns being launched.
- We observe that Theater campaigns launched in May (111) and June (100) have the highest number of successful outcomes.
- We observe that Theater campaigns launched in May (67%) and June (65%) have the highest percentage of successful outcomes.

**Recommendations:**
- Louise should launch her campaign in May or June to maximize her chances of being successful.


### PART 3: Final recommendations, Limitations and Next Steps

With these two analysis, we can make the following recommendations to Louise:
- Keep your fundraising goal below $4,999 to increase chances to be successful.
- Launch your campaign in May or June to maximize chances to be successful.

However, we're unable to provide a cohesive answer to the two questions asked in the introduction as it would require further analysis to do so, such as:
- Analysis of Outcomes Based on Length of Campaign
- Analysis of Descriptive Statistics (Mean, Median, IQR)
- Analysis of Outcomes Based on Length and Percentage Funded

--------------
#### C) Additional Work

Here we'll be trying to do further analysis and provide Louise with additional recommendations.

#### Analyzing Outcomes Based on Campaign Length
On the line graph below, you can visualize the percentage of successful/failed plays campaigns based on the length of the campaign.
![alt text](https://github.com/jbtrahin/Module1-Challenge/blob/master/Outcomes%20Based%20on%20Length.png)

In the table below, you'll find descriptive statistics about the plays subcategory.
![alt text](https://github.com/jbtrahin/Module1-Challenge/blob/master/Descriptive%20Statistics.png)

**Observations:**
- We observe that more than half (56%) of the plays campaigns last between 21 and 31 days, while the other half is split between 1 and 21 days and 31 days and over.
- We observe that plays campaigns that last between 11 to 21 days have the highest percentage of successful outcomes (79%).
- We observe than 25% of successful plays campaigns have a length of 23 days or lower. This can be considered a short amount of time to reach your goal.
- Based on our data point definition, we've calculated that 179 plays campaigns out of 1066 total plays campaigns (16.7%) were able to come close or achieve their goals (Percentage Funded >= 90%) in a short amount of time (Length <= 23 days). 

**Additional Recommendations:**
- Louise should run her plays Kickstarter campaign between 11 to 21 days to maximize her chances of success. 
