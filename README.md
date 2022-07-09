# NBA2020-2021
# This is my Machine Learning project which aims to predict results of NBA 2020-21 regular season games.
# A player based rating system (ESPN's real plus minus) has been used to train model.
# Top 10 players (starting line up and 1st bench) are considered while training the model.
# Considering the player was healthy, most recent performance i.e NBA 2019-2020 has beens considered. If coming off from an injury( for eg steph curry,kevin durant, john wall...), their previous year performances have been considered.
# The most crucial part of rating players, was rating rookies as their espn rpm is not available. For that, based on draft order and intution, rookies have been rated.
# The predicitions heavily rely on players being healthy. Already before the start of season, few injuries( kemba walker out till january...) have ocurred.
# Along with player rating, home and away are also taken care of although first half of season may see empty arenas.
# ensemble of 7 different models with neural network having high weightage( 3 vs 1 ) is combined to form this model.
# Due to the ongoing pandemic, NBA may be forced to postpone, delay, alter the schedule of NBA 2020-21 regular season.
