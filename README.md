# 🏥 Predicting 30-Day Hospital Readmissions with Explainable Machine Learning

This project uses clinical data from the UCI Diabetes 130-US Hospitals dataset to predict whether a patient will be readmitted within 30 days of hospital discharge.

## 📌 Project Highlights
- Built ML models (Logistic Regression & XGBoost)
- Used SHAP for model interpretability
- Compared models using ROC-AUC
- Created business recommendations for hospital use

## 💡 Tools Used
- Python (pandas, scikit-learn, xgboost)
- SHAP for explainable AI
- Matplotlib for visualization
- Jupyter Notebook

## 📈 Results
XGBoost outperformed Logistic Regression and identified key predictors like inpatient visits and insulin usage.

## 🚀 How to Run
1. Clone this repo  
2. Install requirements:  
   `pip install -r requirements.txt`  
3. Run the notebook:  
   `jupyter notebook notebook/readmission_model.ipynb`

## 📂 Folder Structure
hospital-readmission-prediction/ ├── notebook/
│ └── readmission_model.ipynb ├── visuals/ (SHAP/ROC plots) ├── data/ (sample dataset) ├── requirements.txt └── README.md