# 🩺 Disease Prediction from Medical Data — CodeAlpha Machine Learning Internship (Task 4)

This repository contains the solution for **Task 4** of the CodeAlpha Machine Learning Internship: **Disease Prediction from Medical Data (Heart Disease)**.  
The objective is to build a machine learning model that predicts the presence of heart disease using clinical data.

---

## 📁 Project Overview

This project focuses on **predicting heart disease** from medical datasets using data science and machine learning techniques. The workflow includes:

- **Data Loading & Exploration:** Understanding and visualizing medical features
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature scaling
- **Model Development:** Implementing multiple algorithms for disease prediction
- **Evaluation:** Comparing models using accuracy, confusion matrix, and classification reports
- **Visualization:** Displaying feature distributions and model performance

---

## 🧠 Objectives

- Load and explore the Heart Disease dataset
- Perform data cleaning and preprocessing (handling nulls, encoding, scaling)
- Build and compare multiple classification models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Evaluate model performance using:
  - Accuracy scores
  - Confusion matrix
  - Classification report (Precision, Recall, F1-score)
- Visualize results and feature importance

---

## 🧩 Dataset

**Dataset:** Heart Disease UCI  
**Source:** [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

**Features Typically Include:**  
- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol  
- Fasting blood sugar  
- Resting ECG results  
- Max heart rate achieved  
- Exercise-induced angina  
- ST depression  
- Slope of peak exercise ST segment  
- Number of major vessels  
- Thalassemia  
- Target (1 = disease present, 0 = not present)

---

## ⚙️ Steps Performed

### 1. Import Required Libraries
- Installed: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`
- Used: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

### 2. Data Loading & Exploration
- Loaded CSV data
- Explored feature distributions and checked for missing values

### 3. Data Preprocessing
- Handled missing values
- Performed label encoding and feature scaling
- Split data into training and test sets

### 4. Model Building & Training
- Implemented Logistic Regression, Random Forest, SVM, and KNN classifiers
- Trained models and compared results

### 5. Model Evaluation & Visualization
- Plotted confusion matrices
- Generated classification reports
- Visualized feature importance

---

## 📊 Visualizations

- **Feature Distributions:** Histograms and boxplots for medical features
- **Correlation Matrix:** Heatmap of feature relationships
- **Confusion Matrix:** Model prediction breakdown
- **Classification Report:** Precision, Recall, F1-score for each class
- **Feature Importance:** Which factors most influence prediction

---

## 🧰 Technologies Used

- **Python 3.10+**
- **Google Colab / Jupyter Notebook**
- **NumPy / Pandas / Matplotlib / Seaborn**
- **Scikit-learn**

---

## 👩‍💻 Author

**Khansa Urooj**  
CodeAlpha — Machine Learning Internship (Task 4: Disease Prediction from Medical Data)  
🔗 [GitHub Repository](https://github.com/khansaurooj/CodeAlpha_ML_Internship)

---

## 🚀 Future Work

- Integrate additional clinical datasets for broader disease prediction
- Apply hyperparameter tuning and cross-validation for model optimization
- Deploy as a web application for real-time disease risk assessment
- Incorporate advanced models (e.g., XGBoost, LightGBM, Neural Networks)
- Explore explainable AI (XAI) to interpret predictions

---

> For feedback, questions, or contributions, please open an issue or contact the author via GitHub.
