# Linear Regression: Salary Prediction

## Project Overview

This project demonstrates the implementation of **Linear Regression**, a supervised machine learning algorithm, to predict salary based on years of work experience.

The objective is to understand how a regression model learns the relationship between an independent variable and a continuous target variable, makes predictions, and evaluates its performance.

## Problem Statement

Can we predict an individual's salary based on their years of work experience?

This project uses a simple sample dataset to build a Linear Regression model and explore how experience relates to salary.

## Objectives

- Understand the working of Linear Regression.
- Prepare features and target variables.
- Split data into training and testing sets.
- Train a Linear Regression model.
- Predict salary using years of experience.
- Evaluate model performance using regression metrics.
- Visualize the regression line and analyze residuals.

## Technologies & Libraries

- **Python** – Programming language
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine learning model and evaluation

## Dataset Description

The project uses a small sample dataset containing 10 observations.

| Variable | Description |
|---|---|
| Experience | Years of work experience |
| Salary | Corresponding salary value |

**Note:** This is a sample dataset created for learning and demonstration purposes. It does not represent real-world salary records.

## Project Workflow

1. **Data Preparation** – Import libraries and create the sample dataset.
2. **Feature and Target Selection** – Select Experience as the independent variable (X) and Salary as the dependent variable (y).
3. **Train-Test Split** – Split the dataset into 80% training data and 20% testing data.
4. **Model Training** – Build and train the Linear Regression model.
5. **Prediction** – Predict salary values using the test data.
6. **Model Evaluation** – Evaluate predictions using MAE, MSE, RMSE, and R² Score.
7. **Visualization** – Plot the regression line and analyze residuals.

## Model Evaluation Metrics

The following metrics are used to evaluate the model:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error):** Represents prediction error in the target variable's units.
- **R² Score:** Measures how much variation in the target variable is explained by the model.

## Visualizations

The notebook includes:

- **Regression Line Plot:** Shows the training and testing observations along with the fitted regression line.
- **Residual Plot:** Displays the residuals against the model's training predictions to help inspect prediction errors.

## How to Run This Project

1. Clone this repository:

   ```bash
   git clone https://github.com/riakatkar/linear-regression-salary-prediction.git
   ```

2. Navigate to the project folder:

   ```bash
   cd linear-regression-salary-prediction
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `linear_regression_with_markdowns.ipynb` and run the cells.

## Project Limitations

- The dataset contains only 10 observations.
- The model uses only one independent variable: years of experience.
- The small test set is not sufficient for reliable evaluation of real-world performance.
- Real-world salary prediction would require a larger dataset and additional features such as education, job role, location, and industry.

## Medium Article

I have also written a detailed article explaining the concepts, mathematics, and practical implementation of Linear Regression.

**Read the full article:**

[Linear Regression: The Algorithm That Taught Me How Machines Learn to Predict](https://medium.com/@riakatkar/linear-regression-the-algorithm-that-taught-me-how-machines-learn-to-predict-406cefcd518c)

## Key Learning

Through this project, I gained practical experience with the complete Linear Regression workflow, from preparing data and training a model to evaluating predictions and interpreting visualizations.

---

**Author:** Ria Katkar

**Tools:** Python | Pandas | NumPy | Matplotlib | Scikit-learn
