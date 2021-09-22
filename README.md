# BillboardTop100-time-series

### Goal of project was to use time series techniques to forecast the top Billboard ranking for a genre.

### Dataset: "Data on Songs from Billboard 1999-2019" dataset from Kaggle, transformed data from ranking by song/genre by week, to average ranking by genre by week

### Statistical Model - Used ARFIMA model, which resulted in 0.19 sMAPE and 14.3 MSE (lowest compared to other models).
####     Application: Predict when genre will be at it's peak, radio stations know when to do heavier marketing.

### Machine Learning Model - Clustered genres with DTW distance to find genres with similar trends.
####     Application: Genres similar to much bigger genres can be played on the radio at the same time.

## CODE
### TS_FinalProject_Dataset.ipynb
#### 1. Contains data processing to transform dataset from ranking by song/genre by week, to average ranking by genre by week
#### 2. Dynamic time warping calculation on 50 genres with most top 100 rankings
#### 3. Clustering of genres using DTW as similarity measure

### Final Project Stats Models_git.rmd
#### Statistical models used to forecast ranking for Rap genre
#### Tried ARIMA, SARIMA, Holt-Winters, and ARFIMA
