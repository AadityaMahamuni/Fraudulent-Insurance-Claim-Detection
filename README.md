# 🛡️ Fraudulent Insurance Claim Detection using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-EC6B23?style=for-the-badge)

</p>

---

## 📖 Project Overview

This project develops a Machine Learning solution for detecting fraudulent insurance claims using historical insurance claims data.

The objective is to classify incoming insurance claims as **Fraudulent** or **Legitimate**, enabling insurance companies to identify suspicious claims early in the approval process, reduce financial losses, and improve operational efficiency.

---

## 🎯 Problem Statement

**Global Insure**, a leading insurance company, processes thousands of insurance claims every year.

A significant portion of these claims are fraudulent, leading to substantial financial losses. The existing manual fraud detection process is time-consuming, inefficient, and often identifies fraudulent claims only after payouts have already been made.

This project addresses this challenge by developing a predictive machine learning model that classifies insurance claims as fraudulent or legitimate based on historical claim data, allowing the company to proactively investigate high-risk claims before approval.

---

## 🎯 Objectives

- Analyze historical insurance claim data.
- Perform Exploratory Data Analysis (EDA).
- Identify important fraud indicators.
- Handle missing values and categorical variables.
- Address class imbalance using SMOTE.
- Train and compare multiple classification models.
- Select the best-performing model.
- Generate actionable business insights.



## 📂 Dataset Information

The dataset contains approximately **1,000 insurance claims** described by around **40 attributes**, including:

- Customer demographics
- Policy details
- Vehicle information
- Incident details
- Claim amount
- Police reports
- Incident severity
- Claim history

### Target Variable

```text
fraud_reported
```
-
  - Y → Fraudulent Claim
  - N → Legitimate Claim

The dataset is imbalanced:

- Fraudulent Claims: **231 (23.1%)**
- Legitimate Claims: **769 (76.9%)** 



## 🛠 Technologies Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| IDE | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Gradient Boosting | XGBoost |
| Class Balancing | SMOTE |



## 🔄 Project Workflow

```text
Load Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Treatment
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Encoding
      │
      ▼
Feature Scaling
      │
      ▼
SMOTE (Class Balancing)
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
(Logistic Regression,
Decision Tree,
Random Forest,
XGBoost)
      │
      ▼
Model Comparison
      │
      ▼
Model Evaluation
      │
      ▼
Business Recommendations
```



## 🧹 Data Preprocessing

The preprocessing pipeline included:

- Missing value imputation
- One-hot encoding of categorical variables
- Feature scaling
- Removal of irrelevant features
- Class balancing using SMOTE
- Feature importance analysis



## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

After comparing multiple models, **XGBoost** achieved the best overall performance. 



## 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Precision-Recall Curve
- Confusion Matrix



## 🏆 Best Model Performance

| Model | Performance |
|--------|-------------|
| XGBoost | Best Overall Model |
| Accuracy | **95%** |
| F1 Score | **0.89** |
| ROC-AUC | **0.97** |

The XGBoost model achieved the highest predictive performance, making it the preferred model for fraud detection. 



## 💡 Key Insights

Important findings from the analysis include:

- Incident Severity is one of the strongest fraud indicators.
- High Total Claim Amounts are frequently associated with fraudulent claims.
- Multi-vehicle collisions appear more frequently in fraudulent cases.
- Certain insured hobbies exhibit unusually high fraud rates.
- Missing police reports increase fraud likelihood.
- Class balancing using SMOTE significantly improved fraud detection performance.
- XGBoost outperformed Logistic Regression, Decision Tree, and Random Forest. 


## 📸 Sample Visualizations

<img width="767" height="585" alt="image" src="https://github.com/user-attachments/assets/7fe2eeb8-51b6-41f0-820e-a711e3fc6470" />  <img width="788" height="595" alt="image" src="https://github.com/user-attachments/assets/36323acf-256c-466f-80fe-fe3c532e1723" />  <img width="735" height="545" alt="image" src="https://github.com/user-attachments/assets/3bf23231-3bc4-4eb6-a32c-3333b14e9ff7" />  



## 💼 Business Recommendations

Based on the project findings:

- Prioritize claims with high predicted fraud probability for manual review.
- Integrate the trained model into the claim approval workflow.
- Continuously retrain the model using newly available claim data.
- Collect additional fraud-related features to further improve prediction accuracy.
- Monitor model performance and periodically update probability thresholds.



## 📁 Project Structure

```text
Fraudulent_Insurance-Claim-Detection
│
├── Fraudulent_Insurance-Claim-Detection.ipynb      # Complete notebook containing EDA, preprocessing, model training, and evaluation
│
├── Project_Report.pdf                              # Technical report explaining methodology and results
│
├── Project_Presentation.pdf                        # Presentation summarizing the project and key findings
│
├── README.md                                       # Complete project documentation
│
└── requirements.txt                                # Required Python libraries
 
```

---

## 🚀 Future Improvements

- Deploy the model as a REST API for real-time fraud detection.
- Develop an interactive Streamlit dashboard.
- Incorporate deep learning techniques for complex fraud patterns.
- Explore anomaly detection methods for identifying previously unseen fraud cases.
- Continuously retrain the model with newly collected insurance claim data.

---

## 👨‍💻 Author

**ADITYA AMRENDRA MAHAMUNI**

Master's Student in Mechatronics  
Interested in Data Science • Machine Learning •  Computer Vision • Robotics • Embedded Systems 

---

## 📞 Contact & Questions

For questions about this project:
- 📧 Email: adityamahamuni108@gmail.com
- 🔗 LinkedIn: [Aditya-Mahamuni](https://www.linkedin.com/in/aaditya-mahamuni/)
- 🐙 GitHub: [@AadityaMahamuni](https://github.com/AadityaMahamuni)

---

⭐ If you found this project useful, please consider giving it a STAR..!!
