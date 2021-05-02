# Preowned car analysis
This project analyzed the different features affecting the preowned cars' marketing price. 
## First Step: Data preprocessing
I preprocessed the dataset including eliminate outliers at (year, price, etc), normalized the skewness, label-encoding, and performed feature engineering to get the modeling-ready cleaned dataset. Also I performed some EDA to check the distribution of some important features. 
## Second Step: Basic modeling ---- Linear Regression
I used Linear Regression with all the features to get the baseline of the modeling with RMSE = 9033.42
## Third Step: Multiple Machine Learning Models
I used KNN, XGBoost and Random Forest models with cross validation to predict the price, and evaluate different models by comparing their RMSE scores. The best model is Random Forest. 
