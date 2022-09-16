# kickstarter-analysis

# Kickstarting with Excel

## Overview of Project

Louise is a play writer and has recently run a crowdfunding campaign in order to raise money for her upcoming play, “Fever”. After coming close to her fundraising goal in a short period of time, Louise is curious how crowdfunding campaigns for other theater performances perform based on their launch dates and funding goals. By analyzing and sorting the data from the kickstarter campaigns provided, we will be able to determine the factors that may influence the success of crowdfunding campaigns. Using this information, Louise will be able to make an informed decision on how to run her kickstarter campaign based on previous campaigns launch dates and funding goals.


## Analysis and Challenges




### Analysis of Outcomes Based on Launch Date

Using a pivot table filtered by theater productions only with successes, failures, and canceled kickstarters sorted by launch date, we are able to create the graph below and begin to draw conclusions regarding the most and least effective months to begin a crowdfunding campaign for a theater production. 

Based on the data provided in the line graph below, we can conclude that there is an upwards trend in the number of successful campaigns that are launched from May to June, with a sharp decline in successful campaigns in the months following. December had a notably low number of successful campaigns comparatively, with almost ⅓ of the success rate of those launched in May. Some challenges that Louise may face with future campaigns could be equated to suboptimal launch dates, with data showing that late spring - early summer have largely more successful campaigns. 

### Analysis of Outcomes Based on Goals

By creating a table populated by the number of successful, the number of failed, and the number of canceled crowdfunding campaigns specifically for plays, we were able to create the linegraph displayed below. This table allowed us to calculate the percentage of successful and failed projects based on their target goal. The line graph that we created allows us to determine that kickstarter campaigns for plays were most successful in reaching their goal when the goal was less than $1,000, with 76% of campaigns able to meet their goal. Campaigns with goals higher than $45,000 were 88-100% unsuccessful in reaching their goal. Campaigns that ranged from $5,000 to $15,000 had approximately a 55% chance of reachingtheir goal and 45% chance of failing to reach this goal, making it likely the most efficient campaign goal if the funding was necessary, while campaigns with goals less than $1,000 would be the safest option most of the time. 

### Challenges and Difficulties Encountered

While working with this dataset, I ran into difficulties at several points that prevented me from creating accurate graphs that could easily be analyzed. The largest of these difficulties came from my order of sorting and filtering data while experimenting with making my pivot table, which led to previous graphs displaying incorrect sets of data. For example, I have copied a photo of one of my previous graphs in which I had sorted data by years instead of date created, leading me to interpret data incorrectly and have to return to the kickstarter spreadsheet and make adjustments.

I also encountered difficulty when writing the formulas to calculate the number of successful campaigns in the “Outcomes based on goals” sheet. Originally, I had written, “=COUNTIFS(Kickstarter!$F:$F, "Successful", Kickstarter!$R:$R, Kickstarter!$D:$D, "<1000")” which left out an important “plays” following the “Kickstarter!$R:$R,” which changed my graph significantly from what I was trying to achieve. After some research and discussions with my peers using slack, I was able to identify where I was making my mistake and add the necessary parameter to filter my data by plays only, making my totals and percentages accurate and ultimately making my line graph match the one in the instruction. 

Some challenges or difficulties that Louise may encounter in her campaigns could include lower likelihood of success based on the month that she launched the campaign and what her goal for the campaign would be. For example, if Louise is looking at raising money in the $10,000 to $20,000 range, she will be looking at approximately 55% odds of reaching that goal. It would be my recommendation that she makes a campaign with a lower range of goals, for example the $1,000 to $5,000 range which has a 73% success rate based on previous play campaigns. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Two conclusions that we are able to draw regarding the theater outcomes by launch date are that launching the campaign at the right time is a key factor in the success of the campaign’s ability to succeed and that the length and type of kickstarter campaign could also play an important role in the success of reaching her goal. Campaigns that were launched in the late spring to early summer saw far more success than those that were launched in the winter months. 

- What can you conclude about the Outcomes based on Goals?

A conclusion that can be drawn from the outcomes based on goals would be that having higher funding goals for your campaign drastically reduces the chances that the campaign will be able to meet said goal. Campaigns with goals below $5,000 were approximately 75% successful, with those that were higher dropping significantly. If Louise was to do another campaign to raise money for a play, I would recommend that she sets her goal to be within that $0-$5,000 range at first due to their average success rates. 


- What are some limitations of this dataset?

Some factors that could be considered if another analysis was to take place could be the subgenre of plays and success rates for different genres to meet their campaign goals. Another factor to consider could be the year range of the data set. Taking into account data from campaigns for plays from years prior and from current times could provide us with a larger sample size and more accurate data in regards to current trends in the success of campaigns. Another limitation of this dataset was the inclusion of currently active or “live” campaigns. These campaigns could succeed or fail in the near future, changing the way that the data for goals or months look entirely.

- What are some other possible tables and/or graphs that we could create?

 The use of line graphs to display the success rates for campaigns based on how long they are active could be beneficial when trying to determine what parameters should be set when Louise makes a future campaign. 



