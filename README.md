# Kickstarting with Excel

## Overview: 

Analyzing kickstarter data to find trends for successful and failed campaigns to help a playwriter understand her chances

### Background

The data used in this analysis is pulled from a crowd funding website, showing details about campaigns for different projects from 2009 to 2017 

### Purpose: 

The Purpose of this analysis is to find the trends of Kickstarter plays campaigns relating to the campaign launching month and the campaign financial goal

## Analysis and Challenges

### Analysis of Outcomes based on Launch Date

This analysis studies the success or failure rate of a campaign based on the month it was launched, analyzing campaigns that were launched from the year 2009 till the year 2017.

This analysis only focuses on campaigns under the category Theater, studying a total of 1369 campaigns. 

<img width="317" alt="table 1" src="https://user-images.githubusercontent.com/79733383/110227021-ecb4ec80-7ec1-11eb-9b9e-081a1b603a9b.PNG">


As shown in the above table, the data shows that the maximum number of campaigns was launched in May, whereas the minimum nubmer launched was in December. It also shows that the number of campaigns launched is generally more in hotter months than in cooler months, with the exception of October, which is relatively higher than other cold months.

The Output chart shows the number of campaigns that were successful, failed or were canceled in each launching month. 

[Outcome based on Launching months Chart] (https://github.com/Lamismn/Kickstarter-analysis/blob/main/Resources/Theater_Outcome_vs_Launch.png)

### Analysis of Outcomes Based on Goals

This part of the analysis studies the success or failure of the campaigns based on the financial goal they are requesting, over the same period from 2009 till 2017.

This analysis focuses only on campaigns under the category Theater & the subcategory plays to give a more relavent view of similar projects, studying a total of 1047 projects


<img width="701" alt="table 2" src="https://user-images.githubusercontent.com/79733383/110227017-dc047680-7ec1-11eb-8ee4-289a683226c9.PNG">

As Shown in the above table,  the highest number of projects had their goals between $1000 and $5000, whereas the smallest number had was that of projects between $45000 and $50000

The analysis also shows that no campaigns for plays were canceled within our datset

The output chart of this analysis shows the percentage of success and failure based on the goal, goal values are divided in intervals starting from less than $1000, between $1000 and $4999, and then equal intervals of $5000 increments till $50000, and then above $50000.

[Outcome vs goals chart] (https://github.com/Lamismn/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

One of the challlenges that is not considered in this analysis is the currency exchange rate, the dataset does not consider it which means that the goal & pledged values do not give an accurate representation of the actual data points. Had we decided to rectify this, unifying the currency would have proved to be a challenge, especially with the long duration of the data points, as currency rates change daily.

## Results

Based on the Analysis conducted, we can conclude the following results:

### Outcomes based on Launch date

We can conclude from the chart that the month of May has the highest probability of success for campaigns, as well as the highest number of campaigns launched, followed by the months of June then July. This means that launching the campaign in May would be the best option.

The Chart also shows that the month of December has the lowest success rate for campaigns as well as the lowest number of campaigns launched, so it is advised to avoid launching a campaign during this month

We can also conclude that launching a campaign in a hotter weather month gives it a better chance of success than launching it in a cooler month.

### Outcomes based on Goals

We can conclude from the chart that plays with goals less than $5000 have the highest probability of success & that plays with goals above $45000 have the lowest probability of success. This means that it is advised to try and keep the required goals below $5000 to increase the chances of the campaign's success.

The chart also shows that the plays with goals between $35000 and $45000 do not follow the general pattern of decreasing probability of success as the goal increases.

### Limitations of the dataset

One of the limitations of the dataset is that the analysis based on goals only considers the percentage of successful & failed campaigns without considering the total number. This shows a problem in intervals like the goals between $35000 and $45000 where the total number of projects is 9 but the probability of success is 66.7%.

Also there is the limitation that the data used for this analysis is extracted off of only one crowd funding website, which does not give a complete picture of crowd funding campaigns in general. This website may be more active in some countries than in others or during some periods than others, for example, in year 2017, the total number of theater campaigns significantly drops (31 in 2017 vs 391 in 2016). This drop may for example be caused by some technical problems in the website, or by any other cause, but it does affect the integrity of our data.

Another limitation is the variation in the funding goal currency, which is not considered in the analysis, the currency exchange rates may affect the ultimate value of the campaign & change its positioning from one interval to another, thus affecting the chart outcomes

### Suggestions for possible tables and graphs

An additional bar graph analyzing data by the length of the campaign to show the success rate related to the campaign length

An additional line chart showing the average donation per backer vs the total goal, to show if the average tends to increase for campaigns with a higher goal.

An additional chart for failed campaigns analyzing the goal & the pledged amounts relating to the launch month  









