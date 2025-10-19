# 🧠 Machine-Learning-Internal-Project

This repository contains a collection of **machine learning projects** developed for internal research and experimentation.  
Each project explores a unique real-world dataset from **Kaggle Playground Series** and applies **data preprocessing, EDA, model building, and evaluation** using various ML algorithms.

---

## 📂 Projects Overview

### 🏦 1. Loan Approval Prediction
- **Goal:** Predict loan approval status (approved/rejected).  
- **Techniques:** Data cleaning, correlation analysis, and Random Forest classification.  
- **Highlights:**
  - Target mapping for categorical labels (`Y/N/Approved/Rejected`).  
  - Missing value handling and factorization.  
  - K-fold cross-validation with AUC & accuracy metrics.  
  - Feature importance visualization.

### 🧱 2. Steel Plate Defect Prediction
- **Goal:** Detect multiple defect types on steel plates (multi-label classification).  
- **Algorithm:** LightGBM with stratified 5-fold cross-validation.  
- **Highlights:**
  - Multi-output classification for 8 defect types.  
  - Data preprocessing for categorical and numerical features.  
  - Correlation heatmap between targets.  
  - Feature importance analysis across folds.

### 🚗 3. Regression of Used Car Prices
- **Goal:** Predict market prices of used cars based on specifications.  
- **Algorithm:** LightGBM Regression with K-Fold CV.  
- **Highlights:**
  - EDA including target distribution, heatmaps, and categorical analysis.  
  - Label encoding for categorical features.  
  - RMSE-based model evaluation.  
  - Feature importance visualization.

### 🎬 4. TMDB Box Office Prediction
- **Goal:** Predict movie box office revenue using metadata from TMDB.  
- **Algorithm:** LightGBM Regression (log-transformed revenue).  
- **Highlights:**
  - JSON parsing for nested fields (`genres`, `cast`, `crew`, etc.).  
  - Advanced feature engineering (budget, runtime, collection, release date).  
  - Log-transformed regression for stability.  
  - Feature importance and visualization.

---

## 🧩 Tech Stack
- **Languages:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `lightgbm`  
- **Tools:** Kaggle, Jupyter Notebook, Git  

---

## 🧪 Common ML Workflow
1. **Data Loading** – from Kaggle datasets  
2. **Preprocessing** – handle missing values, encode categorical variables  
3. **Exploratory Data Analysis (EDA)** – distributions, correlations, visualizations  
4. **Model Building** – RandomForest / LightGBM  
5. **Cross-Validation** – StratifiedKFold / KFold for model reliability  
6. **Evaluation** – AUC, RMSE, accuracy  
7. **Feature Importance & Visualization**  
8. **Submission Creation** – Save predictions in CSV format  

---

## 📁 Repository Structure
```
Machine-Learning-Internal-Project/
├── loan_approval_prediction/
├── steel_plate_defect_prediction/
├── used_car_price_regression/
├── tmdb_box_office_prediction/
└── README.md
```

---

## 🧑‍💻 Author
Developed by the **Machine Learning Internal Research Team**  
For internal research, analysis, and model experimentation.
