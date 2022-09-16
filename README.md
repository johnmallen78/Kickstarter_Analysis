# Kickstarting with Excel

## Overview of Project
In this project we were charged with analyzing a set of Kickstarter data in order to help our client Louise for a potential crowd funding project.

### Purpose
The purpose of this analysis was to provide actionable data to Louise to start a crowdfunding campaign for her play "Fever". She has provided a budget of over $10,000 and wants to ensure that crowdfunding her play can be as successful as possible.

## Analysis and Challenges
In the data set provided we had more than 4,000 different crowdfunding campaigns across multiple categories. In order to provide the most detailed dataset for Louise we started by creating and filtering to subcategories of plays. 

The first major challenge introduced in this data set is the formatting of the Deadline and Launched dates. These dates were presented in Unix shown below.

![Unix image](/resources/Unix.png)

In order to make them more approachable they were reformatted to standard date format shown below.

![Standard_Date](/resources/Standard_Date.png)

Other challenges included working around outlying datasets that created a rather large gap in some of the comparisons needed.

### Analysis of Outcomes Based on Launch Date
In the graphical chart below, we researched the successful, failed, and canceled campaigns across all years provided in the data set broken out by month.

![Theater Outcomes vs Launch](/resources/Theater_Outcomes_vs_Launch.png)

You can see from this chart that there is a distinct trend toward success for campaigns launched around the middle of the year rather than early or late into the year.

### Analysis of Outcomes Based on Goals
We further analyzed the data provided in order to determine the success rates of campaigns launched with a specific range of goals. As you can see in the chart below, the success rates of campaigns with goals under $5,000 is significantly higher than any other monetary range.

![Outcomes vs Goals](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
The major challenges encountered in this analysis were the Unix dates. There were also some campaigns that had 0  backers so referencing IF statements that could deal with this (especially during creation of the Outcomes Based on Goals table) were necessary. An example of the code used to provide accurate Percentages if the divisor was 0 is  =IF(B2,B2/$E2,"0%").
## Results

We concluded that the best time to launch a campaign would be early May or June. This would provide the highest level of success based on the data provided.

The dataset provided that the highest percentage of success fell between goals less than $1,000 to $5,000. The goals higher than $10,000 had a much lower rate of success.

We should take into consideration that the dataset is limited based on the date ranges only being from 2009-2017. A data set with more up-to-date information would provide an even better picture of the success/failure of these types of campaigns. Another limitation of the dataset is the range of goals achieved. The number of outlying successful campaigns higher than $50,000 creates a very scewed view of the overall dataset.

We could also look into the rate of success based on the country as well as total funding to determine if there is a greater chance of success by targeting specific areas.