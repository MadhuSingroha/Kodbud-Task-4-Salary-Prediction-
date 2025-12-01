# Salary Prediction Model

## Project Overview

This project focuses on predicting employee salaries using a **Linear Regression model** based on factors like **Age, Gender, Education Level, Job Title, and Years of Experience**. The model was trained and evaluated using Mean Squared Error (MSE) to ensure accuracy.

## Dataset

The dataset consists of the following columns:

* **Age**: Age of the employee (numeric)
* **Gender**: Gender of the employee (categorical)
* **Education Level**: Highest education level attained (categorical)
* **Job Title**: Role of the employee (categorical)
* **Years of Experience**: Experience in years (numeric)
* **Salary**: Target variable - annual salary of the employee (numeric)

> The dataset can be downloaded from Kaggle: [Salary Prediction Dataset](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer)

## Key Steps

1. **Data Preprocessing**

   * Handled categorical variables using **OneHotEncoder**
   * Numerical variables were left as-is (or scaled if needed)

2. **Train-Test Split**

   * Dataset split into training and testing sets using `train_test_split`

3. **Model Training**

   * Linear Regression model trained on the training set

4. **Evaluation**

   * Model evaluated using **Mean Squared Error (MSE)**
   * Additional metrics: MAE, RMSE, R² score

## Libraries Used

* `pandas`
* `numpy`
* `scikit-learn`

  * `LinearRegression`
  * `train_test_split`
  * `OneHotEncoder`
  * `ColumnTransformer`
  * `mean_squared_error`, `r2_score`

## How to Run

1. Clone the repository or download the files.
2. Ensure the dataset CSV file is available in the working directory.
3. Run the Python notebook or script.
4. Check evaluation metrics and predictions.

## Links

* **Dataset CSV**: [Kaggle](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer)
* **Jupyter Notebook**: [GitHub Notebook](https://github.com/MadhuSingroha/Kodbud-Task-4-Salary-Prediction-/blob/main/Kodbud%20Task%204%28Salary%20Prediction%29.ipynb)
* **Power BI Dashboard**: [GitHub PBIX](https://github.com/MadhuSingroha/Kodbud-Task-4-Salary-Prediction-/blob/main/Kodbud%20Task%204%28Salary%20Predictions%29.pbix)

## Author

**Madhu Singroha**
Email: [madhu.singroha@gmail.com](mailto:madhu.singroha@gmail.com)
LinkedIn: [linkedin.com/in/madhu-singroha-67b50a369](https://linkedin.com/in/madhu-singroha-67b50a369)

## Hashtags

#Kodbud #Kodbud #DataScience #MachineLearning #Python #SalaryPrediction #LinearRegression #Analytics
