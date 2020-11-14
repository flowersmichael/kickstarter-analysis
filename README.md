# Kickstarting with Excel

## Overview of Project

Our client is interested in launching a Kickstarter campaign to fund a theater production. In this analysis we reviewed Kickstarter campaign data to determine what factors might contribute to whether or not a campaign succeeds or fails. 

We zeroed in on two specific factors:

*Launch Date: What time of year the campaign is launched?

*Goals: What's the targeted amount of money being raised in the campaign?


### Purpose

The purpose of this analysis is to help our client make informed decisions and increase the probability that her campaign will be successful.


## Analysis and Challenges

For our analysis we looked closely at outcomes based on Launch Date, and outcomes based on Goals. For both Launch Date and Goals, we grouped campaigns by their outcomes: successful, failed, canceled, or live (ongoing).

For Launch Date, we included all campaigns in the Theater Parent Category. Such campaigns included Plays, Musicals, and Spaces.

For Goals, we looked specifically at Plays.

We filtered out all live campaigns for our analysis since the outcome of these campaigns is unknown at this point.

Our data set includes campaigns from over 20 countries for the years 2009 through 2017. These characteristics of the data set highlight some limitations of our analysis. For one thing, our client's play is targeted for release in the United States, and these data include all countries. We could limit our analysis to US data but that would decrease the sample size. Also, it's now 2020 and our data only goes through 2017, so the data is somewhat stale.

Most importantly, the onset of COVID-19 is likely the greatest determinant regarding the success or failure of campaigns such as theater plays that involve crowd gatherings. It's best to consider this analysis as a helpful resource for when the pandemic subsides and life in the U.S. returns to normal.


### Analysis of Outcomes Based on Launch Date
Looking at the chart below, it's clear that most successful campaigns are launched in the early summer months of May, June, and July. More theater plays are launched in these three months than any other months, with a key takeaway being that the success:failure ratio is highest during these months.

Theater campaigns launched in May and June in particular are not only the most successful in terms of total campaigns, but also in terms of success:failure.

We can generally ignore the canceled plays with respect to launch date because the number of plays canceled is very small and also steady over the course of the year.

![Outcomes Based on Launch Date](https://github.com/flowersmichael/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals

Looking at the outcomes based on the amount of the fundraising goal, we can draw several conclusions.

First, ~69% of all campaigns have a fundraising goal of less than $5,000, and these campaigns are successful roughly three-quarters of the time.

Second, it's probably most helpful to look only at campaigns with fundraising goals less than $25,000. The number of campaigns with fundraising goals of $25,000 and above is very small, roughly 3.5% of all thater play campaigns. Additionally, our client is looking to raise around $12,000 for her play, so outcomes with goals in that ballpark are likely most informative.

The high-dollar goal campaigns should possibly be viewed as outliers, or special situations. There are few enough of them to warrant closer inspection regarding their success or failure.

Third, our client may want to consider reducing her fundraising goal to something closer to $5,000. We observe that nearly 75% of campaigns in this goal range are successful. In contrast, the campaigns that effort to raise between $5k-$25k have roughly a 50/50 chance of meeting their goal.

![Outcomes Based on Fundraising Goals](https://github.com/flowersmichael/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Challenges and Difficulties Encountered



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May and June look loke the best months to launch a theater project.
2. December is the worst month to launch a theater project.

- What can you conclude about the Outcomes based on Goals?
1. Plays with a fundraising goal of less than $5k are successful nearly 75% of the time.
2. Plays with a fundraising goal between $5k and $25k are successful about half of the time.
3. We don't have much data on plays with fundraising goals higher than $25,000.


- What are some limitations of this dataset?
1. This dataset does not include any data after 2017. It would be helpful to have 2018 and 2019 data.
2. This dataset is not helpful for decisions regarding campaigns in 2020, and possibly 2021 as well. The COVID-19 pandemic dramatically impacts the success or failure of theater play campaigns since most plays involve live crowd gatherings. Analysis of this dataset might be irrelevant for theater productions involving virtual audiences.
3. We don't have information about who is launching the campaign. Their profile and level of experience might be a major driver in the success of the campaign.


- What are some other possible tables and/or graphs that we could create?

