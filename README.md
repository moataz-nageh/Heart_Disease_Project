# Heart Disease Prediction Project

## 📌 Overview
This project implements a full machine learning pipeline to analyze and predict heart disease using the UCI Heart Disease dataset. It includes preprocessing, feature selection, dimensionality reduction, supervised and unsupervised learning, model evaluation, and hyperparameter tuning.

---

## 📁 Project Structure

```
Heart_Disease_Project/
│
├── data/
│   └── heart_disease.csv
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_pca_analysis.ipynb
│   ├── 03_feature_selection.ipynb
│   ├── 04_supervised_learning.ipynb
│   ├── 05_unsupervised_learning.ipynb
│   └── 06_hyperparameter_tuning.ipynb
│
├── models/
│   └── final_model.pkl
│
├── results/
│   └── evaluation_metrics.txt
│
├── requirements.txt
├── README.md
├── .gitignore
```

---

## ✅ Features

- Data Cleaning and Preprocessing
- Dimensionality Reduction using PCA
- Feature Selection (RFE, Chi-Square, Feature Importance)
- Classification using Logistic Regression, Decision Tree, Random Forest, and SVM
- Clustering using KMeans and Hierarchical Clustering
- Hyperparameter Tuning using GridSearchCV
- Performance Evaluation (Accuracy, F1-Score, AUC)
- Model Saving in `.pkl` format

---

## 💻 How to Run

1. Clone the repository  
   ```
   git clone https://github.com/your-username/Heart_Disease_Project.git
   cd Heart_Disease_Project
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. Install required libraries:
   ```
   pip install -r requirements.txt
   ```

4. Run notebooks step by step in the `notebooks/` folder.

---

## 🔍 Dataset
The dataset used is the UCI Heart Disease Dataset, containing 303 samples and 14 features related to health and heart conditions.

---

## 🤖 Final Model
- Best Model: Logistic Regression
- Accuracy: ~88%
- AUC Score: ~0.94
- Saved as: `models/final_model.pkl`

---

## 📊 Results
- Performance metrics and evaluation scores are saved in the `results/` folder.
- PCA reduced the dataset to 12 components explaining 95% of the variance.

---

## 🚀 Bonus Features (Optional)
- Streamlit App (real-time prediction)
- Ngrok for external app deployment

---

## 📌 Author
Moataz Nageh