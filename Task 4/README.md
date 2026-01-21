# Task 4: Feature Encoding & Scaling

##  Objective
The objective of this task is to understand and implement **feature engineering techniques**, specifically **feature encoding and feature scaling**, using the **Adult Income Dataset**. This task helps in preparing raw data into a machine-learning-ready format.

---

## 🗂 Dataset
- **Name:** Adult Income (Census Income) Dataset  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/uciml/adult-census-income  

The dataset contains demographic and employment-related attributes used to predict whether a person earns more than \$50K annually.

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  Task Breakdown

### 1. Data Loading & Exploration
- Loaded the Adult Income dataset using Pandas
- Inspected data types, structure, and missing values
- Cleaned missing values (`?`) and removed null entries

### 2. Feature Identification
- Identified **categorical features** (object type)
- Identified **numerical features** (int and float type)

### 3. Feature Encoding
- **Label Encoding**
  - Applied to ordinal/target feature (`income`)
- **One-Hot Encoding**
  - Applied to nominal categorical features such as:
    - workclass
    - education
    - marital-status
    - occupation
    - race
    - sex
    - native-country

### 4. Feature Scaling
- Used **StandardScaler**
- Scaled numerical features such as:
  - age
  - capital-gain
  - capital-loss
  - hours-per-week
- Compared feature distributions **before and after scaling**

### 5. Model Readiness Comparison
- Observed how scaling standardizes feature ranges
- Explained impact on ML algorithms

### 6. Dataset Export
- Saved the final preprocessed dataset as:
