# 📊 Customer Credit Risk Analysis

## Data Preprocessing and Feature Engineering Project 🚀

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![ScikitLearn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 🌟 Project Overview

This project focuses on performing **complete Data Preprocessing and Feature Engineering** on a **Customer Credit Risk Dataset** containing **50 customer records**.

The goal of this project is to transform raw and incomplete data into a **clean, structured, and Machine Learning ready dataset** using multiple preprocessing techniques.

The project demonstrates real-world Data Science workflow including data acquisition, cleaning, missing value handling, outlier detection, encoding, scaling, and transformation.

---

# 🎯 Objectives

The main objectives of this project are:

✅ Understand complete Data Preprocessing workflow
✅ Handle missing values using multiple imputation techniques
✅ Detect and treat outliers in dataset
✅ Encode categorical data into numerical format
✅ Apply feature scaling techniques
✅ Prepare dataset for Machine Learning model training
✅ Build industry-level Data Science understanding

---

# 🛠 Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-Learn
* 🗄 SQLite Database
* 📄 JSON
* 📓 Jupyter Notebook

---

# 📂 Dataset Information

Dataset contains **50 banking customer records**.

### Features Included

* customer_id
* age
* gender
* region
* education_level
* employment_type
* annual_income
* loan_amount
* loan_purpose
* credit_score
* repayment_history
* transaction_count
* spending_ratio
* join_date
* default_flag

---

# 📌 Project Workflow

The project is divided into multiple sections.

---

# 🧩 Part A – Conceptual Foundation

This section covers theoretical concepts.

Topics covered:

📖 What is Data Analysis
📖 How to Plan a Data Science Project
📖 Machine Learning Problem Framing
📖 Tensor Operations using NumPy

Implemented:

* 1D Tensor
* 2D Tensor
* 3D Tensor
* Shape Detection
* Dimension Checking
* Mathematical Operations

---

# 📥 Part B – Data Acquisition

Data was collected from multiple sources.

### Sources Used

📄 CSV File → Customer Dataset

📄 JSON File → Metadata Dataset

🗄 SQL Database → Loan History Storage

Operations performed:

* Data Loading
* Database Connection
* SQL Table Creation
* Data Insertion
* Data Retrieval

---

# 🧹 Part C – Missing Value Handling

Dataset contained missing values in multiple columns.

Missing columns:

* Age
* Employment Type
* Credit Score

Methods used:

✅ Mean Imputation
✅ Median Imputation
✅ Mode Imputation
✅ KNN Imputer
✅ Iterative Imputer (MICE)

---

# 📸 Screenshot 1 – Missing Value Detection Matrix

<img width="2027" height="971" alt="image" src="https://github.com/user-attachments/assets/486d9d7c-7ac1-467b-b2a6-828d135df4cd" />

**Description:**
This graph shows missing values present in the original dataset before preprocessing. White spaces indicate incomplete data records.

---

# 📸 Screenshot 2 – Missing Values After Cleaning

<img width="2042" height="1006" alt="image" src="https://github.com/user-attachments/assets/1c1a8400-af99-4d54-9660-e1fb7cb41ea3" />


**Description:**
After applying imputation techniques, all missing values were removed successfully. Every column now contains 50 complete records.

---

# 📊 Part D – Outlier Detection and Treatment

Outliers are extreme abnormal values that can affect machine learning performance.

Methods used:

📈 Z-Score Method
📊 IQR Method
📦 Boxplot Visualization
⚡ Winsorization Technique

---

# 📸 Screenshot 3 – Annual Income Outlier Detection

<img width="520" height="433" alt="image" src="https://github.com/user-attachments/assets/93cc9ab9-c27e-4614-9ff6-6640ec17d966" />


**Description:**
Boxplot visualization used for detecting outliers in customer annual income data.

---

# 📸 Screenshot 4 – Loan Amount Outlier Detection

<img width="536" height="433" alt="image" src="https://github.com/user-attachments/assets/a6de2330-c09d-46d6-af9a-c6d4d5d31f89" />


**Description:**
This boxplot was used to analyze abnormal loan amount distribution.

---

# 📸 Screenshot 5 – Annual Income After Outlier Treatment

<img width="520" height="433" alt="image" src="https://github.com/user-attachments/assets/44035b0a-f6d5-49ad-a704-9e2ae5829f0a" />


**Description:**
Winsorization was applied to control extreme annual income values.

---

# 📸 Screenshot 6 – Final Winsor Income Distribution

<img width="525" height="433" alt="image" src="https://github.com/user-attachments/assets/f0f331ff-7be2-4857-8714-1bf409dd7fb3" />


**Description:**
Final boxplot showing reduced effect of outliers after preprocessing.

---

# 🔢 Part E – Categorical Data Encoding

Machine Learning requires numerical data.

Encoding methods used:

### Label Encoding

Applied on:

* Gender
* Employment Type

### One Hot Encoding

Applied on:

* Region

Generated columns:

* Region East
* Region North
* Region South
* Region West

### Ordinal Encoding

Applied on Education Level.

Order used:

Primary → 0
Secondary → 1
Graduate → 2
Post-Graduate → 3

---

# ⚙ Part F – Feature Scaling and Transformation

Feature scaling improves machine learning performance.

Methods used:

📊 StandardScaler
📈 MinMaxScaler
⚡ MaxAbsScaler
🛡 RobustScaler
🔄 PowerTransformer

These methods transformed numerical values into standardized ranges.

---

# 🏆 Final Results

Project successfully completed complete preprocessing pipeline.

Final achievements:

✅ Missing values removed successfully
✅ Outliers detected and treated
✅ Categorical data encoded
✅ Numerical data scaled properly
✅ Final machine learning ready dataset prepared

Records Processed:

**50 Customer Records**

---

# 📖 Learning Outcomes

This project helped understand:

* Data Cleaning Techniques
* Missing Value Handling
* Outlier Detection
* Feature Engineering
* Encoding Methods
* Scaling Techniques
* Real-world Data Science Workflow

---

# 🚀 Conclusion

This project successfully demonstrated a complete **Data Preprocessing and Feature Engineering pipeline** using Python.

Raw customer credit risk data was transformed into a clean and structured dataset ready for Machine Learning applications.

The project provided practical understanding of real-world Data Science workflow and industry-level preprocessing techniques.

---

# 🙏 Thank You ⭐
