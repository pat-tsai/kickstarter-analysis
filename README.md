# kickstarter-analysis
Analyzing kickstarter data from 2009-2017 to discover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to analyze the outcomes of theater category kickstarters based upon their launch date. A second analysis was also performed on the play subcategory to determine kickstarter outcome based on the pledge goal amount required.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Based on our kickstarter data from 2009-2017, I created a pivot table which revealed a significantly higher success rate for kickstarters in the theater category that began in May. However, this success rate steadily decreased over the next 4 months before reaching around 50% success rate in September. Lastly, December has the lowest theater kickstarter success rate, which could be possibly attributed to busier schedules and tighter spending during holiday seasons. I experienced no major challenges in analyzing this data, but possible challenges include filtering the category to only display theater kickstarters, and grouping the row labels to only display months instead of each individual date.
![ScreenShot](https://raw.githubusercontent.com/pat-tsai/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals
Using the same dataset, I created a table using conditional count statements, adding criteria to filter outcomes and region, and sum the total number of the respective projects. From the table, I generated a line graph displaying the results. Based on the graph, I observed that kickstarters were more likely to be successful if the goal amount was between $1 and $5000, or between $35,000 to $45,000. I also observed a 60% failure rate for kickstarters requiring between $25,000 and $30,000, and 100% failure rate for those requiring $45,000 to $49,999. However, these results may not be entirely accurate since our sample size was very small for these higher-funding kickstarter groups. While writing the count formulas, I initially had trouble specifying the values, which was resolved once I added in the missing apostrophes. 

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The linegraph reveals that kickstarters in the theater category have the highest chance to be successful if launched in May, June, or July. In addition, those with launch dates in February, April, and August also had success rates higher than 55%. Lastly, the results also suggest those kickstarters launched in December are least likely to be successful, having less than 40% success. Since each group of months had roughly the same amount of samples, with May, June, and July having the most samples, I am confident that launching a campaign during those 3 months should lead to higher success rates.

- What can you conclude about the Outcomes based on Goals?

The results of the linegraph indicate that kickstarters in the play subcategory are more likely to reach its target funding if the asking amount is between 1$ and $5000, or between $35000 and $45000. There is strong evidence indicating that projects asking for less than $5000 funding will be successful due to their larger than average sample sizes, having 86 and 320 total projects respectively in the <1000 and 1000 to 4999 groups. In addition, we can infer that kickstarters having a target funding goal >$45000 are very unlikely to be successful due to their high costs, but this conclusion is not very accurate since there were very few samples in these groups (1 in group 45000 to 49999 and 13 in >50000)

- What are some limitations of this dataset?

Limitations of this dataset include the limited number of samples we have per month. For example, within the play subcategory there is only 1 data value from October 2010 and December 2010, whereas there are 11 data values for April 2014. If the dataset were sufficiently large enough, it would be interesting to graph the lieklihood of kickstarter success for each month within a single year, as trends may vary from year to year based on various economical or other social factors. Furthermore, we are unaware of how each kickstarter was advertised, as some may have been actively shared through social media and advertisements, whereas others may have only been solely listed on the kickstarter website. It is possible that the more people who see the kickstarter, the more likely it is to be successful. It would also be interesting to see how many individuals backed each kickstarter, as some kickstarters that require a lot of funding may have been supported by a few large coorporations as opposed to thousands of individuals.

- What are some other possible tables and/or graphs that we could create?

Some other graphs and visualizations we can create from this dataset include how likely a kickstarter will be successful based on how long the campaign is launched, by subtracting the campaign deadline date from campaign launch date. Since this challenge analyzed the success of US kickstarters, it would also be interesting to visualize results of other countries(ie. GB, SG, AU, etc). Lastly, we could also analyze whether being a kickstarter staff pick influenced the success rate of the campaign.
