# 🍹 **Energy Drink Price Range Prediction**

This repository contains a machine learning project aimed at predicting the price range for energy drinks. Developed for the **CodeX** company, this project leverages advanced machine learning techniques, feature engineering, and MLflow for tracking experiments to deliver accurate and insightful predictions.


---

## Motivation

Pricing energy drinks effectively is crucial for profitability and market competitiveness. This project provides a data-driven approach to understanding pricing patterns in the food and beverage domain by:

- Identifying critical factors influencing price.
- Creating new features to enhance model performance.
- Leveraging a scalable solution for real-world deployment.

---

## Goals

1. **Build a robust machine learning model** for predicting energy drink price ranges.
2. **Engineer new features** to improve model accuracy and interpretability.
3. **Implement MLflow** for experiment tracking and reproducibility.
4. **Provide a user-friendly pipeline** for data processing, training, and prediction.

---
## Technical Details

### Tools and Libraries

- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Scikit-learn**: Model building and evaluation.
- **MLflow**: Experiment tracking and logging.
- **Seaborn & Matplotlib**: Visualization for EDA.
- **Joblib**: Model serialization for deployment.



### Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting Machines (e.g., XGBoost)
- LightGBM

**Final Model Selection**: Xg boost achieved the best performance in terms of accuracy and interpretability.

 ** For Feature Engineering**:
   - Created new features (`ingredient_density`, `price_per_ml`, `premium_score`) to enhance predictions

---

## MLflow Integration

This project uses **MLflow**   
Link :  https://dagshub.com/NDN-Surya/Price-Prediction.mlflow

![Code-X Food & Beverage Price Prediction UI](New%20folder/Screenshot%20(101).png)
