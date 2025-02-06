# 🦠 **Rabies Cases Analysis and Prediction Pipeline**  

This repository presents a comprehensive pipeline for analyzing and predicting **Rabies cases** using cutting-edge **machine learning models**. Leveraging publicly available data from the **New York State Health Department**, the project aims to help researchers, public health officials, and policymakers better understand Rabies trends and allocate resources effectively.

---

## 🚀 **Project Structure**  

### 1. 📥 **Data Collection**  
- **Source:** New York State Health Department  
- **Format:** CSV files dynamically fetched via API requests

### 2. 🔧 **Data Preprocessing**  
- Handling missing values  
- Encoding categorical variables  
- Scaling features  
- Balancing the dataset using **SMOTE (Synthetic Minority Oversampling Technique)**  

### 3. 📊 **Exploratory Data Analysis (EDA)**  
- Gaining insights using summary statistics  
- Visualizing trends and key variables  

### 4. 🤖 **Modeling**  
- Applying machine learning models:
  - **Logistic Regression**
  - **XGBoost**
  - **Neural Networks**  

### 5. 📈 **Model Evaluation**  
- Evaluating performance using:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
  - **Confusion Matrix**  

---

## 📚 **Prerequisites**  
Ensure you have the required libraries installed by running:  

```bash
pip install scikit-learn xgboost imbalanced-learn pandas matplotlib seaborn torch keras
