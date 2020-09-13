# Cricket Simulation
I have tried to implement The cricket simulation model where the first innings score is predicted using ML algorithms.
## Dataset
A complete set of cricket dataset for test and limited overs is available on https://cricsheet.org/downloads/.
<br/>For my simulation I've retrieved a dataset which has the data for the teams of England and Ireland, England being the batting team and Ireland being the bowling team : https://github.com/codophobia/CricketScorePredictor/blob/master/data/odi.csv

### Each dataset consists of the following columns:
- mid: Each match is given a unique number
- date: When the match happened
- venue: Stadium where match is being played
- bat_team: Batting team name
- bowl_team: Bowling team name
- batsman: Batsman name who faced that ball
- bowler: Bowler who bowled that ball
- runs: Total runs scored by team at that instance
- wickets: Total wickets fallen at that instance
- overs: Total overs bowled at that instance
- runs_last_5: Total runs scored in last 5 overs
- wickets_last_5: Total wickets that fell in last 5 overs
- striker: max(runs scored by striker, runs scored by non-striker)
- non-striker: min(runs scored by striker, runs scored by non-striker)

## Algorithm Used

Support Vector Machines : cricket_pred_SVM
<br>Random Forest Regression : cricket_predictions

