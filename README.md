# Mainflow-Internship-task-4
# Regression Analysis - House Price Prediction

## Project Overview
This project focuses on **building a regression model** to predict house prices based on various features using **Linear Regression**. The dataset contains information such as **Size, Location, and Number of Rooms**, which influence house prices.

## Dataset Information
- **Dataset Name:** `house_prices.csv`
- **Key Features:**
  - `Size`: Numeric (e.g., square feet)
  - `Location`: Categorical (e.g., urban, suburban, rural)
  - `Number of Rooms`: Numeric
  - `Price`: Numeric (Target variable)

## steps to Complete the Project

### 1️⃣ Load and Explore
- Load the dataset.
- Check for missing values and handle them.
- Analyze distributions of numerical variables.
- Identify and remove potential outliers.

### 2️⃣ Data Preprocessing
- **Normalize Numerical Data:** Apply **Min-Max Scaling** or **Standardization** for features like `Size` and `Number of Rooms`.
- **Encode Categorical Features:** Convert `Location` into numerical values using:
  - **One-Hot Encoding** (for non-ordinal categories).
  - **Label Encoding** (if applicable for ordinal categories).

### 3️⃣ Feature Selection
- Perform **correlation analysis** to determine the relationship between features and `Price`.
- Remove low-impact predictors to improve model performance.

### 4️⃣ Model Training
- Split the dataset into **training (80%) and testing (20%)**.
- Train a **Linear Regression Model** using **Scikit-Learn**.

### 5️⃣ Model Evaluation
- Evaluate model performance using:
  - **Root Mean Squared Error (RMSE)**
  - **R² Score (Coefficient of Determination)**
- Analyze model coefficients to understand feature impact.

## Deliverables
- A trained **Linear Regression model** capable of predicting house prices.
- **Predicted vs Actual** price comparisons.
- **Evaluation metrics** (RMSE, R²).
- Summary of **most important predictors** influencing house prices.

## Expected Insights
- The correlation between `Size`, `Number of Rooms`, and `Price`.
- The effect of `Location` on pricing.
- Model accuracy and reliability for real-world price predictions.

