# Evaluating-the-Effectiveness-of-Machine-Learning-Models-for-Performance-Forecasting-in-Basketball

## Introduction

This repository has been established in conjunction with the publication of the research paper "Evaluating the Effectiveness of Machine Learning Models for Performance Forecasting in Basketball: A Comparative Study". It serves as a supplementary resource for researchers, analysts, and enthusiasts, conducting in-depth analyses, and creating predictive models related to the game of basketball.

Within this repository, you will find a carefully curated collection of data that spans various aspects of the sport for the seasons 2019-20 up to 2021-22, including player performance, team statistics, game outcomes, and more. The data is presented in a structured format, making it accessible for both novice data enthusiasts and seasoned statisticians.

## Data Source

The statistics and data contained within this repository have been collected from the official [NBA website](https://www.nba.com/stats/). The data is used under the terms of their use policy, and all appropriate credit for the original data collection goes to the NBA.

Please note that this repository is not affiliated with, sponsored by, or endorsed by the NBA.

## Repository Contents

- `Player Stats`: Detailed player statistics, including points, rebounds, assists, and efficiency metrics.
- `Team Stats`: Aggregated team performance data covering various aspects of gameplay.
- `Game Records`: Historical game results, scores, and significant in-game events.
- `Advanced Metrics`: Computationally derived statistics that offer deeper insights into player and team performance.
- `Momentum Averages`: Trend data that captures the performance dynamics of players and teams over time.

## How to Use This Data

The data provided in this repository can be utilized for a multitude of purposes:
- **Sports Analytics**: Leverage the data to conduct detailed sports analytics and research studies.
- **Machine Learning Projects**: Use the dataset as a training ground for predictive modeling and machine learning applications.
- **Fan Engagement**: Create interactive visualizations and tools to enhance fan engagement and understanding of the game.
- **Educational Use**: Employ the dataset as an educational tool for teaching statistical analysis and data science concepts through sports.

# Glossary examples of Basketball Statistics and KPIs

## Standard Metrics
- `SEASON_YEAR`: The NBA season during which the games were played.
- `PLAYER_ID`: A unique identifier for each player in the NBA.
- `PLAYER_NAME`: The full name of the player.
- `NICKNAME`: The player's commonly known nickname.
- `TEAM_ID`: A unique identifier for each team in the NBA.
- `TEAM_ABBREVIATION`: The three-letter abbreviation representing the team.
- `TEAM_NAME`: The full team name.
- `GAME_ID`: A unique identifier for each NBA game.
- `GAME_DATE`: The date on which the game was played.
- `H/A`: Denotes whether the player's team was at home (H) or away (A).
- `REB`: Rebounds grabbed by the player.
- `AST`: Assists made by the player.
- `PTS`: Total points scored by the player.
- `PLUS_MINUS`: The point differential when the player is on the court.
- `NBA_FANTASY_PTS`: Fantasy points based on the NBA's fantasy point system.
- `PERIOD`: The quarter or overtime period of the game.
- `NET_RATING`: The team's point differential per 100 possessions while the player is on the court.
- `AST_TO`: Assist to turnover ratio.
- `AST_RATIO`: The number of assists per 100 possessions by the player.
- `EFG_PCT`: Effective field goal percentage, adjusting for the fact that a 3-point field goal is worth one more point than a 2-point field goal.
- `USG_PCT`: Usage percentage, an estimate of the percentage of team plays used by a player while on the floor.
- `PACE`: The number of possessions a team uses per game.
- `PIE`: Player Impact Estimate, a measure of a player's overall statistical contribution.
- `FOUR_FACTORS`: Four statistical categories that correlate highly with a team's success.
- `TENDEX`: A basketball player performance rating system.
- `GMSC`: Game Score; a rough measure of a player's productivity for a single game.
- `EFF`: Efficiency; a composite basketball statistic that is derived from basic individual statistics.
- 
## Advanced Metrics
- `TEAM_PERIOD`: The game period (quarter/overtime) being analyzed for the team.
- `OPPONENT`: The opposing team.
- `LAST_MATCH_OPP_TEAM_PTS_OFF_TOV`: Points off turnovers by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PTS_2ND_CHANCE`: Second-chance points by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PTS_FB`: Fast break points by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PTS_PAINT`: Points in the paint by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_EFG_PCT`: Effective field goal percentage by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_FTA_RATE`: Free throw attempt rate by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_OREB_PCT`: Offensive rebound percentage by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_AST`: Assists by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_TOV`: Turnovers by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_STL`: Steals by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_BLK`: Blocks by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PF`: Personal fouls by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PFD`: Personal fouls drawn by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_PTS`: Total points scored by the opponent in their last match.
- `LAST_MATCH_OPP_TEAM_NET_RATING`: Net rating of the opponent in their last match.


## Momentum Metrics
- `MOMENTUM`: Metrics that are designed to capture the recent performance trend of a player or team.
- `LAST_MATCHES_3_DAYS_WL_SUM`: Sum of wins and losses over the last 3 days.
- `LAST_MATCHES_3_DAYS_DD2_SUM`: Sum of double-doubles over the last 3 days.
- `LAST_MATCHES_3_DAYS_TD3_SUM`: Sum of triple-doubles over the last 3 days.
- `LAST_MATCHES_3_DAYS_MIN_SUM`: Total minutes played over the last 3 days.
- `LAST_MATCH_WL`: Win or loss in the last match.
- `LAST_MATCH_MIN`: Minutes played in the last match.

## Averages and Percentages
- `AVG`: Average value of a statistic over a specified period.
- `PCT`: Percentages, often used for shooting metrics (e.g., FG%, 3P%).

## Per Game Metrics
- `FGM_PG`: Field goals made per game.
- `FGA_PG`: Field goals attempted per game.
- `PTS_OFF_TOV`: Points off turnovers per game.

## Rest Days Metrics
- `LAST_MATCH_REST_DAYS`: The number of days a player rested before the last match.

## Engineering Examples
- `LAST_MATCH_DD2`: Indicates whether a player achieved a double-double (e.g., points and rebounds, points and assists) in the last match.
- `LAST_MATCH_TD3`: Indicates whether a player achieved a triple-double (e.g., points, rebounds, and assists) in the last match.
- `LAST_MATCH_WNBA_FANTASY_PTS`: Fantasy points scored by the player in the last match based on the Women's National Basketball Association's (WNBA) fantasy scoring system.
- `LAST_MATCH_VIDEO_AVAILABLE_FLAG`: A binary indicator of whether video highlights are available for the player's last match.
- `LAST_MATCH_E_OFF_RATING`: The estimated offensive rating for the player in the last match.
- `LAST_MATCH_OFF_RATING`: The actual offensive rating for the player in the last match.
- `LAST_MATCH_sp_work_OFF_RATING`: A specialized or adjusted offensive rating for the player in the last match.
- `LAST_MATCH_E_DEF_RATING`: The estimated defensive rating for the player in the last match.
- `LAST_MATCH_DEF_RATING`: The actual defensive rating for the player in the last match.
- `LAST_MATCH_sp_work_DEF_RATING`: A specialized or adjusted defensive rating for the player in the last match.
- `LAST_MATCH_E_NET_RATING`: The estimated net rating for the player in the last match.
- `LAST_MATCH_NET_RATING`: The actual net rating for the player in the last match.
- `LAST_MATCH_sp_work_NET_RATING`: A specialized or adjusted net rating for the player in the last match.
- `LAST_MATCH_AST_PCT`: The percentage of team field goals the player assisted on in the last match.
- `LAST_MATCH_AST_TO`: The assist-to-turnover ratio for the player in the last match.
- `LAST_MATCH_AST_RATIO`: The number of assists the player averaged per 100 possessions in the last match.
- `LAST_MATCH_OREB_PCT`: The percentage of available offensive rebounds the player grabbed in the last match.
- `LAST_MATCH_DREB_PCT`: The percentage of available defensive rebounds the player grabbed in the last match.
- `LAST_MATCH_REB_PCT`: The percentage of total rebounds the player grabbed in the last match.
- `LAST_MATCH_TM_TOV_PCT`: The percentage of turnovers per 100 plays for the player's team in the last match.
- `LAST_MATCH_E_TOV_PCT`: The estimated turnover percentage for the player in the last match.
- `LAST_MATCH_EFG_PCT`: The player's effective field goal percentage in the last match.
- `LAST_MATCH_TS_PCT`: The player's true shooting percentage, which takes into account 2-point field goals, 3-point field goals, and free throws, in the last match.
- `LAST_MATCH_USG_PCT`: The player's usage percentage in the last match.
- `LAST_MATCH_E_USG_PCT`: The estimated usage percentage for the player in the last match.
- `LAST_MATCH_E_PACE`: The estimated pace factor for the player in the last match, which is an estimate of the number of possessions per 48 minutes.
- `LAST_MATCH_PACE`: The actual pace factor for the player in the last match.
- `LAST_MATCH_PACE_PER40`: The pace factor for the player in the last match, normalized per 40 minutes.
- `LAST_MATCH_sp_work_PACE`: A specialized or adjusted pace factor for the player in the last match.
- `LAST_MATCH_PIE`: The Player Impact Estimate for the player in the last match, which measures a player's overall statistical contribution.
- `LAST_MATCH_POSS`: The number of possessions the player was involved in during the last match.
- `LAST_MATCH_FGM_PG`: The average number of field goals made by the player per game, up to the last match.
- `LAST_MATCH_FGA_PG`: The average number of field goals attempted by the player per game, up to the last match.
- `LAST_MATCH_PTS_OFF_TOV`: The points the player scored off turnovers in the last match.
- `LAST_MATCH_PTS_2ND_CHANCE`: The second-chance points the player scored in the last match.
- `LAST_MATCH_PTS_FB`: The fast break points the player scored in the last match.
- `LAST_MATCH_PTS_PAINT`: The points the player scored in the paint in the last match.
