# 🚗 TASK - 3: Car Price Prediction using Machine Learning

## 📘 Objective
The goal of this project is to create a machine learning model that can accurately estimate the price of a car based on factors such as brand, year of manufacture, mileage, fuel type, transmission, and other key specifications.

---

## 🧩 Steps Performed

### 1. **Data Loading and Preprocessing**
- Imported essential libraries including `pandas`, `numpy`, and `sklearn`.
- Loaded the dataset and performed initial inspection.
- Identified and handled missing values, duplicates, and unnecessary fields.
- Cleaned and structured the data to prepare it for the modeling phase.

### 2. **Feature Engineering**
- Transformed categorical columns (e.g., brand, transmission, fuel type) into numerical values using **Label Encoding** or **One-Hot Encoding**.
- Scaled numerical attributes with **StandardScaler** for better model stability.
- Treated outliers and adjusted skewed distributions where needed.

### 3. **Model Building**
- Used the **XGBoost Regressor (XGBRegressor)** for effective and reliable car price prediction.
- Built a **Pipeline** to streamline preprocessing and model training.
- Divided the dataset into **training** and **testing** portions with `train_test_split`.

### 4. **Model Evaluation**
- Assessed model performance with metrics such as:
  - **R² Score**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
- Compared predicted values with actual car prices to validate the model’s accuracy.

### 5. **Model Saving**
- Saved the trained model using **Pickle** for reuse.
- Ensured the model can be loaded later without retraining.

---

## ⚙️ Tools & Libraries Used

| Category | Tools/Libraries |
|----------|------------------|
| Data Handling | `pandas`, `numpy` |
| Machine Learning | `xgboost`, `scikit-learn` |
| Evaluation Metrics | `r2_score`, `mean_squared_error`, `math` |
| Model Saving | `pickle` |

---

## 🏁 Outcome
- Developed a reliable **car price prediction system** with strong accuracy.
- Achieved a high **R² score**, showing effective performance.
- Demonstrated a complete ML pipeline—from data cleaning and feature engineering to training, evaluation, and model deployment.

---
