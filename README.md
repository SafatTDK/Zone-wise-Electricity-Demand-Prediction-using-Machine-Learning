This project develops a machine learning solution to forecast daily electricity demand across nine distinct zones in Bangladesh. Using a historical dataset from the Bangladesh Power Development Board (BPDB) spanning from 2020 to 2025, we performed extensive data preprocessing and advanced feature engineering, creating time-based, lag, and rolling-window features to capture temporal patterns. A comprehensive suite of machine learning models was implemented, including baseline regressors, advanced boosting algorithms, neural networks (MLP and LSTM), and ensemble methods. Our findings show that the Ensemble (Stacking) Regressor achieved the highest performance, with an R-squared score of 0.9841, demonstrating exceptional accuracy. The results indicate that a combination of robust feature engineering and sophisticated ensemble techniques can produce highly reliable demand forecasts, offering a valuable tool for optimizing power distribution and reducing load shedding.
Model Implementation:
A total of 16 models were trained and evaluated to identify the best performer.
o	Linear Regression
o	Decision Tree
o	Support Vector Regressor (SVR)
o	K-Neighbors Regressor (KNN)
o	Random Forest
o	Bagging Regressor
o	Gradient Boosting
o	AdaBoost
o	XGBoost
o	LightGBM
o	CatBoost
o	Multi-layer Perceptron (MLP)
o	LSTM
•	Ensemble Models:
o	Voting Regressor: Combined the predictions of Random Forest, LightGBM, and XGBoost.
o	Stacking Regressor: Used Random Forest, LightGBM, and XGBoost as base models and a Linear Regression as the final meta-learner.

