# Overview
### Project by: Oluwademilade Oyebanji
This analysis provides insights into traffic trends, financial results and their correlation with stock market performance. 

The notebook is formatted for use on [Google Colab](https://colab.research.google.com/)
# Comparing The Data Periods

__________________________________________________________________________________________________________
The **'Monthly Traffic Score'** is the calculated difference between the average monthly median traffic (all-time) and the median traffic for month in question. The Monthly Traffic Score for May 2020 is **-2.66** which means it typically had higher traffic than is expected for most months.

The **'2020 Monthly Traffic Score'** gives more insight. This is a comparison of the average monthly median for the year 2020 and the average median for may. May has a 2020 Monthly Traffic Score of **-1.56** which means it was better than other months that year in terms of traffic.

What these scores tell us, is that the company has seen a rise in traffic over the lifespan of the dataset (it's harder for high traffic compete in 2020 than it has been to compete historically), and that May 2020 (even in comparison to a stronger year) was better still in terms of Traffic.

So we can say for sure that the search results increased in May when the financial results were released.

# Reading The Heatmap Data

To answer the question requires us to answer two prerequisite questions. How do we define "concentrated" and how do we define "just a few hours". We can see that all days have a pretty even distribution of traffic at around the same times. All 7 days hit their peak traffic for about 4-6 hours out of the 24 available. Dropping to almost 0 traffic for 5-6 hours at around the same time daily (assumed to be between 10 PM and 3-5 AM when people mostly go tobed ).

So with about 6 hours of high activity and 6 hours of low activity, that leaves about 12 hours daily for what can be considered, median, medium or average or activity.


# Analyzing The Time Series


We can notice a few trends in the datasets. In the **close** dataset, we see the spike in closing price in may (when financial earning were announced) and we also see the corresponding spike in **search traffic** in that period. Which can be used to buttress the narrative of the rebounding market strength towards the second half of 2020. Another consistency we find is the lack of data around **March of 2020** (when lockdowns first hit their peak and companies struggled to maintain their workflow), this was also consistent between the close and Search Trend datasets.

However when we look closer there are certain discrepancies that make me wary to say the statement is 100% accurate. While **closing prices** certainly rose after april in 2020, the average **peak search volume** was actually lower than the first quarter of the year (except for the peak in May when earnings were announced). This suggests that the acquisition pipeline for new customers (based on search trends) hadnt made a consistent recovery with the closing price.

All in all the narrative is correct but not accurate to the data


# Correlation Analysis

As search trends increase, the stock volatility correlation shows that statistically it should decrease but the correlation of -0.14 is so week that it would generally be ignored unless from a massive dataset.

Hourly Stock Returns typically correlate positively with an increase in lagges search trends, but the correlation of 0.017 is so weak it would likely also be ignored.


# Most Traffic (time)
The heatmap already showed us that 11 Pm to midnight is the most popular time

# Most Traffic (Day)
The Grouped Bar Graph already showed us that Tuesday has the greatest traffic. (Assuming 0 is Monday)

# Time Period For Concern (Annual)

October 15-19 Every Year
