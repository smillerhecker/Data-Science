# House Price Prediction using XGBoost

## 📌 Project Overview

This project builds a **house price prediction model** using **XGBoost**, a powerful gradient boosting algorithm. The goal is to predict house prices based on features like bedrooms, bathrooms, square footage, and location.

The model was trained on a Kaggle **House Pricing Dataset** and achieved a **Mean Absolute Error (MAE) of 69,384**, showing a significant improvement over simpler models like Linear Regression.

---

## 📊 Dataset Description

The dataset contains information about houses, including:

- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `sqft_living`: Square footage of the house
- `floors`: Number of floors
- `view`: How good the house’s view is
- `grade`: Overall grade of the house
- `sqft_above`: Square footage of the house (excluding basement)
- `lat`: Latitude (location)
- `long`: Longitude (location)
- `price`: **Target variable (house price in USD)**

---

## 🛠 Model & Techniques Used

- **Feature Selection**: Removed unnecessary features to improve accuracy
- **Train-Test Split**: 80% training, 20% testing
- **Model Used**: `XGBRegressor` with **1000 estimators & learning rate 0.05**
- **Early Stopping**: Prevents overfitting by stopping training when no further improvement is observed
- **Evaluation Metric**: Mean Absolute Error (MAE) → Lower is better

---

## ⚡ Results & Improvements

| Model               | Mean Absolute Error (MAE) |
| ------------------- | ------------------------- |
| Linear Regression   | 328,699.56                |
| XGBoost (Optimized) | **69,384.65**             |

- **XGBoost reduced the error by over 78% compared to Linear Regression!** 🚀
- Feature selection & early stopping played a key role in improving performance.

---

## 💻 How to Run the Code

1. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn xgboost
   ```
2. Clone this repository:
   ```bash
   git clone https://github.com/yourgithubusername/house-price-prediction.git
   cd house-price-prediction
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook House_Price_Prediction.ipynb
   ```

---

## 📢 Next Steps

- **Hyperparameter Tuning**: Further optimization using GridSearchCV
- **Feature Engineering**: Adding polynomial features or log transformations
- **Try Other Models**: Compare with Random Forest or Neural Networks

✅ If you find this project useful, give it a ⭐ on GitHub!

---

**Author:** *Your Name*\
**GitHub:** [Your GitHub Profile](https://github.com/yourgithubusername/)

