# SocialNetworkAnalysis
In this repository I share a detailed project done for a course about Social Network Analysis at IE HST.

# 1. Madrid's Bike Sharing System compared to New York's and Montreal's
With the high increase in bicycle sharing systems in most large cities around the world, I found it interesting to analyze and compare some of the best established ones. I here use a different approach that would ususally be applied on such data. Indeed, I use a Network Analysis to try finding insights.

In this project, I focus on turning bike trips into  networks that we can analyze. Thus throughout the study, I established networks in which the nodes are the bike stations throughout the city, and the edges are the flows of the trips in each direction between the stations. And the edges are weighted by the number of trips carried out by the bikes on that edge. 

The different cities analyzed here are Montreal, New York, and Madrid which respectively started operating those bicycle sharing systems in 2009, 2013, and 2014.

Here is a snapshot of Madrid's network that we explain in the study:

![Madrid's Network over 3 years](/1_Madrid_Montreal_NY_bikes/graphs/madrid.png)

The goal of this research would be to try finding similarities and differences in the networks of these cities' systems as well as finding interesting patterns within each city. 

Here is another look at the comparison of the networks of the 3 cities is:

![Comparison between the 3 cities](/1_Madrid_Montreal_NY_bikes/graphs/comparison.png)

We also look at specific aspects of the bike systems and try to come up with insights. One of these is the following graph highlighting the different behaviors of users in the Madrid network:

![Madrid's users; behaviors](/1_Madrid_Montreal_NY_bikes/graphs/madrid_users.png)

This project was made possible with the help of my colleague Begoña Frigolet. The tools used for the project are the following:

- R for the analysis and the report in a Markdown format;
- Python for data transformation;
- Gephi for some of the visualizations of our networks;
- FlowingBlue for maping the networks on mapped backgrounds.

To be able to reproduce most of the work, you will just need to dowload the data from the sources mentionned in the report. To be able to reproduce the maps on FlowingBlue, you can take a look at my other repository (FlowMap) in which I extensively explain how to use this tool. I here attach the Python notebook for the data preparation, the R markdown, as well as the final HTML report.


