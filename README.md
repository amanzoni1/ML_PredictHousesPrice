# House Price Prediction

This project aims to predict the sale prices of residential homes in Ames, Iowa, using the well-known Ames Housing Dataset. The project is divided into two key stages: Data Analysis & Feature Engineering and Modeling & Prediction.


### Introduction

This repository contains a comprehensive analysis and prediction pipeline for house prices. By leveraging various regression models, the goal was to identify the best model for predicting house prices with high accuracy.

### Data Analysis & Feature Engineering

Before diving into the modeling process, the dataset underwent extensive cleaning and preprocessing. This stage included:

- **Exploratory Data Analysis (EDA)**:
  - **Understanding Distributions**: Analyzed the distribution of key variables such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and maximum heart rate.
  - **Relationship Exploration**: Investigated relationships between features and the target variable to identify potential predictors.

- **Handling Missing Values**:
  - **Imputation Strategies**: Applied appropriate methods to impute missing values, ensuring the integrity of the dataset.

- **Feature Engineering**:
  - **Creating New Features**: Developed new features that could enhance model performance, such as total square footage, age of the house, and other derived metrics.
  - **Interaction Terms**: Explored interaction terms between features to capture more complex relationships.

- **Encoding Categorical Variables**:
  - **One-Hot Encoding**: Converted categorical features into numerical values using one-hot encoding to make them suitable for regression models.

- **Scaling Features**:
  - **Standardization**: Standardized numerical features to ensure consistent model performance and improve convergence during training.



### Modeling & Prediction

With the data prepared, several machine learning models were trained and evaluated:

- **Linear Regression**: Initial baseline model with poor performance due to its simplicity.
- **Support Vector Regression (SVR)**: Improved performance with parameter tuning.
- **Random Forest Regressor**: A strong performer with significant feature importance insights.
- **AdaBoost Regressor**: Provided competitive results with boosting techniques.
- **Gradient Boosting Regressor**: The best-performing model, achieving an R² score above 0.9.

Each model was evaluated based on key metrics, including Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² Score. The best model was selected and retrained on the entire dataset for final predictions.

### Results

The Gradient Boosting Regressor was selected as the final model due to its superior performance:

- **R² Score**: 0.9851
- **Mean Absolute Error (MAE)**: \$7,436.74
- **Root Mean Squared Error (RMSE)**: \$9,756.22

These results indicate a high level of accuracy, with the model successfully predicting house prices within a small margin of error.

### Conclusion

The project successfully developed a robust model for house price prediction, with the Gradient Boosting Regressor outperforming other models. The results demonstrate that, with proper data preparation and model selection, it is possible to predict house prices with high accuracy.
