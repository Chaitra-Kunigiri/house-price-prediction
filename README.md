# House Price Prediction

A machine learning project that predicts house prices from features such as
median income, house age, number of rooms, and location.

## Objective
Build and compare regression models to predict median house value.

## Dataset
California Housing dataset (scikit-learn), about 20,000 records and 8 features.

## Workflow
1. Data exploration (distributions, correlation heatmap, location map)
2. Preprocessing (missing value handling, feature scaling with a Pipeline)
3. Train/test split (80/20)
4. Model training: Linear Regression (baseline) and Random Forest
5. Evaluation with MSE, RMSE, MAE and R²
6. Feature importance analysis

## Results
| Model             | RMSE | R²   |
|-------------------|------|------|
| Linear Regression | 0.6429 | 0.5689 |
| Random Forest     | 0.4636 | 0.7758 |

Median income and location were the strongest predictors of price.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
pip install pandas numpy matplotlib seaborn scikit-learn joblib
jupyter notebook House_Price_Prediction.ipynb

## Future Improvements
- Hyperparameter tuning with GridSearchCV
- Try Gradient Boosting / XGBoost
- Deploy as a Streamlit web app
