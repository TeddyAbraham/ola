# OLA – Employee Attrition Prediction using Ensemble Learning 🚖📊

## 📌 Project Overview
This project focuses on predicting driver attrition for **OLA** using machine learning.  
The analysis involves extensive **feature engineering, imputation, and ensemble learning methods** (Bagging & Boosting) to model driver behavior, improve retention strategies, and provide actionable business recommendations.  

## 🛠️ Workflow & Methodology

### 🔍 Data Exploration & Preprocessing
- Imported dataset and performed EDA (checked structure, distribution, characteristics)  
- Converted **date-like features** into proper datetime format  
- Checked for missing values and applied **KNN Imputation** (numerical features)  
- Aggregated data to remove duplicate driver records by grouping on **Driver ID**  

### 🏗️ Feature Engineering
- Created a column to indicate **quarterly rating improvement** (1 if increased, 0 otherwise)  
- Defined **target variable**: Driver attrition (1 if last working day present, else 0)  
- Created a column to indicate **monthly income increase** (1 if increased, 0 otherwise)  
- Generated statistical summary of derived dataset  

### 📊 Data Preparation
- Checked correlations among independent variables  
- Applied **One-Hot Encoding** for categorical variables  
- Handled **class imbalance** using resampling/SMOTE  
- Standardized training data for model readiness  

### 🤖 Modeling – Ensemble Learning
- Implemented **Bagging methods** (Random Forest, Extra Trees)  
- Implemented **Boosting methods** (XGBoost, AdaBoost, Gradient Boosting)  
- Performed **hyperparameter tuning** for model optimization  

### 📈 Evaluation Metrics
- **Classification Report** (Precision, Recall, F1-score, Accuracy)  
- **ROC-AUC Curve** for model performance comparison  
- Compared results across ensemble models  

### 💡 Insights & Recommendations
- Identified key factors influencing driver attrition  
- Suggested retention strategies based on predictive features  
- Provided business recommendations for driver satisfaction & reduced turnover  

## ⚙️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, Imbalanced-learn  
- **Methods:** KNN Imputation, Feature Engineering, Ensemble Learning, Class Imbalance Treatment, Hyperparameter Tuning  
