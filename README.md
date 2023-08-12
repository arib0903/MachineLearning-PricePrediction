# Machine Learning Project: Airbnb Price Prediction

This repository contains the implementation of a machine learning project focused on analyzing an Airbnb dataset to predict the prices of Airbnb listings. The project follows a structured plan to preprocess data, implement models, and evaluate their performance.

## Technologies Used

- **Python:** The entire project is coded in Python, utilizing libraries like Pandas, NumPy, and Scikit-learn for data manipulation, analysis, and machine learning tasks.

- **Pandas:** Used for data loading, cleaning, and exploratory data analysis, aiding in better understanding the dataset.

- **Scikit-learn:** Implemented machine learning models, including Random Forest and Gradient Boosting Regressors, and performed cross-validation and evaluation.


## Project Structure

- **Part 1:** Introduction and project setup.
- **Part 2:** Data loading and exploratory data analysis.
- **Part 3:** Data preparation, handling missing values, and feature selection.
- **Part 4:** One-hot encoding for categorical features.
- **Part 5:** Model implementation: Random Forest and Gradient Boosting.
- **Part 6:** Model tuning via stacking using Stacking Regressor.
- **Part 7:** Evaluation and analysis of model results using Root Mean Squared Error and R^2

# Analysis of Results

### Comparing Stacking and Random Forest

- **Stacking Model's RMSE:** 89.22
- **Random Forest Model's RMSE:** 89.70

### The stacking model marginally outperformed the Random Forest model, with a slightly lower RMSE.

Random Forest vs. Gradient Boosting in R² Metrics

- **Random Forest (RF) R²:** 0.618
- **Gradient Boosting (GBDT) R²:** 0.580

