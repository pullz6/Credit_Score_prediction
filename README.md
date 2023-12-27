# Credit_Score_prediction

This is a project to predict the redit score based on the below dataset: 

Link to kaggle dataset -> https://www.kaggle.com/datasets/conorsully1/credit-score/data

Process: 

1. The data was preprocessed
     a. Removing unwanted columns
     b. Converting categorical data into numerical values through Label Encoding
     c. Converting the converted categorical data with One-hot encoding.
     d. Normalizing the dataset with Min - Max scaler

2. Training with SVR , KNeighborsRegressor , DecisionTreeRegressor
3. Stacking these models together, with Linear Regression as the final model (meta model)
4. Predicting the values
