# Nigeria House Price Prediction (ML + Clustering + Streamlit)

> 🚀 This is the advanced rebuild (v2) of my original ML project.  
> 📌 View the original version (v1) here: [Nigerian House Price Prediction – v1](https://github.com/Taiwo11/Nigerian-House-Price-Prediction-Model)


---

## 📘 Project Overview

The Nigerian real estate market is growing rapidly, yet pricing remains inconsistent due to a lack of standardized valuation models.

This project aims to build a machine learning–based predictive model that estimates house prices using historical property listing data from across Nigeria.

### 🎯 Goal

To develop a data-driven pricing system that can help buyers, sellers, and developers make more informed decisions.

---

## 🚀 Key Features

- Predict house prices using Linear Regression and Random Forest
- Compare model outputs
- Segment properties using K-Means clustering
- Deploy interactive prediction interface using Streamlit



---

## Project Structure

```
nigeria-house-price-prediction-model/
│
├── data/
│   ├── raw/                # Original dataset
│   └── processed/          # Cleaned data
│
├── notebooks/              # EDA and experimentation
│   ├── 01_eda.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_clustering.ipynb
│
├── src/                    # Core ML pipeline
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   └── clustering.py
│
├── app/                    # Streamlit deployment
│   └── streamlit_app.py
│
├── models/                 # Saved trained models
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   ├── scaler.pkl
│   └── kmeans.pkl
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Models Used

### ✅ Regression (Price Prediction)
- **Linear Regression**
- **Random Forest Regressor**

### ✅ Unsupervised Learning (Segmentation)
- **K-Means Clustering**
  - Groups properties into similar market segments
  - Helps interpret pricing patterns beyond prediction

---

## Streamlit App Features
- Predict house price from user inputs
- Compare predictions from Linear Regression vs Random Forest
- Show which cluster the property belongs to + cluster insights

---

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Streamlit, Matplotlib

---

## 🖥 Programming Language

- Python 🐍

---

## 📚 Libraries

- **Data Processing & Analysis:**  
  pandas, numpy  

- **Visualization:**  
  matplotlib, seaborn  

- **Machine Learning & Modeling:**  
  scikit-learn  

- **Evaluation Metrics:**  
  sklearn.metrics (MAE, RMSE)  

- **Web Deployment:**  
  Streamlit (for interactive model deployment)

---

## How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Taiwo11/nigeria-house-price-prediction-model.git
cd nigeria-house-price-prediction-model

pip install -r requirements.txt

streamlit run app/streamlit_app.py
```

---
#

## Author
Disu Taiye Mary

