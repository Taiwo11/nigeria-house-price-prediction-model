# Nigeria House Price Prediction (ML + Clustering + Streamlit)

This project predicts Nigerian house prices using supervised machine learning models and also segments properties into clusters using K-Means for market grouping.

It includes:
- Linear Regression (baseline)
- Random Forest Regressor (improved accuracy)
- K-Means clustering (housing market segmentation)
- Streamlit deployment (interactive app)

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

