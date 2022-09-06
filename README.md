# Score_prediction_IPL
### Objective
The objective is to predict the total score of the cricket match by using various features. Dataset contains ball by ball data of the matches played during the 10 seasons of IPL. 

### Important features
    - venue: Stadium where match was played
    - battingteam: Batting team name
    - bowlingteam: Bowling team name
    - runs: Runs scored by team till that point of instance
    - wickets: Number of Wickets fallen of the team till that point of instance
    - overs: Number of Overs bowled till that point of instance
    - runslast5: Runs scored in previous 5 overs
    - wicketslast5: Number of Wickets that fell in previous 5 overs
    - striker: max(runs scored by striker, runs scored by non-striker)
    - non-striker: min(runs scored by striker, runs scored by non-striker)
    - total: Total runs scored by batting team at the end of first innings

### Algorithm vs accuracy

| Algorithm  | Accuracy % |
| ------------- | ------------- |
| Decision tree  | 89.98  |
| Linear regression  | 66.43  |
| Random forest regressor  | 95.89  |
| Lasso regression  | 65.32  |
| Support vector regressor  | 58.30  |
| Neural networks  | 89.31  |
![accuracies_score_prediction](https://user-images.githubusercontent.com/93145713/188705557-c02d6c7c-8610-42c1-88ca-7e08e1ca9c7f.png)

### Final model
        - Random forest
        - Accuracy score - 95.89%
        - Mean Absolute Error (MAE): 3.32
        - Mean Squared Error (MSE): 36.07
        - Root Mean Squared Error (RMSE): 6.005
