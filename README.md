# **Kickstart-analysis**
Kickstart musical and play analysis

## **Overview of Project**
This is a breakdown of Kickstarter data that takes a look at the relationships between the total goal amounts and date creation of projects.

### **Purpose of the project**
The purpose of the porject is to assist Louise's kickstarter project, "Fever".  It is a theatrical play for which the analysis was created to best help Louise determine what could be an optimal time of project creation on Kickstater as well as what range of funding goals are typically successful.

## **Analysis and Challenges**
The result chart files can be viewed [here](https://github.com/deyoungmatthew/Kickstart-analysis/tree/main/Resources).  The analysis was performed by using Kickstarters project data.  To make the data applicable to Louise's upcoming project, we narrowed the data down to Theater projects, with release dates broken down by month.    In regards to determining what project goal totals appeared to most successful, we created twelve caterogies of amount ranges.  The results of the percentage of successful, failed, and canceled events by these ranges can be view on this [chart]( https://github.com/deyoungmatthew/Kickstart-analysis/blob/main/Resources/Outcomes_vs_Goals.png).  While I didn't personally run into any challenges, I could see how the categorizing of the data into not just the amount ranges used, but as well as by project subcategory could be difficult.

### **Analysis of Outcomes Based on Launch Date**
In terms of timing of the project creation date on Kickstater, the data appear to show a correlation between launching the project on Kickstarter sometime in late spring or early summer.  The month of May in parcticular appears to not only highest number of total successes, but the highest ration of succes to failures at 2.13 to 1.  This can been seen in the chart below ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/78942457/109441717-0955ae00-7a04-11eb-980c-02278359c6e9.png)
.  The chart also shows the worst period appears to be in late fall, early winter.  From October through December, the number of successful events is at it's lowest, with December having nearly as many successes as failures.

### **Analysis of Outcomes Based on Goals**
The chart below shows that if Louise is looking for at least a 50-50 chance of succes, her project goal amount shouldn't exceed $20,000.  Projects less than $1,000 have the highest success rate of 75.8%.  Interestingly, projects with goal amounts between $35,000 and $45,000 have succeeded 66.7% of the time.  However, the total amount of projects that have attempted this range of amounts only total 9 evetns, whereas the number of projects $20,000 or less totals 985 individual projects.  THis could mean that there could likely not be enough examples of these large amount projects to get an accurate likelyhood of success.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/78942457/109441705-0064dc80-7a04-11eb-9d09-69b6a7c6dbec.png)


### **Challenges and Difficulties Encountered**
There are a few limitations of the data set including the successful projects where run by individuals that had already run successful Kickstarter projects before.  This also only emcompasses Kickstarter data.  There is a possibility that these Kickstarters are also being partially funded by other sources.  Louise's project myabe smaller than some of the other projects that are looking for less money but ultimately cost more but are being funded by other third parties.  

## **Results**
Based on other projects, Louise will likely achieve a successful result by creating her Project in May.  It is also best for her to avoid creating the project any time between October and December.

Louise should also look to keep her goal amount below $20,000 with the best results if the goal is less than $5,000.

The dataset doesn't include any outside data that could potentially bring the goal amount into sharper focus.  It could also be extremely to gather more data from Kickstarter itself, including data about the individuals that are creating these projects.  A helpful chart that could be created with existing data includes a cross section of successful, failed, cancelled events by both month and goal amount.  It may show that the $30,000 to $45,000 projects succeeded during the winter when smaller events were failing, or they may have succeeded by taking advantage of the apparent spring/summer timeframe where events typically succeed the most. For unknown data, it could useful to see a graph that displays the success rate of individuals as well as what genre of play the project is.
