# DS5500-PART1

In this project, we will focus on a problem that selecting lineups for daily fantasy sports contests. A brief example: suppose that there are 200 players in a sport league (e.g. NBA). On each game day, we want to select a combination of 8 players, that their summed performance, which is a quantitative variable, is higher than other competitors’ combination. So we can win the contest.

 

The project would contain two parts: first we have to predict player’s performance, i.e. how many fantasy score would a player achieve in the next game. Secondly, we need to come up with an optimization strategy to choose our lineups. Without loss of generosity, we will focus on the NBA for this project, and the method could well extend to other sports.

 

Our dataset is historical statistics record of player’s game log, which includes features like points, rebounds, steals etc.for each player in each game. Also, player’s quantitative performance which is measured by fantasy score, is calculated based on statistics.

 

Our proposed method is to build a model to find out the best combination.
