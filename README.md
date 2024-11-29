# Covid-Vaccination-Prediction

## Description

This project focuses on predicting COVID-19 vaccination trends using various machine learning models. The goal is to compare the performance of different regression algorithms in terms of metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.

The dataset includes features related to vaccination statistics, population data, and other relevant factors influencing vaccination rates. After preprocessing and feature engineering, multiple regression models were trained and evaluated to determine the most accurate predictor.

## Workflow

1. **Data Collection**: Dataset sourced and cleaned for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualized trends and relationships in the data.
3. **Feature Engineering**: Selected and engineered relevant features for training.
4. **Model Training**: Trained various regression models including:
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
   - Random Forest
   - Gradient Boosting
   - XGBoost
5. **Model Evaluation**: Evaluated models using metrics such as MSE, MAE, and R² Score.
6. **Result Comparison**: Compared all models to select the best-performing one.

## Libraries and Dependencies

The following Python libraries are used in this project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

Ensure these are installed before running the notebook.

## Results

The table below summarizes the performance of each model:


| Model               | MSE               | MAE           | R² Score |
|---------------------|-------------------|---------------|----------|
| Linear Regression   | 13358769626832.57| 1407242.14    | 0.995359 |
| Ridge Regression    | 13356997792359.79| 1407276.99    | 0.995360 |
| Lasso Regression    | 13358770320790.74| 1407241.96    | 0.995359 |
| Random Forest       | 802201173937.08  | 113959.26     | 0.999721 |
| Gradient Boosting   | 1518675912606.44 | 361593.08     | 0.999472 |
| XGBoost             | 1446282674930.85 | 186126.44     | 0.999498 |


From the comparison, **Random Forest** achieved the best results with the lowest MAE and the highest R² Score, making it the most accurate model for predicting vaccination trends.

## How to Use

1. Clone this repository to your local machine.
2. Install the required libraries listed above.
3. Open the `Covid-Vaccination-Prediction.ipynb` notebook.
4. Follow the steps in the notebook to reproduce the analysis and results.

## Conclusion

This project demonstrates the effectiveness of machine learning models in predicting COVID-19 vaccination trends. By leveraging Random Forest regression, we achieved highly accurate predictions, which can aid policymakers and health organizations in planning vaccination campaigns.
