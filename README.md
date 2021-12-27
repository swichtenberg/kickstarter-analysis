# Kickstarting with Excel
## Overview of Project
Kickstarter, a crowdfunding platform, helps bring creative projects to life. The platform allows creators to share project ideas and gain funding support from individuals around the world. Common projects include those in the arts, entertainment, and technology.
### Purpose
The purpose of the project is to gain a greater understanding of the factors that influence the success of Kickstarter campaigns. As an up-and-coming playwright, Louise is particularly intersted in an analysis of Kickstarter data that will help guide fundraising decision making for her play, *Fever*. Variables of interest include campaign launch date and fundraising goals of similar projects.
## Analysis and Challenges
Data from over 4,000 Kickstarter projects were analyzed. The data included both completed and live projects from around the world in several categories (e.g., technology, film, theater).
### Analysis of Outcomes Based on Launch Date
First, the outcome of theater projects based on launch date was visualized (below). As can be seen in the graph, there is a peak in successful theater projects in May with a greater numbers of successful projects throughout the summer months. The number of failed and canceled projects is also fairly consistent throughout the year.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96216947/147412100-12993fc9-bc50-4d63-ac6a-37cb75e6175a.png)
### Analysis of Outcomes Based on Goals
Second, the outcome of play projects based on fundraising goal was visualized (below). As can be seen in the graph, the percent of failed projects increases as the total fundraising goal increases. Likewise, the percent of successful projects decreases as the fundraising goal increases.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96216947/147505521-996ed8c9-8269-49c3-a65d-ecaa683bd3e2.png)
### Challenges and Difficulties Encountered
No challenges or difficulties were encountered; however, challenges and difficulties could have included issues with the raw data. Overall, the Kickstarter data was relatively clean and required little manipulation. It is possible the data could have been poorly organized/formatted and did not include the necessary information for the desired analysis. Another difficulty may have been too little data (i.e., small sample size) to complete the analysis.
## Results
### Conclusions
#### Outcomes Based on Launch Date
Two conclusions can be drawn from the relationship between launch date and the success of theater projects. First, the *Theater Outcomes Based on Launch Date* suggests more theater projects succeed than fail. As such, we can conclude there is a higher probability a theater project will succeed than it will fail. In addition, the relationship also suggests there is a greater number of successful projects during the summer months (i.e., May-Aug) without a significant increase in failed projects during the same period. As such, we can conclude there is a higher probability a theater project will succeed if it is launched during the summer.
#### Outcomes Based on Goals
One conclusions can also be drawn from the relationship between the fundraising goal and the success of play projects. As evidenced by the *Outcomes Based on Goal* graph, the number of failed play projects increases as the total fundraising goal increases. As such, we can conclude that a play project with a smaller fundraising goal has a higher probability of succeeding than one with a larger fundraising goal.
### Limitations and Future Analysis
There are a few notable limitations to the dataset and completed analysis. As the data includes projects from around the world, the affect of launch date on project success may be misrepresented. With significant seasonal differences around the world (i.e., northern and southern hemisphere) failed projects during the 'summer' months may have included those that were actually launched in the winter in the southern hemisphere. As such, it may be more accurate to evaluate the impact of launch month at a smaller geographical scale. Likewise, it would be more informative to represent project success as a percentage rather than a count of projects. In addition, the *Outcomes Based on Goal* graph displays goals in US Dollars. Again, as data includes projects from around the world, it appears no conversation factors were applied to standardize monetary values to the US Dollar. This is evident in the *currency* column of the raw data. Further analysis should include conversions to US Dollars. Finally, the analysis did not evaluate the percent of fundraising goal reached. This analysis may be more informative as a $10,000 campaign that raises $9,999 could still be considered a success if the project can move forward.
