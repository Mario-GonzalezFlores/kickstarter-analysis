# Kickstarting with Excel

## Launch dates and Goals analysis

### To determine the best time to launch a kickstarter campaign for a play and identify the optimal funding range.

## First, we must make sure that all the necessary data is available in the format required for our analysis. To analyze by date it's important to create the "Year" column to provide the date for our pivot tables

![Column](https://user-images.githubusercontent.com/89816213/133293388-d05e8fcf-3010-4ead-8cfc-fa952244aa69.PNG)


## Then, when we create our pivot table, we must be aware that the date might be compressed, so we have to remove the "groups" from our table

![Remove-groups](https://user-images.githubusercontent.com/89816213/133293832-68368b21-8c44-4545-a250-b04d92150b90.PNG)

## Once we have the right parameters and create the timeline (graph) it's noticeable that most plays kisckstarters are succesful, but there are important differences in the success rate ameng the year, as well as peaks of both failed and successful, which change the correlation and seem to piont a clear period in which the project has better success chances.

## When we get to use the "countifs" formula for the analysis based on outcomes and goals we have to be careful of using the correct ranges and correctly determine the parameters to condition the formula. I struggled with the quotation marks for the range of the goal:

![Formula](https://user-images.githubusercontent.com/89816213/133294600-313d3f51-dd98-47ff-961c-782273ba9574.PNG)

## When we create the chart we can see that there seem to be ranges that alternate in which success and failure rates drop or rise drastically, giving us important information to consider for our analysis.


### Analysis of Outcomes Based on Launch Date

### ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89816213/133297794-59f8eba1-5a9b-4bd1-9379-8503c675df10.png)

### This graph shows that the best time to start a fundreaiser for a play is in the months between may and july, since this months show a higher number of succesful campaigns. Also we can infere that october and december are the worst months to launch the campaign, since in those months the number of successful and failed campaigns are almost equal.

### Although the months betwween may and july show a peak in successful campaigns, we can also see that these are the months with most campaign launches, while february and april have a similar success rate and much less competition for funds.

### Analysis of Outcomes Based on Goals

### ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89816213/133300030-7141144d-57cf-4c89-8544-2f0b8d52794e.png)

### In this chart we can see that the best success rates are for plays that ask for less than 5,000 dollars and between 35,000 to 44,999; while plays in the range between 15,000 and 34,999 are most likely to fail.

### Analysis of Average donation and number of backers

### ![Avg-donation-backers](https://user-images.githubusercontent.com/89816213/133305157-bda3d44b-18ba-4843-92c2-5f81d247bc88.png)

### This chart shows that number of backers is roughly the same for failed and successful play campaigns, but there is an important gap in the average donation made by such backers, being so that an average donation of around 70 seems to be the necessary to achieve the goal, and if one seeks for high amounts of donation then it's imperative to consider launching the campaign in the months between may and july, which shoy the most donors around the year.
