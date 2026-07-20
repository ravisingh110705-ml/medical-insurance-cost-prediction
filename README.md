# Medical Insurance Cost Prediction

A regression model that predicts medical insurance charges based on personal attributes, built and evaluated using multiple ML models.

## Problem

Insurance charges vary a lot between individuals. This project predicts a person's expected insurance cost using their age, sex, BMI, number of children, smoking status, and region.

## Dataset

The dataset includes the following features:
- `age`, `sex`, `bmi`, `children`, `smoker`, `region`
- Target variable: `charges`

## Approach

1. Cleaned and preprocessed the data (encoding categorical variables, scaling numerical features)
2. Trained and compared multiple regression models:
   - Random Forest Regressor
   - Decision Tree Regressor
   - Support Vector Regressor (SVR)
   - XGBoost Regressor
3. Evaluated models using **MAE** and **R² score**

## Results

| Model | R² Score |
|---|---|
| **Random Forest** | **0.8656** |

Random Forest performed best, explaining ~86.6% of the variance in insurance charges, with a Mean Absolute Error (MAE) of ~2539.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib

## Files

- `main.ipynb` — full notebook: data preprocessing, model training, and evaluation
- `data/` — dataset used for training and testing

## Author

Ravi Singh Bungla — [GitHub](https://github.com/ravisingh110705-ml) | [LinkedIn](your-linkedin-url-here)

## Other Projects

- [Titanic Survival Prediction](https://github.com/ravisingh110705-ml/titanic-survival-prediction)
- [Heart Disease Prediction](https://github.com/ravisingh110705-ml/heart-disease-prediction)
- [Telco Customer Churn Prediction](https://github.com/ravisingh110705-ml/telco-churn-prediction)


