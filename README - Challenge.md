# Kickstarting with Excel

## Overview of Project

Using a Kickstart dataset a analysis was made to know the relationship of different campaigns between its funding goals and launching dates. 

This analysis was made applying a simple `COUNTIF` formula and only two but insightful data charts:

 - Outcomes Based on Launch Date Chart
 - Outcomes Based on Goals Chart
 
 These two charts will be explanied respectively in the below *Analysis and Challange* section.

### Purpose

We wanted to gain an accurate and deep understanding of the relationship of different campaigns between its funding goals and launching dates.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By inserting a pivot table and filtering by 'Theather' as Parent Category, we were able to make a chart that represents the *Outcomes based on a Launching date.* With this visualization, we identified if there was a month in which there were more successful campaign launches and in which month were more failed campaign launches.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/78564912/133183458-9e1f4cd0-4fca-4435-a1b9-37962660da2f.png)


### Analysis of Outcomes Based on Goals

Applying a simple `COUNTIF` formula, we could get the *Outcomes based on Goal*. Within a USD scale ranging from $0 to greater than $50,000 we are able to identify at which range/level there were more porcentage of successful and failed campaigns, but also the relationship between these two. It would seem that not because a campaign raised/pledged more money, is going to be necessarily a success.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/78564912/133183390-e47b44eb-da95-4448-9e14-1afb92f02bfe.png)

![table](https://user-images.githubusercontent.com/78564912/133183436-b86d5931-eee1-456d-830d-b94961c67ba0.png)


### Challenges and Difficulties Encountered

1) At the beginning I was making a mistake, by not fixing cell references in the table.

2)  I was having a hard time tracking another error, because besides *successful* and *failed* outcomes I was taking into account *live* outcome as well from the dataset.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    1) From this Kickstart dataset from 2009-2017, the peak of successful campaings for the parent Category *Theater* is in May, with around 110 campaigns and the lowest point of the successful campaigns is at the end of the Year in December with ~ 40 campaigns.

    2) At this same point (~ 40 campaigns), the amount of failed campaings converge with the lowest point of the successful ones. As per this dataset, it would seem that the best month to launch a campaign is in May.

- What can you conclude about the Outcomes based on Goals?
    
    Even though it would seem that the greater the amount of the Goal, the lower Number of Successful campaigns. When we measure in percentage, we would conclude that this is not completely true, with the exception of the last two ranges from '45,000 to 49,999' and '> 50,000'.
    
    In fact, analyzing the graph we cannot conclude any trend, since it has a 'erratic' (ups and downs) across the different goal amounts.
    
    So, not because a campaign raised/pledged more money, is going to be necessarily a success and visceversa, which leaves room to think that there should be other variables that are not being considered.

- What are some limitations of this dataset?

    I would say that, even though we have very rich quantitative data, the qualitative data is missing. For example, the reason of why a campaign leads to be a success or a failure.
    
    We would need un updated dataset, since it dates since 2009 (+10 years ago) and the preferences changes across decades.
    
    
- What are some other possible tables and/or graphs that we could create?

    Charting the relationship between the number backers and the % funded amount, would interesting to study how these two variables behave and answer the question: If you have more backers, is it more likely to reach have a successful campaign?
    
    If more time elapsed between the Date Created and the Date End of the campaign, are you able to get a successful outcome? I think this data would let us know, also how well received is the campaign among the backers, the shorter time, the more interest they have on it.
    
    
