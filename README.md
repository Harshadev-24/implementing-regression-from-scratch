# Linear Regression from Scratch: Salary Prediction

This project implements **Simple Linear Regression** from scratch using only Python and core libraries (NumPy, pandas, Matplotlib), focusing on the relationship between years of experience and salary. This is a classic supervised machine learning problem, allowing you to understand the math and core logic behind regression models without using high-level ML libraries.

## 📁 Dataset

- **Source**: Kaggle [Salary Data Dataset](https://www.kaggle.com/datasets/shubham47/salary-data-dataset-for-linear-regression)
- **Features**:
  - `YearsExperience` (float): Number of years of experience of each individual.
  - `Salary` (float): Corresponding salary.

## 🛠️ What’s Inside

- **Data loading and preprocessing:**  
  - Reads data as pandas DataFrame and converts relevant columns to NumPy arrays.
  - Standardizes/normalizes data for stability during learning.

- **Exploratory Data Analysis:**
  - Initial scatter plot to visualize the linear relationship between years of experience and salary.
  - Data normalization and verification of linearity.

- **Regression Modeling:**
  - Implements a `SimpleLR` class with:
    - Custom initialization (learning rate, max iterations, threshold)
    - Methods for prediction, fitting (gradient descent), and plotting results.
  - Implements batch gradient descent for learning the best fit.

- **Loss Function:**
  - Uses Mean Squared Error (MSE) to measure model performance and monitor optimization.

- **Model Training:**
  - Model fits to the normalized data, updates weights and bias, and records loss per iteration.
  - Includes an early stopping condition based on a threshold for loss change.

- **Visualization:**
  - Plots the original data and the learned regression line.
  - Plots loss history per iteration to visualize convergence.

- **Result:**
  - Demonstrates the regression model's fit and ability to predict salary from years of experience.

## 📊 Outputs

- **Best-fit line** overlayed on the scatter plot of the dataset.
- **Loss curve** showing convergence of the optimization algorithm (should decrease and stabilize).

## 🚀 Usage

To run this project:
1. **Clone the repo** and ensure you have Python (3.x) and the necessary libraries:
2. **Place the CSV dataset** in the expected path or update the notebook path as required.
3. **Open the notebook** and execute cells step by step to see outputs and plots.

## 🧠 Key Learnings

- Hands-on understanding of **linear regression math**: mean, variance, normalization, gradient descent.
- Practical workflow of building, tuning, and validating a regression model without external ML libraries.
- Visualization techniques in data science, including result and loss diagnostics.

## 💡 Possible Extensions

- Try using multiple features (multivariate regression).
- Experiment with stochastic or mini-batch gradient descent variants.
- Compare results with scikit-learn's built-in regression.


