# 💳 **Buy Now Pay Later (BNPL) Model Analysis and Prediction**

This project focuses on the development of a **Buy Now, Pay Later (BNPL) prediction model** using **machine learning** techniques. The goal is to identify customers who are most likely to opt for BNPL services and predict payment behaviors, enabling strategic interventions and risk mitigation.

---

## 🚀 **Project Overview**

- **Business Objective:** Predict the likelihood of users opting for BNPL services, assess potential risks, and provide actionable insights for stakeholders.  
- **Data Source:** Customer transactional, behavioral, and demographic data (provided in the notebook).  
- **Key Models:** Logistic Regression, Random Forest, Gradient Boosting Machines.  

---

## 🛠️ **Project Workflow**

1. **Data Loading and Cleaning:**  
   - Handle missing values.  
   - Remove outliers.  
   - Encode categorical variables.  

2. **Exploratory Data Analysis (EDA):**  
   - Analyze customer segments.  
   - Identify transaction patterns.  
   - Visualize key insights using Matplotlib and Seaborn.  

3. **Feature Engineering:**  
   - Create relevant features such as payment history, transaction frequency, etc.  

4. **Modeling:**  
   - Train models like Logistic Regression, Random Forest, and Gradient Boosting.  
   - Perform hyperparameter tuning using Grid Search or Random Search.  

5. **Model Evaluation:**  
   - Evaluate models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC curves.  

6. **Insights and Recommendations:**  
   - Segment customers by risk profile.  
   - Provide suggestions for strategic interventions.  

---

## 📚 **Prerequisites**

Install the following dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

## ⚙️ **How to Run the Project**

1. **Clone the Repository:**  
```bash
git clone https://github.com/yourusername/bnpl-prediction.git
cd bnpl-prediction
```

2. **Install Dependencies:**  
```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook:**  
```bash
jupyter notebook Buy_Now_Pay_Later_Model.ipynb
```

---

## 📊 **Key Insights**

- **Key Predictors:** Features such as payment history, transaction amounts, and frequency significantly influence BNPL adoption.  
- **Customer Segmentation:** High-risk customers are identified through specific financial and transactional behaviors.  
- **Model Performance:** The Gradient Boosting model demonstrated superior predictive accuracy compared to other models.  

---

## 📜 **Directory Structure**

```
📂 bnpl-prediction
 ┣ 📂 data               # Contains datasets 
 ┣ 📂 models             # Saved models
 ┗ 📜 README.md          # Project documentation
```

---

## 🌍 **Use Cases**

- **Credit Risk Assessment:** Predict potential defaults and help mitigate financial risk.  
- **Marketing Campaigns:** Identify customers likely to adopt BNPL services for targeted marketing.  
- **Fraud Detection:** Spot anomalies in transactions and reduce fraudulent behavior.  

---

## 👩‍🔬 **Contributors**

- **[Nidhi Choudhary]([nidhi](https://github.com/NidhiChoudhary7/)** - Project Lead  
- **[Ritik Sinha](2)** - Data Analyst  


---

## 💬 **Feedback and Contributions**

We welcome feedback, suggestions, and contributions. Feel free to **open an issue** or submit a pull request.


