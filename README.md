# 🏡 House Price Prediction using Machine Learning

This project aims to build a regression model to accurately predict the selling price of houses based on various features like area, location, number of rooms, and more. It leverages machine learning techniques to analyze and model historical housing data.

## 📌 Problem Statement

Predict house sale prices based on features such as the number of rooms, overall quality, area, year built, etc. This is a classic supervised learning regression task.

---

## 📂 Dataset

- **Source**: Kaggle - [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Rows**: ~1,460 training examples
- **Columns**: 80+ features (numerical + categorical)

---

## 🧹 Data Preprocessing

- Handled missing values using mean, median, or most frequent imputation
- Converted categorical features using Label Encoding and One-Hot Encoding
- Removed outliers from numerical columns like 'GrLivArea'
- Scaled numerical features using StandardScaler

---

## 📊 Exploratory Data Analysis (EDA)

- Correlation heatmap to identify strongly related features
- Visualized distributions of numerical columns like 'SalePrice', 'LotArea'
- Checked skewness and applied log transformation where necessary

---

## 🧠 Models Used

| Model                  | Notes                       |
|------------------------|-----------------------------|
| Linear Regression      | Baseline model              |
| Ridge Regression       | Regularized linear model    |
| Lasso Regression       | Feature selection           |
| Random Forest Regressor| Ensemble method             |
| XGBoost Regressor      | High-performing boosting    |

---

## 🧪 Model Evaluation

- **Metrics**:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- **Best Model**: XGBoost (highest R² and lowest RMSE)

---

## 📈 Feature Importance

- Top contributing features:
  - OverallQual (Quality of house)
  - GrLivArea (Living area above ground)
  - TotalBsmtSF (Basement square footage)
  - GarageCars (Garage capacity)

---

## ✅ Final Observations

- Feature engineering and handling missing values were critical to model performance.
- Ensemble models like Random Forest and XGBoost significantly outperformed linear models.
- Further improvements could involve hyperparameter tuning and model stacking.

---

## 🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Seaborn, Matplotlib

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sumedhahemadri/House-price-prediction.git
