# API Web-Scraping NBA Stats in Python
# Introduction
In the first part of the project(main.ipynb), I scrape data from nba.com/stats for analysis, found NBA APIs, and scrape data on a large scale with the Python requests package. As the data was scraped from 2014-2023 regular season, and the playoffs as well. In the second part of the project(analysis.ipynb), I used the data that I scraped so that I can visualize three main topics regarding NBA stats:

1) Player stat correlations
2) Player scoring distributions (Playoffs vs. Regular Season)
3) How the game has changed over the past decade (Playoffs vs. Regular Season)

# Analysis
1) Player stat correlations
- For this, I used a for loop to get all the important stat lines to see the correlations between the players that have atleast played 50 minutes in a season.
- We can use this to correlate between stats. For instance, if a player has a high FGA then their points would be high as well.

![image](https://github.com/AJsimplydevelops/Web-Scraping/assets/78631693/8195786f-f145-43c1-a18b-71a86fbfa74d)

2) Player scoring distributions (Playoffs vs. Regular Season)
- For this, I showed the figures that shows how points are distributed from players between playoffs and the regular season. Using the histogram function to visualize this effectively.
- As we conclude, more players are scoring higher averages in the playoffs.

Regular season: 
![image](https://github.com/AJsimplydevelops/Web-Scraping/assets/78631693/50e7d2d8-20c6-482c-b5a0-417d98ebd0cd)

Playoffs:
![image](https://github.com/AJsimplydevelops/Web-Scraping/assets/78631693/b851e0d9-1547-4b70-81aa-488189136ada)

3) How the game has changed over the past decade (Playoffs vs. Regular Season)
For this, I integrated a new column in my dataframe which is POSS_per_48 that calculates the efficiency of possession. Used a line chart to effectively display how it has changed 
- We conclude the game has evolved since there's more points, more 3's are being taken, as well as possessions are more effective.

![image](https://github.com/AJsimplydevelops/Web-Scraping/assets/78631693/efde82a7-af3d-43aa-a742-ddecc12d1da8)



