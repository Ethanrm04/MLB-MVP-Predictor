This link is for a reference point:
[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

About what to do with READMEs:
[AboutREADMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

# Proposed working project title

Determining MVP Winners in Major League Baseball: A Statistical Baseline Analysis

# Brief Background

In the world of sports, players aim to be the best of the best. Whether that is winning the end of the year championship (World Series, Super Bowl, etc.) or the individual awards. In most cases the most important individual award is the league’s Most Valuable Player. This leads to the question of what combination of player performance metrics best predicts the winner of the Major League Baseball’s (MLB) Most Valuable Player (MVP) award.

# Question

Is it possible to predict the potential MLB MVP Winners?
Are the winner/s of these awards chosen by statistics or popularity or a combination of both?

# Hypothesis and Predictions

## Hypothesis

Within this project we hypothesize that a player’s offensive performance metrics (batting average, home runs, runs batted in, and on-base percentage) combined with advanced statistics (such as Wins Above Replacement, WAR) are strong predictors of winning the American League’s and National League’s Most Valuable Player award.

## Predictions

We predict that players with higher offensive performance metrics and superior advanced statistics are more likely to win the American League (AL) or National League (NL) Most Valuable Player award. By leveraging these metrics, it is possible to accurately forecast MVP award winners with a high degree of accuracy.

# Data Dictionary

**Rank**

Description: Ranking of players in MVP Voting.
Options: 
1. First
2. Second
3. Third
4. Fourth
5. Fifth
6. Sixth
7. Seventh
8. Eighth
9. Ninth 

**Name**

Description: The name of the player.

**Tm**

Description: Team that the player played on that year of voting.

**League**

Description: Major League baseball is split equally into 2 leagues. League indicates which league the specific team was a part of.
Options:
-AL: American League
-NL: National League

**Year**

Description: Indicates the year in which the voting had occurred.

**Vote.Pts**

Description: Is the total number of points that is obtained from the amounts of placements per ballot. (Ex: 1st place is 14 pts, 2nd place is 9 pts, etc. from 30 ballots per league) 

**X1st.Place**

Description: Number of 1st place votes.

**Share**

Description: The vote points divided by most points possible. Unanimous choice is 100%.

**WAR**

Description: * *Wins Above Replacement* *. A single number that presents the number of wins the player added to the team above what a replacement player from the minor leagues would add.
-8+ is MVP Quality
-5+ is All-Star Quality 
-2+ is Starter
-0-2 is Reserve
-< 0 is Replacement Level

**G** 

Description: * *Games Played* *. The number of games played by the player in that specific season.

**AB**

Description: * *At Bats* *. The number of at bats the player had in the specific season.

**R**

Description: * *Runs Scored* *. The amount of times the player has scored during that season.

**H**

Description: * *Hits* *. The number of hits the player had during that season.

**HR**

Description: * *Home Runs* *. Number of home runs the player hit during that season.

**RBI**

Description: * *Runs Batted In* *. Is the number of times where the result of the player’s plate appearance is a run being scored during that season.

**SB**

Description: * *Stolen Bases* *. THe number of stolen bases by the player during that season.

**BB**

Description: * *Bases on Balls/Walks* *. The number of times the player has been walked during their plate appearance over the course of the season.

**BA**

Description: * *Batting Average* *. H / AB 

**OBP**

Description: * *On-base Percentage* *. (H + BB + HBP) / (AB + BB + HBP + SF)
-HBP: Hit By Pitch
-SF: Sacrifice Fly hit

**SLG**

Description: * *Slugging* *. Total Bases divided by At Bats OR (1B + 2*2B + 3*3B + 4*HR) / AB
-1B: Single
-2B: Double
-3B: Triple

**OPS**

Description: * *On-base Plus Slugging* *. One-Base Percentage + Slugging Percentage.

**Winners**

Description: Indicates who won the MVP Award that season.
Options:
-1: Won
-0: Lost

