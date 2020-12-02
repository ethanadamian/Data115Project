# NBA 3-Point Percentage and Salary Correlation Analysis

# Motivation
I downloaded the ASA All NBA data set, that consists of all the players in depth statistics. I will be looking at for example the 3 point percentage of players and if that has any correlation with how much they get paid, compared to others who don't shoot as well. There may be some fascinating results that may or may not shock you. I've always have had a passion for sports analytics. This was a great opportuninty to explore this avenue of diving deep into the data and seeing what I could find and compare. 
# Data Source
I obtained the data from https://advancedsportsanalytics.com whom provides quantitative DFS strategy and tools for fantasy football, basketball, baseball, and golf contests. The aspect of it being used for fantasy sport contests allowed for me to gather more in depth data than other data sources. I also used https://data.world/datadavis/nba-salaries for collecting the salary data for the players. 
# Processing Steps
Luckily the data was already processed and cleaned nicely. It was easy to use and find what I wanted to showcase on python. 
# Visualization
Once I had processed the data, I started the process of gathering the data and making averages and comparing salaries etc. In this table created from python there is 10 players in 2018 that made over 20 million dollars that I randomly choose. However; I excluded Andre Drummond because he only shot 11 threes for the 2017-2018 season. I then took their 3-point averages and it resulted in .43+.45+.38+.34+.40+.36+.42+.38+.36= 3.414/9 = .38 = 38% This is a very good 3-point percentage for NBA standards. 



![image](https://user-images.githubusercontent.com/72041283/100938903-529c6d00-34aa-11eb-910c-9a0eb348a459.png)






# Analysis
I created a scatterplot of the 3-point percentages and salaries for 2018. From the scatterplot you can see that players shooting around 40% receive higher pay than those who don't. However; in the scatterplot you'll see a big blob of dots near the 35-40% range but a lot of those players are either not in the league anymore or shot very few threes as they are on mininum contracts for the most part. 




![image](https://user-images.githubusercontent.com/72041283/100938994-6fd13b80-34aa-11eb-8bf7-4d2c46b126cc.png)


# Descriptions of Code and Materials
There is one jupyter notebook that contains all the data and resources called 3ptandSalary.ipynb


