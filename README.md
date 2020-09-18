# An analysis of Kickstarter Campaigns
## *Performing analysis on Kickstarter data to uncover trends and generate insights for better understanding of different campaigns in relation to their launch dates and funding goals.*
---
### **How can your fund-raising campaign be successful? Does the launch date and funding goal play an importante role in the success of a campaign?**
---
## Theater Outcomes vs Launch Date
To help you answer these questions and be able to plan your crowdfunding I worked with Kickstarter Campigns data, specifically wanted to show the relation with the launch dates ann funding goals. To be able to do this, I created a pivot table that allowed me to filter the data based on the outcome, launch date and to make it easier, I also filtered to only retrieve data from the "theater" category. Instead of showing a full date, I wanted to focus on the months where the campaigns started. See the chart below to see results:
---
<img width="708" alt="Theater_Outcomer_vs_Launch" src="https://user-images.githubusercontent.com/70611325/93641509-3a3faa80-f9b1-11ea-8424-8a164da2ff34.png">
---
*** Chart 1.** Line chart of the outcome based on Launched Date. By looking at the chart we can notice that campaigns started in the month of May have a greater success rate. Unlike the last quarter of the year, where we can see that there is a drecrease on the success rate, especially in the month of December.*
---
## Outcomes vs Goals Amount
You will want to know if the success of your campign will depend on the actual funding goal, to review this I created a new table with goal amounts ranges of $4,999.00, starting from less than a $1000.00 to more than $50,0000.00 being the last of dollar-amount ranges, this way I grouped campaigns based on their goal amount. I wanted to look into the number of successful campaigns, failed campaigns and canceles campaigns, and to make it por specific, I ony count the subcategory of "plays". Once I had the numbers and add them up to obtain the number of total projects per dollar-amount ranges, and calculated the percentage of successful, failed, and canceled campaigns. See the chat below to visualize the relationship between the goal amount ranges and the percentage of each outcome:
---
<img width="648" alt="Outcomes vs Goals" src="https://user-images.githubusercontent.com/70611325/93643017-fa2df700-f9b3-11ea-952e-017afdfb6c88.png">
---
*** Chart 2.** Line chart of the outcome based on goal amount. By looking at the chat we can notice that when the goal amount increases, campaigns often fail.*
---
One of the challenges I encountered working with this large data set, is that I tend to forgot what columns I had filtered and resulted in different data than the one I was looking for. Once I got it, personally I found it easier to clear the filerts once I am done using that specific filter. 
---
## Results:
Based on the Theater Outcomes vs Launch Date analysis, I can conclude that:
- The most recommended months to start a fundraising campaign is in May or June. 
- The highest failed rate have been in the month of October, and from there the last two months of the year have the lowest success rate.
Based on Outcomes vs Goals Amount I conlude that the campaigns with much higher goal amount are the ones that failed the most.
What are some limitations of this dataset?
- Some date on the blurb/description column is not readable.
- The date from the Launched Dates and Deadline dates are presented Unix timestamps.
- There are some extreme outliers.
What are some other possible tables and/or graphs that we could create?
- We could study and create a line chart to see if the amount pledge depends on the number of backers.

