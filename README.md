# Game_Success_Classification
Video games have been one of the fastest-growing industries in the last decade, with revenues increasing from 32 billion dollars in 2012 to 192 billion dollars in 2022. In 2021, Steam recorded a total concurrent player count of 26.09 million, and this figure only applies to players in their platform games. In the long run, having such a large amount of traffic provides any game developer with enough and more data on user behavior to help predict the success of specific games.In this project,we attempt to correlate a few independent variables in order to successfully predict the overall success rate of particular games in a given sales region.

We started with data cleaning and preprocessing, which involved cleaning missing and NaN values. Next comes identifying relevent variables and dropping the unnecessary columns. Later we transformed our variables according to the goal of the project and for easing the work with data.
We proceeded to transform our target variable to a column of the name of the country with maximum sales. We used Label encoding for all our categorical predictors.

Since the project aimed to determine the most successful sales region for games, employing the K-Nearest Neighbors (KNN) model, a popular choice for categorical variables, we classified which country is likely to achieve the highest success. Given that both target and predictor variables are categorical, KNN proves effective in classifying data and identifying the seven nearest neighbors to determine the product's sales region. For evaluation metrics, we used RMSE and Accuracy Score along with confusion matrix. The results of our Knn model show a modest predictive power with an accuracy score above baseline accuracy of random guessing (0.6 > 0.5).
 
## Game sales dataset
https://www.kaggle.com/datasets/gregorut/videogamesales

