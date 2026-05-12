# Formula 1 2025 Race Results
The dataset I will be using is a Formula 1 2025 race results. I’m using this dataset to see
each drivers race result from each place they raced at. There also a lot of other variables
that can also affect a drivers race result like weather, mechanical issues and the track they
are racing on since each track is different. My variables are the Starting Grid, Team, Driver,
Fastest Lap, and Lap Time. Since my outputs are numerous and continuous, this is a
regression problem. I will be using a random forecast regression model to predict formula 1
race points.

Dataset:
F1_2025_RaceResults.csv

Methods:
The project used data wrangling, exploratory data analysis, feature engineering, Random Forest regression, model evaluation metrics, and visualization techniques to predict Formula 1 race points.

Findings:
1. Starting grid position was one of the strongest predictors of race points.
Drivers who started closer to the front of the grid generally earned more points.

2. Team performance had a major impact on results. Top teams consistently
scored higher average points than lower ranked teams.

3. Drivers who achieved the fastest lap or maintained faster lap times
tended to finish with higher point totals.

4. The Random Forest model performed well because it captured nonlinear
relationships between race conditions, driver skill, and team performance.

5. Feature importance results showed that variables related to race pace,
starting position, and team strength contributed the most to predicting points.

6. The Actual vs Predicted plot showed that most predictions followed the
overall trend of the observed values, showing the model was reasonably accurate.

7. Some prediction error remained because Formula 1 races contain uncertainty
such as crashes, penalties, weather conditions, and mechanical failures that
are difficult to fully capture in the dataset.
