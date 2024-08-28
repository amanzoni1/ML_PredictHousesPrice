# House Price Prediction

This project aims to predict the sale prices of residential homes in Ames, Iowa, using the well-known Ames Housing Dataset. The project is divided into two key stages: Data Analysis & Feature Engineering and Modeling & Prediction.


### Introduction

This repository contains a comprehensive analysis and prediction pipeline for house prices. By leveraging various regression models, the goal was to identify the best model for predicting house prices with high accuracy.

### Data Analysis & Feature Engineering

Before diving into the modeling process, the dataset underwent extensive cleaning and preprocessing. This stage included:

	•	Exploratory Data Analysis (EDA): Understanding the distribution of variables and the relationships between features.
	•	Handling Missing Values: Imputing missing values with appropriate strategies.
	•	Feature Engineering: Creating new features that could improve model performance, such as total square footage, age of the house, and more.
	•	Encoding Categorical Variables: Converting categorical features into numerical values using techniques like one-hot encoding.
	•	Scaling Features: Standardizing numerical features to ensure consistent model performance.

### Modeling & Prediction

With the data prepared, several machine learning models were trained and evaluated:

	•	Linear Regression: Initial baseline model with poor performance due to its simplicity.
	•	Support Vector Regression (SVR): Improved performance with parameter tuning.
	•	Random Forest Regressor: A strong performer with significant feature importance insights.
	•	AdaBoost Regressor: Provided competitive results with boosting techniques.
	•	Gradient Boosting Regressor: The best-performing model, achieving an R² score above 0.9.

Each model was evaluated based on key metrics, including Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² Score. The best model was selected and retrained on the entire dataset for final predictions.

### Results

	•	Best Model: Gradient Boosting Regressor
	•	R² Score: 0.9544
	•	RMSE: $17,991.02
	•	MAE: $11,851.11

These results indicate that the model is highly effective at predicting house prices in Ames, Iowa.

### Conclusion

The project successfully developed a robust model for house price prediction, with the Gradient Boosting Regressor outperforming other models. The results demonstrate that, with proper data preparation and model selection, it is possible to predict house prices with high accuracy.
