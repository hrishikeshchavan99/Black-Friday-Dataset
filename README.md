# Black-Friday-Dataset
     Problem: Predict purchase amount.

   This dataset comprises of sales transactions captured at a retail store. It’s a classic
dataset to explore and expand your feature engineering skills and day to day
understanding from multiple shopping experiences. This is a regression problem. The
dataset has 550,069 rows and 12 columns.

Dataset: https://datahack.analyticsvidhya.com/contest/black-friday/

## EDA
Performed exploratary data analysis on training data
## PCA
Performed feature engineering/selection and dimensionality reduction using principle component analysis(PCA) 
## Model
To find best model, We tried following algorithms:
1) Lasso regression
2) Ridge regression
3) Linear regression
4) Random Forest
5) Extreme Gradient Boosting(XGBoost)
6) Elastic Net regression
7) Extreme Trees regression
8) Support vector machine(SVM)
9) K nearest neighbour(KNN)<br>
     out of which, XGBoost has given best results.
## Fine tuning
For fine tuning of the model, We tried to reduce RMSE obtained from XGBoost by changing the hyperparameters and preprocessing techniques.

Training data: train.csv <br> size: (550069, 12)<br>
We split it as 80:20 where 20% is for validation set

Test data: test.csv <br> size: (233599, 11)

   ### Final RMSE value obtained: 2535

final_prediction.csv: countain finally predicted purchase values.
