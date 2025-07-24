# 📊 Data Analytics Internship Projects – Bhavesh Santoshkumar Tupe

This repository contains two end-to-end data analytics projects completed as part of a 2-week internship. The focus is on HR Attrition Analysis and Customer Lifetime Value (LTV) Prediction. Both projects involve data preprocessing, visualization, machine learning modeling, and insight generation using Python and Power BI.

---

## 🧑‍💼 Project 1: HR Analytics – Predicting Employee Attrition

### ✅ Objective
To understand the key factors influencing employee attrition and build a machine learning model to predict future resignations, while also visualizing department-wise trends and KPIs using Power BI.

### 🛠 Tools & Technologies
- **Language**: Python  
- **Libraries**: pandas, seaborn, matplotlib, scikit-learn  
- **Visualization**: Power BI  
- **Platform**: Google Colab  

### 🔄 Steps Followed
1. **Data Cleaning**: Dropped constant columns (`EmployeeCount`, `Over18`, etc.) and encoded binary variables.
2. **EDA**: Analyzed attrition by gender, department, overtime, and age groups.
3. **Feature Engineering**: Created `AgeGroup` and used one-hot encoding for categorical features.
4. **Modeling**: 
   - Algorithm: Logistic Regression (`class_weight='balanced'`)
   - Feature Scaling: StandardScaler
   - Achieved **Recall = 0.62**, **Accuracy = 75.17%**
5. **Evaluation**:
   - Confusion Matrix: `[[192, 55], [18, 29]]`
   - F1 Score (Class 1): 0.44
6. **Power BI Dashboard**:
   - KPIs: Attrition Rate, Avg Income (Leavers)
   - Visuals: Attrition by Department, Job Role, AgeGroup, Gender, OverTime

### 📌 Deliverables
- `HR_.ipynb`: Complete EDA and modeling notebook  
- `AttritionDashboard.pbix`: Interactive Power BI report  
- `cleaned_hr_data.csv`: Cleaned data used in Power BI  
- `HR_Analysis.pdf`: Report with insights and prevention suggestions

---

## 🛍️ Project 2: Customer Lifetime Value (LTV) Prediction

### ✅ Objective
To predict the Lifetime Value of customers based on behavioral data, and segment them into value-based groups for marketing strategies.

### 🛠 Tools & Technologies
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, XGBoost  
- **Platform**: Google Colab  
- **Dataset**: Online Retail II Dataset (UK retailer)

### 🔄 Steps Followed
1. **Data Cleaning**: Removed missing CustomerIDs, negative/returned orders.
2. **Feature Engineering**:
   - Recency: Days since last purchase
   - Frequency: No. of transactions
   - AOV: Average Order Value
   - LTV: Total spend (target)
3. **Modeling**:
   - Algorithm: XGBoost Regressor
   - MAE: **703.16**, RMSE: **1672.68**
4. **Segmentation**:
   - Customers split into: Low, Mid, High, Very High LTV
5. **Visualization**:
   - LTV Distribution Plot (right-skewed)
   - Boxplot by LTV Segment

### 📌 Deliverables
- `ltv_prediction.ipynb`: Python notebook for preprocessing, modeling, and segmentation  
- `final_ltv_predictions.csv`: LTV predictions for all customers  
- `ltv_report.pdf`: Summary of findings and marketing strategy

---

## 🔚 Conclusion

Both projects demonstrate the power of combining data preprocessing, machine learning, and visualization for business decision-making. HR attrition modeling supports talent retention, while LTV prediction enables customer value optimization.

---

> 👤 Prepared by: Bhavesh Santoshkumar Tupe  
> 📅 Internship Duration: 2 Weeks  
> 📌 Platform: Google Colab, Power BI  
