
## Overview
The NBA has grown exponentially in the last 10 years. Both in popularity and in how the game is generally been played. A player that is taller usually plays closer to the basket, but as the game has evolved, those same types of players aren’t playing the traditional position. The NBA has 5 standard positions. Point guard, shooting guard, small forward, power forward, and center. Those positions do not reflect the current state of the game. I want to reclassify these positions into more detailed and descriptive roles. An example of someone being labeled as a position but plays something entirely different would be LeBron James. He runs the point or plays a wing position, but is labeled as a Small Forward. These types of players are becoming more and more prevalent in today’s game, and I aim to reclassify the positions into roles that a player plays on a team. In addition, I wanted to see which types of players are found on winning teams. The season that is apart of this study is for the 2018-2019 season. 

## Defining a Player the Traditional Way
Traditionally, players are labeled into 5 positions. Point guard, shooting guard, small forward, power forward, and center. Those labels are given based on 3 factors mainly. Height, how tall a player. Weight, how heavy and strong a player is. Quickness, how that player’s lateral movement relates to other players and their overall speed. There are other small factors that are considered, but these are the main ones. 

[IMAGE]

## EDA
The graph below is very interesting. It shows the change over time regarding the number of shots taken over the past 20 years or so. As you can see, the number of 3-pointers taken has surpassed the number of free throws taken. Showing that the game is or has changed. 

[IMAGE] 


##Methods Used
I used the K-means clustering algorithm to segment the players based on their performance stats. The stats that were used consisted of, Offensive Rebound %, Defensive Rebound %, Assist %, Block %, Turnover %, and distance from the shots taken (0 - 3 feet, 3 -10 feet, 10 -16 feet, 16 feet - 3pt line). All of these stats were taken per 100 possession and then normalized for uniformity. To note, I eliminated platers that were not relevant in the analysis. So players that did not play more than 400 minutes were taken out. 

## Cluster Results 
After picking 12 different types of clusters for the different types of roles, I was able to segment players based on the stats into roles on the team for which I gave them those labels. 

[IMAGE]

## Roles on the most winningest teams
The chart below shows the percentage of roles in winning teams. I defined a winning team has having a positive overall point average if you subtracted the overall opposition points from it. 

[IMAGE]

## Next Steps
I could do this type of clustering for each decade and see how the teams over the years have changed in terms of player performance and playing styles. I would also be very interested in exploring the theory that there are not 5 player position, but actually 3. 
