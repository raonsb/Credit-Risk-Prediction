# 💼 Credit Risk Classification Project

This project focuses on building a machine learning model to classify borrowers into **"Good"** or **"Bad"** credit risk categories. By leveraging historical loan data from 2007-2014, the model aims to help financial institutions automate and improve the accuracy of credit evaluation processes.

---

## 🔍 Project Pipeline

### 📊 1. Data Understanding
- Performed initial inspection of the dataset to understand data structure and feature types.
- Checked for missing values and handled them accordingly.
- Identified and removed duplicate records to ensure data integrity.

### 🛠️ 2. Data Preparation (Part 1)
- Created the **target column** (`credit_risk`) by transforming the original label.
- Dropped irrelevant features that didn't contribute to modeling.
- Converted incorrect data types to ensure compatibility.
- Handled missing data using appropriate imputation strategies.

### 📈 3. Exploratory Data Analysis (EDA)
- Visualized **categorical features** with bar and pie charts.
- Analyzed distributions of **numerical features** using histograms and bar charts.
- Examined correlations between numerical features via a **correlation heatmap**.
- Identified temporal trends in the **loan amount** using a line chart.

### ⚙️ 4. Data Preparation (Part 2)
- Applied **feature engineering** including:
  - Multicollinearity reduction to remove redundant features.
  - **Ordinal and label encoding** for categorical variables.
- Split the dataset into **training and test sets**.
- Handled **class imbalance** using oversampling/undersampling techniques.
- Standardized numerical features for better model performance.

### 🤖 5. Modeling
Trained and evaluated five classification models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **XGBoost (Gradient Boosting)**
- **K-Nearest Neighbors (KNN)**

### 📊 6. Model Evaluation
Each model was evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC AUC Score**
- **Confusion Matrix**

The best performing model was **XGBoost**, which delivered the highest accuracy and lowest misclassification rate, especially in detecting high-risk (bad credit) borrowers.

---

## ✅ Conclusion

Through a full machine learning pipeline from raw data to prediction, this project demonstrated that **XGBoost** is the most suitable model for credit risk prediction. The combination of feature engineering, proper preprocessing, and careful evaluation resulted in a robust classification system.

---

## 💡 Business Recommendations

1. **Deploy XGBoost Model**  
   Use XGBoost for real-time credit scoring to enhance loan approval decisions.

2. **Automate Credit Evaluation**  
   Accelerate credit checks and detect high-risk borrowers early to take preventive action (e.g., request collateral, reduce credit limit).

3. **Monitor Trends Over Time**  
   Analyze predicted outcomes alongside loan trends (e.g., per month or quarter) to identify patterns and risks.

4. **Use Model Output for Strategic Planning**  
   Combine current prediction results with borrower history to develop targeted repayment programs or reduce default risks.

---

## 🧠 Skills Applied

- Data cleaning and wrangling using **Pandas & NumPy**
- Exploratory Data Analysis with **Matplotlib & Seaborn**
- Feature engineering and preprocessing using **Scikit-learn**
- Supervised machine learning (classification) with:
  - **Logistic Regression**
  - **Tree-based Models (Decision Tree, Random Forest)**
  - **XGBoost**
  - **K-Nearest Neighbors (KNN)**
- Model evaluation using metrics like **Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC AUC**
- Public Speaking/Communication of business insights and actionable recommendations

---

> 📩 Feel free to fork this project or reach out if you'd like to collaborate or give feedback!
