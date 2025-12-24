# 💰 Gold Price Prediction using Machine Learning

A machine learning project that predicts gold prices using Random Forest Regression algorithm with data-driven insights and visualizations.

## 🎯 Project Overview

This project analyzes historical gold price data and builds a predictive model to forecast future gold prices based on various economic indicators.

## 📚 Libraries Used

- **NumPy** - Numerical computations
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Scikit-learn** - Machine learning algorithms and metrics
- **KaggleHub** - Dataset download

## 🤖 Algorithm

**Random Forest Regressor** with 100 estimators - An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

## 🔍 Data Preprocessing

1. **Data Loading** - Imported gold price dataset from Kaggle
2. **Data Exploration** - Analyzed shape, info, and statistical summary
3. **Missing Value Check** - Verified data completeness
4. **Feature Engineering** - Removed date column for modeling
5. **Train-Test Split** - 80-20 split with random state for reproducibility

## 📊 Visualizations Performed

- **Correlation Heatmap** - Identified relationships between features and target variable (GLD)
- **Distribution Plot** - Analyzed gold price distribution pattern
- **Actual vs Predicted Plot** - Compared model predictions with actual values

## 📈 Model Performance

- **Metric Used**: R² Score
- Evaluates how well the model explains variance in gold prices
