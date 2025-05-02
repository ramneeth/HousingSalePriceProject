# 🏡 Housing Sale Price Prediction

This project applies data preprocessing and machine learning techniques to predict the sale prices of residential homes using the popular [Ames Housing dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## Project Goals

- Explore and clean a real-world housing dataset.
- Engineer meaningful features for modeling.
- Train and evaluate multiple regression models.
- Compare performance using RMSE and R².

---

## Technologies Used

- **Python**
- **Pandas**, **NumPy** – data wrangling
- **Matplotlib**, **Seaborn** – data visualization
- **Scikit-learn** – modeling and evaluation

---

## Workflow Summary

1. **Data Cleaning**
   - Handled missing values appropriately (e.g. `GarageType`, `Alley`, etc.).
   - Converted categorical variables using one-hot encoding.

2. **Exploratory Data Analysis**
   - Visualized distributions, correlations, and outliers.
   - Identified important features like `OverallQual`, `GrLivArea`, and `GarageCars`.

3. **Feature Engineering**
   - Combined and transformed variables (e.g., total square footage).
   - Dropped irrelevant or redundant features.

4. **Modeling**
   - Trained models including:
     - Linear Regression
     - Ridge & Lasso Regression
   - Used cross-validation and GridSearch to tune hyperparameters and estimate performance.

5. **Evaluation**
   - Compared models using:
     - Root Mean Squared Error (RMSE)
     - R² score
