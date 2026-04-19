# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project builds an end-to-end machine learning pipeline to predict housing prices based on various features such as area, amenities, and furnishing status.

It demonstrates practical skills in:

* Data preprocessing
* Feature engineering
* Model building
* Hyperparameter tuning
* Model evaluation
* Business interpretation

---

## 📊 Dataset

* Source: Housing dataset (CSV format)
* Features include:

  * Area
  * Bedrooms, bathrooms
  * Amenities (AC, parking, etc.)
  * Furnishing status

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 🚀 Workflow

1. Data Cleaning & Encoding
2. Exploratory Data Analysis
3. Train-Test Split
4. Pipeline Creation
5. Hyperparameter Tuning (GridSearchCV)
6. Model Evaluation
7. Feature Importance Analysis

---

## 📈 Model Performance

* Model: Random Forest Regressor
* Metric: R² Score, Mean Squared Error
* Achieved strong predictive performance after tuning

---

## 🔍 Key Insights

* Area and location-related features strongly influence price
* Amenities like air conditioning and parking significantly impact valuation
* Tree-based models outperform linear models due to non-linear relationships

---

## 💾 Model Output

Trained model is saved as:

```
model/house_price_model.pkl
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Add XGBoost / Gradient Boosting
* Deploy using Flask or Streamlit
* Add cross-validation visualization

---
