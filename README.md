# Scouting Classification with Machine Learning
![Scouting Classification with ML](https://user-images.githubusercontent.com/84645968/217363150-af61f02d-bba7-4521-a249-c3f5152c616f.png)

## Business Story
Predicting which class (average, highlighted) players are according to the scores given to the characteristics of the football players watched by the Scouts.
## Dataset
The data set consists of information from Scoutium, which includes the features and scores of the football players evaluated by the scouts according to the characteristics of the footballers observed in the matches.
#### scoutium_attributes.csv
8 Features | 10.730 Observations | 527 KB
| Feature | Definition |
| --- | --- |
| task_response_id | The set of a scout's assessments of all players on a team's roster in a match |
| match_id | The id of the relevant match |
| evaluator_id | The id of the evaluator(scout) |
| player_id | The id of the relevant player |
| position_id | The id of the position played by the relevant player in that match |
1: Goalkeeper
2: Stopper
3: Right Back
4: Left Back
5: Center Defensive Midfielder
6: Center Midfielder
7: Rightwinger
8: Leftwinger
9: Center Attacking Midfielder
10: Forward
| analysis_id | A set containing a scout's attribute evaluations of a player in a match |
| attribute_id | The id of each attribute the players were evaluated for. |
| attribute_value | Value (points) given by a scout to a player's attribute |

#### scoutium_potential_labels.csv
5 Features |  322 Observations | 12 KB
| Feature | Definition |
| --- | --- |
| task_response_id | The set of a scout's assessments of all players on a team's roster in a match |
| match_id | The id of the relevant match |
| evaluator_id | The id of the evaluator(scout) |
| player_id | The id of the relevant player |
| potential_label | Label that indicates the final decision of a scout regarding a player in a match. (target variable) |

## Requirements
```
catboost==1.1.1
lightgbm==3.2.1
matplotlib==3.4.3
numpy==1.20.3
pandas==1.3.4
seaborn==0.11.2
session_info==1.0.0
sklearn==0.24.2
xgboost==1.7.3
```
## Author
[Çağla Deniz Doruk](https://github.com/cagladenizdoruk)
