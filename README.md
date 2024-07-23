# Sales Prediction Project

This project involves predicting sales using various regression models. The models used in this project include Linear Regression, Decision Tree, Random Forest, and XGBoost. The performance of these models is evaluated based on Mean Squared Error (MSE) and R² Score on both training and testing datasets.

## Project Overview

The aim of this project is to compare the performance of different regression models in predicting sales. The models are evaluated based on their accuracy and ability to generalize to unseen data.

## Models Used

1. **Linear Regression**
2. **Decision Tree**
3. **Random Forest**
4. **XGBoost**

## Evaluation Metrics

- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors. It is the average squared difference between the estimated values and the actual value.
- **R² Score**: Represents the proportion of the variance for the dependent variable that's explained by the independent variables in the model.

## Results

| Model              | Training MSE | Testing MSE | Training R² Score | Testing R² Score |
|--------------------|--------------|-------------|--------------------|------------------|
| Linear Regression  | 2.705129     | 3.174097    | 0.895701           | 0.899438         |
| Decision Tree      | 0.000000     | 2.175000    | 1.000000           | 0.931091         |
| Random Forest      | 0.094742     | 0.590732    | 0.996347           | 0.981284         |
| XGBoost            | 0.000003     | 0.868933    | 1.000000           | 0.972470         |



## Conclusion

The Random Forest model achieved the lowest Testing MSE and highest Testing R² Score, indicating it performed the best in predicting sales. The Decision Tree and XGBoost models also performed well, while the Linear Regression model had the highest Testing MSE and lowest Testing R² Score.


