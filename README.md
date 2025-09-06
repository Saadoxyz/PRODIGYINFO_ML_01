
# 🏡 House Price Prediction (Linear Regression)

## 📌 Project Overview

This project implements a **Linear Regression model** to predict house prices using the [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

We use **3 features**:

* `GrLivArea` → Square footage of living area
* `BedroomAbvGr` → Number of bedrooms
* `FullBath` → Number of bathrooms

The target variable is:

* `SalePrice` → House price

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas → data handling
* Scikit-learn → machine learning (linear regression, train/test split, metrics)
* Matplotlib → data visualization

---

## 🚀 Steps in the Project

1. **Load dataset** (`train.csv`) using Pandas.
2. **Select features and target** (`GrLivArea`, `BedroomAbvGr`, `FullBath` → `SalePrice`).
3. **Split data** into training and testing sets (80/20).
4. **Train Linear Regression model** using scikit-learn.
5. **Make predictions** on the test set.
6. **Evaluate model** using:

   * R² Score
   * RMSE (Root Mean Squared Error)
7. **Visualize results** with a scatter plot (Actual vs Predicted Prices).

---

## 📊 Results

* **R² Score**: Closer to 1 = better performance.
* **RMSE**: Lower values = more accurate predictions.
* Scatter plot shows how close predictions are to actual values.

Example:

```python
R² Score: 0.52
RMSE: 45000
```

(Values may vary depending on features and train/test split.)

---

## 📂 How to Run

1. Clone this repository or download the project.
2. Install dependencies:

   ```bash
   pip install pandas scikit-learn matplotlib jupyter
   ```
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open the notebook file and run the cells step by step.

---

## 🔮 Possible Improvements

* Add more features (e.g., `OverallQual`, `YearBuilt`, `GarageCars`).
* Try advanced models (Random Forest, XGBoost).
* Perform feature engineering and data cleaning for better accuracy.

---

## 🙌 Acknowledgements

* Dataset: [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
* Prodigy Infotech Internship Task

---
