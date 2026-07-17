# 📊 Home Depot Customer Spending Prediction

> **Machine Learning | Predictive Analytics | Business Analytics**

This project develops and compares multiple predictive models to forecast annual customer spending at **The Home Depot**. Four predictive models were evaluated to identify the most accurate forecasting approach and provide actionable business insights for revenue forecasting and marketing strategy.

---

## 🎯 Project Overview

The primary objectives of this project are to:

- Predict annual customer spending (`spend12`)
- Compare the performance of multiple predictive models
- Identify the key drivers of customer spending
- Generate business recommendations based on model results

---

## 🧠 Modeling Pipeline

### Data Preprocessing

- Distribution analysis
- Log transformation
- Feature engineering
- Train/Test Split (70% / 30%)

### Predictive Models

- Linear Regression
- Polynomial Regression
- XGBoost
- Stochastic Gradient Descent (SGD)

### Model Evaluation

- R²
- RMSE
- Feature Importance
- Sensitivity Analysis

---

## 📈 Model Performance

| Model | R² | RMSE |
|-------|----:|----:|
| Linear Regression | 0.977 | 0.055 |
| Polynomial Regression | 0.988 | 0.039 |
| ⭐ XGBoost | **0.996** | **0.024** |
| SGD | 0.346 | 0.295 |

**Best Model:** **XGBoost**

The XGBoost model achieved the highest prediction accuracy while maintaining the lowest prediction error, demonstrating superior capability in modeling nonlinear customer behavior.

---

## 💡 Key Business Insights

- 👥 **Customer age** is the most influential predictor of annual spending.
- 📈 Spending follows an **inverted U-shaped** relationship with age.
- 🎯 Marketing activities positively affect customer spending, but the marginal benefit gradually decreases.
- 🛒 Increasing shopping frequency among low-engagement customers generates the largest increase in spending.

---

## 🛠️ Tech Stack

- **Language:** R
- **Machine Learning:** XGBoost
- **Statistical Modeling:** Linear Regression, Polynomial Regression
- **Visualization:** ggplot2
- **Data Manipulation:** dplyr
- **Documentation:** R Markdown

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Predictive_Analysis_Report.pdf` | Final project report |
| `Predictive_Analysis.Rmd` | R Markdown source code |
| `Predictive_Analysis.R` | Data preprocessing and model development |
| `HomeDepot.xlsx` | Source dataset |

---

## 🚀 Future Improvements

Future enhancements may include:

- Cross-validation
- Hyperparameter tuning
- SHAP model interpretation
- Random Forest / LightGBM comparison
- Interactive dashboard (Streamlit or Power BI)

---

## 👤 About the Author

**Wenting Luo**

M.S. Business Analytics

**Areas of Interest**

- Predictive Analytics
- Machine Learning
- Operations Research
- Supply Chain Analytics
- Decision Science

---
⭐ If you found this project helpful, feel free to explore the repository!
