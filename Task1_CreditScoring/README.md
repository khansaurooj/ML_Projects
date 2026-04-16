# 💳 Credit Score Classification — 
  
The goal is to build and compare machine learning models for **Credit Score Classification** using a real-world financial dataset.  

---

## 📁 Project Overview

The objective of this task is to **predict a customer’s credit score** (Good, Standard, Poor) based on various financial and behavioral features such as income, loan details, delayed payments, and more.  
The project involves **data cleaning, preprocessing, model training, and performance evaluation** using multiple classifiers.

---

## 🧠 Objectives

- Preprocess and clean messy real-world data (handle missing values, text-to-numeric conversion, etc.)
- Apply feature encoding and scaling
- Train and compare ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC
- Visualize results for model comparison

---

## 🧩 Dataset

**Source:** https://drive.google.com/file/d/1mQ2FZiUxXquaxnV_sRwaJU8JRG8Sn7ng/view?usp=sharing
**File:** `Credit_Score_Classification.zip` → contains `train.csv`

**Key Features:**
- `Annual_Income`, `Outstanding_Debt`, `Num_Bank_Accounts`, `Credit_Utilization_Ratio`, etc.
- **Target Column:** `Credit_Score` (`Good`, `Standard`, `Poor`)

---

## ⚙️ Steps Performed

### 🪜 Step 1: Import Required Libraries
Imported essential Python libraries such as Pandas, NumPy, Scikit-learn, Seaborn, and Matplotlib.

### 📂 Step 2: Load Dataset
Mounted Google Drive and extracted the dataset ZIP file, then loaded `train.csv`.

### 🔍 Step 3: Exploratory Data Analysis (EDA)
- Checked dataset shape, column info, and missing values.
- Analyzed data types and feature distribution.

### 🧹 Step 4: Data Cleaning & Conversion
- Removed unnecessary columns (`ID`, `Customer_ID`, `Name`, etc.)
- Replaced invalid values (`_`, `NA`, `nan`, etc.) with proper `NaN`.
- Converted all numeric-looking columns to numeric.
- Converted `Credit_History_Age` (e.g., “22 Years and 3 Months”) to total months.
- Filled missing numeric values with median and categorical values with mode.
- Encoded categorical columns using `LabelEncoder`.

### 🧪 Step 5–6: Split Data & Scale Features
- Split into **80% training** and **20% testing** sets.
- Standardized features using `StandardScaler`.

### 🤖 Step 7: Train Models
Trained and evaluated:
- Logistic Regression
- Decision Tree
- Random Forest

### 📈 Step 8: Model Evaluation
Calculated:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- Compared models using bar charts

### 📊 Step 9: ROC-AUC & Best Model
- Computed ROC-AUC for each model.
- Plotted ROC curves for all classes.
- ✅ **Best Model:** `Random Forest` with **AUC = 0.91**

---

## 🧾 Results Summary

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---------------------|-----------|------------|---------|-----------|----------|
| Logistic Regression | 0.6123    | 0.6100     | 0.6123  | 0.5989    | 0.7734   |
| Decision Tree       | 0.6857    | 0.6864     | 0.6857  | 0.6860    | 0.7438   |
| 🏆 Random Forest     | **0.7879** | **0.7877** | **0.7879** | **0.7878** | **0.9102** |

---

## 📊 Visualizations

- Model performance comparison (bar chart)
- ROC Curve for the best model (Random Forest)

---

## 🧰 Technologies Used

- **Python 3.10+**
- **Google Colab**
- **NumPy / Pandas / Matplotlib / Seaborn**
- **Scikit-learn**

---

## 🏁 Conclusion

- Proper data preprocessing and encoding were essential due to mixed and missing values.
- Random Forest outperformed all other models with **~79% accuracy** and **AUC of 0.91**.
- The model is effective for predicting credit scores and can be further optimized using feature selection and hyperparameter tuning.

---

## 📜 Author

**👩‍💻 Khansa Urooj**  

🔗 [GitHub Repository]

---

## 🧩 Next Steps (Future Work)

- Apply hyperparameter tuning (GridSearchCV)
- Implement feature importance visualization
- Try advanced models (XGBoost, LightGBM)
- Deploy the best model using Streamlit or Flask

---

### 📅 Completed: October 2025

