# Assignment 3 – Salary Prediction using Polynomial Regression

## Objective

The objective of this assignment is to develop a Polynomial Regression model to predict employee salaries based on position level. Since the relationship between position level and salary is non-linear, Polynomial Regression is used to model the data more accurately than Linear Regression.

---

## Dataset

**Position Salaries Dataset**

Kaggle Link:

https://www.kaggle.com/datasets/akram24/position-salaries

> Note: The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Methodology

1. Loaded and explored the dataset.
2. Checked for missing values.
3. Selected **Level** as the input feature and **Salary** as the target variable.
4. Split the dataset into 80% training and 20% testing sets.
5. Transformed the input feature using Polynomial Features (Degree = 3).
6. Trained a Polynomial Regression model.
7. Predicted salaries for the test dataset.
8. Evaluated the model using MAE, MSE, and R² Score.
9. Visualized the Polynomial Regression curve.

---

## Results

The Polynomial Regression model successfully learned the non-linear relationship between employee level and salary. The evaluation metrics indicated good predictive performance, and the regression curve closely matched the original data distribution.

---

## Conclusion

Polynomial Regression proved to be more suitable than Linear Regression for this dataset because it effectively captured the non-linear relationship between position level and salary, resulting in more accurate salary predictions.

---

## Repository Structure

```text
Assignment-03/
│
├── notebook/
│   └── Assignment-3.ipynb
│
├── images/
│   └── polynomial_regression_curve.png
│
├── report/
│
├── data/
│
├── README.md
│
└── requirements.txt
```
