# IPL Win Percentage Predictor

This project predicts the win percentage of both teams during the second innings of an IPL match using a random forest model. The model is trained on match and ball-by-ball data from 2008 to 2022. The frontend is developed using Streamlit, providing an interactive user experience.

## Datasets

1. **IPL Match Details Dataset**: This dataset contains details of each IPL match from 2008 to 2022. It includes information such as team names, match venue, match result, and more.
2. **IPL Ball-by-Ball Details Dataset**: This dataset contains ball-by-ball details of every match from 2008 to 2022. It includes information such as runs scored, wickets taken, ball bowled by, and more.
   https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset

## Data Preprocessing

Data preprocessing has been performed on both datasets to handle missing values, encode categorical variables, and engineer features necessary for training the random forest model and the logistic regression model.

## Model

A Random forest Model and a Logistic Regression Model has been trained using the preprocessed data to predict the win percentage of both teams during the second innings. The model has been tested and saved for deployment.

## Frontend

The frontend of the application is built using Streamlit, an open-source app framework for Machine Learning and Data Science projects. Streamlit facilitates the rapid development of interactive web applications.
