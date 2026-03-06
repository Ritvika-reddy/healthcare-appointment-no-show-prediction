# 🏥 Healthcare Appointment No-Show Prediction & Analysis

## 📌 Project Overview
Missed medical appointments (no-shows) are a major issue for healthcare providers. They cause inefficient scheduling, revenue loss, and delays in patient care. Predicting which patients are likely to miss appointments can help hospitals improve scheduling efficiency and reduce operational losses.

This project analyzes healthcare appointment data and builds a **machine learning model to predict patient no-shows**. The workflow includes **data cleaning, exploratory data analysis, machine learning modeling, and dashboard visualization using Power BI** to generate actionable insights.

---

## 🎯 Project Objectives
- Analyze patterns affecting patient appointment attendance
- Identify key factors contributing to appointment no-shows
- Build a predictive machine learning model
- Handle class imbalance using **SMOTE**
- Create an **interactive Power BI dashboard** for business insights

---

## 📂 Dataset
Healthcare Appointment Dataset containing patient scheduling and medical information.

### Main Features
- Gender  
- Age  
- Scholarship  
- Hypertension  
- Diabetes  
- Alcoholism  
- Handicap  
- SMS Received  
- Scheduled Day  
- Appointment Day  
- Neighborhood  

### Target Variable
`no_show`
- **0 → Patient attended appointment**
- **1 → Patient missed appointment**

---

## 🛠 Tools & Technologies Used

### Programming & Data Science
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn
- Decision Tree
- Random Forest
- SMOTE (Imbalanced-Learn)

### Visualization
- Power BI
- DAX

### Development Environment
- Jupyter Notebook

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning & Preprocessing
The dataset required preprocessing before analysis.

Steps performed:
- Removed unnecessary columns
- Converted categorical features to numeric format
- Converted boolean values to integers
- Created new features such as:
  - **Waiting Days**
  - **Age Groups**
  - **Appointment Weekday**
- Prepared dataset for machine learning models

---

### 2️⃣ Exploratory Data Analysis (EDA)
EDA was performed to understand patterns influencing appointment attendance.

Key analyses:
- Distribution of no-show appointments
- Impact of waiting days on attendance
- Effect of SMS reminders
- Age group analysis
- Weekday impact on no-show behavior

Visualization libraries used:
- Matplotlib
- Seaborn

---

### 3️⃣ Handling Class Imbalance
The dataset contained significantly more attended appointments than missed ones.

To address this imbalance:
- **SMOTE (Synthetic Minority Oversampling Technique)** was applied
- This generated synthetic samples for the minority class (no-show)

This step improved the model’s ability to detect missed appointments.

---

### 4️⃣ Machine Learning Model Development
Several models were trained and evaluated.

Models tested:
- Decision Tree
- Decision Tree (Balanced)
- Random Forest
- Random Forest with SMOTE

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Special focus was placed on **Recall for the No-Show class**, as detecting high-risk patients is more important than maximizing overall accuracy in healthcare applications.

---

## 📊 Model Performance
The final optimized model used in this project was:

**Random Forest + SMOTE**

Key results:
- Improved recall for predicting missed appointments
- Better identification of high-risk patients
- Balanced classification performance

---

## 📊 Power BI Dashboard
An interactive dashboard was developed using Power BI to visualize insights from the dataset.

### Dashboard Components

**Key Metrics (KPIs)**
- Total Patients
- Total No-Shows
- No-Show Rate

**Visualizations**
- Waiting Days vs No-Show Rate
- SMS Reminder Impact
- No-Show by Age Group
- Weekday Impact

**Interactive Filters**
- Gender
- Age Group

The dashboard helps healthcare administrators understand patterns and make data-driven decisions.

---

## 🔎 Key Insights
- Approximately **20% of appointments are missed**
- Longer waiting periods increase the likelihood of no-shows
- SMS reminders reduce missed appointments
- Certain age groups show higher no-show behavior
- Appointment day patterns influence attendance

---

## 💡 Business Recommendations
Healthcare providers can reduce missed appointments by:

- Reducing waiting time between scheduling and appointment
- Implementing strong reminder systems (SMS / notifications)
- Identifying high-risk patients using predictive models
- Adjusting scheduling strategies based on historical patterns

---

## 📁 Project Structure
data/ – Dataset files  
notebook/ – Jupyter notebook for analysis and modeling  
dashboard/ – Power BI dashboard  
report/ – Project report  
README.md – Project documentation

---

## 🎓 Learning Outcomes
Through this project I gained experience in:

- Real-world healthcare data analysis
- Handling imbalanced datasets
- Machine learning model evaluation
- Data storytelling with dashboards
- End-to-end data science workflow

---

## 📌 Conclusion
This project demonstrates how **data analytics and machine learning can help solve real-world healthcare challenges**. By predicting appointment no-shows and identifying key behavioral patterns, healthcare providers can optimize scheduling, reduce missed appointments, and improve operational efficiency.

The integration of **machine learning models with interactive Power BI dashboards** enables effective data-driven decision making in healthcare management.
