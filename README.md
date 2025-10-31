# 🏠 California Housing Price Prediction

## Overview
This project predicts the **median house value** in California using the California Housing dataset from Scikit-Learn.  
It demonstrates an **End-To-End Regression Workflow**, including data exploration, preprocessing, model training, evaluation, and interpretation.

Key steps include:  
- Exploratory Data Analysis (EDA)  
- Multicollinearity check with **VIF**  
- Feature standardization  
- **Linear Regression**, **Ridge**, and **Lasso** models  
- Model evaluation (RMSE, R²) and comparison  
- Insights from feature selection (Lasso dropping less important features)

---

## Dataset
Dataset provided by Scikit-Learn:  
[California Housing Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)

> **Note:** Dataset is not included in the repo; it can be loaded directly from Scikit-Learn.

---

## 🛠️ Tools & Techniques Used

**Programming & ML:**  
- Python 3.12  
- Jupyter Notebook (Interactive analysis)  
- Scikit-learn (Linear Regression, Ridge, Lasso, train/test split, StandardScaler, GridSearchCV)  
- Statsmodels (OLS regression, VIF analysis)

**Data Handling:**  
- Pandas, NumPy  

**Visualization:**  
- Matplotlib, Seaborn  

**Modeling Techniques:**  
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Feature Scaling & Standardization  

**Validation & Evaluation:**  
- Cross-validation (5-fold)  
- RMSE, R², coefficient analysis  
- Predicted vs Actual plots

**Key Findings:**  
- Lasso dropped the `Population` feature, simplifying the model  
- Ridge and Lasso improved generalization compared to OLS  
- Predicted vs actual scatter plots show good alignment with test data  

---

## 📬 Contact  
Created by FELLAH HANANE

📧 Email: hananefellah35@gmail.com

🌐 GitHub: hananefellah

## 📄 License  
MIT License  

---

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/California_Housing_Regression.git
cd California_Housing_Regression
pip install -r requirements.txt
