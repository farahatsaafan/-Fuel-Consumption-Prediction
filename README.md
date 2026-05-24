# 🚗 Fuel Consumption Prediction

A machine learning project that predicts vehicle fuel efficiency (MPG)
using Polynomial Linear Regression with full data preprocessing pipeline.

## 📌 Project Overview
Built and improved a regression model that predicts miles-per-gallon (MPG)
for vehicles based on engine and design features.
Achieved R² improvement from 79.42% → improved score through
feature engineering and outlier removal.

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn (LinearRegression, PolynomialFeatures, StandardScaler)
- Matplotlib & Seaborn
- Google Colab

## ⚙️ What I Did
- Performed Exploratory Data Analysis (EDA) on the MPG dataset
- Cleaned data: removed null values and outliers using IQR method
- Applied Feature Scaling using StandardScaler
- Applied Polynomial Features (degree=2) to capture non-linear patterns
- Evaluated model using MAE, RMSE, and R² metrics
- Visualized results: correlation heatmap + actual vs predicted plot

## 📊 Results

| Model | R² Score |
|-------|----------|
| Basic Linear Regression | 79.42% |
| Improved (Poly + Scaling) | Higher ✅ |

## 🚀 How to Run
1. Open `fuel_consumption_improved.py` in Google Colab
2. Run all cells in order
3. View evaluation results and plots
