# My-personal-data-set



# NHL Special Teams Statistics 2018-2019 Season

# Motivation
As a former hockey player, I always wondered how much of an impact special teams in the big league and so I wanted to try and correlate the top teams in the NHL to their power play and penalty kill rankings. From my personal experience, when I started to play at higher levels, the special teams became more and more important so I wanted to see how much impact it had at the highest level of hockey.

# Data Process
The Data that I obtained came from
https://www.hockey-reference.com/leagues/NHL_2019.html and https://www.espn.com/nhl/statistics/team/_/stat/special-teams/sort/powerPlayPct/year/2019/league/east.

The First link is for the NHL league rankings which is just what I wanted to compare with the special teams data. The second link is from ESPN where the NHL special teams data came from. In terms of cleaning I basically uploaded the data into an excel file then removed the strings that I did not need so that I could use R Studios to make a visualization. Also note that anything in the file that has a decimal in it is a percentage and I did not use it. I just wanted to use raw numbers and not calcualted percentages. 

# Visualization

<img src = "https://raw.githubusercontent.com/swiranata/My-personal-data-set/main/Power%20play%20goals%20for%20vs%20against%20figure.PNG">
The figure shows the connection between teams power play goals for versus against. It can be inferred that the top team for special teams has a higher power play goals for and much lower power play goals against. You can also see there are a couple points where the power play goals agasint was very high compared to power play goals for which can infer that those are most likely the weakest teams. 

