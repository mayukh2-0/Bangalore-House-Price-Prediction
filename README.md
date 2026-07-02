# 🏡 Bangalore House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Regression-green)
![LightGBM](https://img.shields.io/badge/LightGBM-Ensemble-success)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient%20Boosting-yellow)
![License](https://img.shields.io/badge/License-MIT-red)

---

# 📌 Project Overview

This project develops an end-to-end Machine Learning pipeline to predict residential property prices in Bangalore using advanced regression models and ensemble learning techniques.

The workflow includes data preprocessing, feature engineering, outlier removal, hyperparameter optimization, model explainability using SHAP, and a Stacking Ensemble to achieve high prediction accuracy.

---

# 🎯 Objectives

- Predict house prices in Bangalore
- Perform complete data preprocessing
- Engineer meaningful features
- Compare multiple ML algorithms
- Optimize models using Optuna
- Interpret predictions using SHAP
- Build an accurate ensemble model

---

# 📂 Dataset Information

Dataset Name:

**Bengaluru House Data**

Number of Records

- 13,320

Number of Features

- 9

Target Variable

- Price (Lakhs INR)

Original Features

- Area Type
- Availability
- Location
- Size
- Society
- Total Square Feet
- Bathrooms
- Balconies
- Price

---

# 📊 Data Preprocessing

The following preprocessing steps were performed:

- Missing Value Handling
- Data Cleaning
- Total Square Feet Conversion
- BHK Extraction
- Location Encoding
- Outlier Removal
- Feature Scaling
- One-Hot Encoding

---

# ⚙️ Feature Engineering

New engineered features include:

- BHK
- Price per Square Foot
- Bath per BHK
- Square Feet per BHK
- Society Availability
- Location Frequency Encoding

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated.

- Random Forest Regressor
- XGBoost Regressor
- LightGBM
- CatBoost Regressor
- Optuna Tuned LightGBM
- Stacking Ensemble

---

# 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| **Stacking Ensemble** | **24.07** | **53.23** | **0.7947** |
| Random Forest | 23.75 | 54.12 | 0.7878 |
| CatBoost | 25.15 | 54.95 | 0.7812 |
| XGBoost | 23.85 | 58.32 | 0.7535 |
| LightGBM (Optuna) | 26.01 | 60.71 | 0.7329 |
| LightGBM | 26.36 | 60.99 | 0.7305 |

---

# 🏆 Best Performing Model

**Stacking Ensemble**

Performance

- MAE : 24.07
- RMSE : 53.23
- R² Score : 0.7947

---

# 📌 Sample Predictions

| Location | Configuration | Predicted Price |
|-----------|---------------|----------------|
| Whitefield | 2 BHK • 1200 sqft | ₹52.97 Lakhs |
| Koramangala | 4 BHK • 2500 sqft | ₹324.25 Lakhs |
| Electronic City | 1 BHK • 600 sqft | ₹33.59 Lakhs |
| Jayanagar | 5 BHK • 3500 sqft | ₹357.90 Lakhs |

---

# 📊 Visualizations

The project automatically generates

- Model Comparison Chart
- SHAP Feature Importance Plot
- Predicted vs Actual Plot
- Residual Distribution

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- Optuna
- SHAP

---

# 📁 Repository Structure

```
Bangalore-House-Price-Prediction
│
├── Bangalore_house_price_prediction.ipynb
├── Bengaluru_House_Data.csv
├── model comparison.png
├── SHAP feature importance.png
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/mayukh2-0/Bangalore-House-Price-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```
Bangalore_house_price_prediction.ipynb
```

Run all cells.

---

# 📌 Future Improvements

- Deploy using Streamlit
- Build REST API using FastAPI
- Docker Container
- Model Versioning
- CI/CD Pipeline
- Cloud Deployment

---

# 👨‍💻 Author

**Mayukh Mondal**

Indian Institute of Technology Kharagpur

Civil Engineering

Machine Learning • Data Science • Artificial Intelligence

---

⭐ If you found this project useful, consider giving this repository a star.
