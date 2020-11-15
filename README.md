# Kickstarting with Excel

## Overview of Project
Our client is interested in launching a Kickstarter campaign to fund a theater production. In this analysis we reviewed Kickstarter campaign data to determine what factors might contribute to a campaign's success or failure. 

We zeroed in on two specific factors:

*Launch Date: What time of year the campaign is launched?

*Goals: What's the campaign's target financial goal?


### Purpose
The purpose of this analysis is to help our client make an informed decision and increase the probability that her campaign will be successful.


## Analysis and Challenges
For our analysis we looked closely at outcomes based on Launch Date, and outcomes based on fundraising Goals. For both Launch Date and Goals, we grouped campaigns by their outcomes: successful, failed, canceled, or live (ongoing).

For Launch Date, we included all campaigns in the Theater parent category. Such campaigns included Plays, Musicals, and Spaces (typically actual theater construction projects).

For Goals, we looked specifically at the Plays subcategory.

We filtered out all live campaigns for our analysis since the outcome of these campaigns is unknown at this point.

Our dataset includes campaigns from over 20 countries for the years 2009 through 2017. These characteristics of the dataset highlight some limitations of our analysis. For one thing, our client's play is targeted for release in the United States, and these data include all countries. We could limit our analysis to US data but that would decrease the sample size. Also, it's now 2020 and our data only goes through 2017, so the data is somewhat stale.

Most importantly, the onset of COVID-19 is likely the greatest determinant regarding the success or failure of campaigns that involve crowd gatherings, such as theater plays. It's best to consider this analysis as a helpful resource for when the pandemic subsides and life in the U.S. returns to normal.


### Analysis of Outcomes Based on Launch Date
Looking at the chart below, it's clear that the early summer months of May and June (and July to a lesser extent) offer the highest chance of success for theater campaigns.

More theater campaigns are launched in these three months than any of the other months, with key takeaways being that not only do May and June have the highest absolute number of successful theater campaigns, but the success:failure ratio is also highest during May and June.

*(We can generally ignore the canceled theater campaigns with respect to launch date because the number canceled is very small and also quite steady over the course of the year.)*

![Outcomes Based on Fundraising Goals](https://github.com/flowersmichael/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
Looking at the outcomes based on the amount of the fundraising goal, we can make several observations.

1. First, ~69% of all campaigns have a fundraising goal of less than $5,000, and these campaigns are successful roughly three-quarters of the time.

2. Second, it's probably most helpful to look only at campaigns with fundraising goals less than $25,000. 

The number of campaigns with fundraising goals of $25,000 and above is very small, roughly 3.5% of all thater play campaigns. The high-dollar goal campaigns should possibly be viewed as outliers, or special situations.

Additionally, our client is looking to raise around $12,000 for her play, so outcomes with goals in that ballpark are likely most informative.

3. Third, our client may want to consider reducing her fundraising goal to something closer to $5,000. 

We observe that nearly 75% of campaigns in the <$5k range are successful. In contrast, campaigners trying to raise between $5k-$25k have roughly a 50/50 chance of meeting their goal.

![Outcomes Based on Launch Date](https://github.com/flowersmichael/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
One of the challenges I previously highlighted was that the data are somewhat stale, only through 2017. It would be helpful to have the 2018 and 2019 data to have more data points as well as more recent data.

Another challenge is the unique state of the world in 2020. The COVID-19 pandemic has had a major impact globally in ways, including how we spend our time and how we spend our money. All events involving crowd gatherings have been dramatically affected by the pandemic, including movies, concerts, and plays. It would presumably be much more difficult to raise money for a play while the duration of the pandemic's impact on crowd gatherings is unknown.


## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**

1. May and June look like the best months to launch a theater project.

2. December is the worst month to launch a theater project.


**What can you conclude about the Outcomes based on Goals?**

1. Plays with a fundraising goal of less than $5k are successful nearly 75% of the time.

2. Plays with a fundraising goal between $5k and $25k are successful about half of the time.

3. We don't have much data on plays with fundraising goals higher than $25,000.


**What are some limitations of this dataset?**

1. This dataset does not include any data after 2017. It would be helpful to have 2018 and 2019 data.

2. This dataset is not helpful for decisions regarding campaigns in 2020, and possibly 2021 as well. The COVID-19 pandemic dramatically impacts the success or failure of theater play campaigns since most plays involve live crowd gatherings. Analysis of this dataset might be irrelevant for theater productions involving virtual audiences.

3. We don't have information about who is launching the campaign. Their profile and level of experience might be a major driver in the success of the campaign.

4. It might be helpful to have information about the genre of each Theater Play campaign. Perhaps comedies have different success:failure ratios compared to dramas, for example.


**What are some other possible tables and/or graphs that we could create?**

1. It would be helpful to look at a table/chart of the Outcomes based on Launch Date that's limited to Theater Plays. Perhaps it would be very similar to the chart that includes all theater projects, but it could be different in meaningful ways that might change the advice we'd give to the client.

2. We could also include Musicals with Plays in our analysis. If we'd like to have a larger sample size than just Plays, Musicals are fairly similar. Theater Space crowdfunding efforts, typically larger construction projects with high-dollar fundraising goals, are very different from Musicals and Plays.

3. Since our client is based in the US and wants the play to Limiting the analysis to US data might also provide different insights from the global dataset we used to analyze the Outcomes based on Launch Date and Goals.

4. There is also a field that identifies whether or not a campaign is a Kickstarter Staff Pick. It would be interesting to see if the success:failure ratio for Staff Pick Plays is meaningfully different from non-Staff Picks. If there's a significantly higher success ratio for Staff Picks, it might be worth investigating whether or not there is a process for helping improve your campaigns chances of being a Staff Pick.
