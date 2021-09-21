# BillboardTop100-time-series

# Goal of project was to use time series techniques to forecast the top Billboard ranking for a genre.

# Dataset: "Data on Songs from Billboard 1999-2019" dataset from Kaggle, transformed data from ranking by song/genre by week, to average ranking by genre by week

# Statistical Model - Used ARFIMA model, which resulted in 0.19 sMAPE and 14.3 MSE (lowest compared to other models).
## Application: Predict when genre will be at it's peak, radio stations know when to do heavier marketing.

# Machine Learning Model - Clustered genres with DTW distance to find genres with similar trends.
## Application: Genres similar to much bigger genres can be played on the radio at the same time.
