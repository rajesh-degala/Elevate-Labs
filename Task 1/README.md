# Dataset Analysis Task

## Objective
The objective of this task is to understand the structure, data types, and machine learning readiness of given datasets using Python and Pandas.

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

---

## Datasets Used
1. **Titanic Dataset**
   - File: `titanic.csv`
   - Problem Type: Binary Classification
   - Target Variable: `Survived`

2. **Students Performance Dataset**
   - File: `StudentsPerformance.csv`
   - Problem Type: Regression
   - Target Variable: `math score`

---

## Task Performed
- Loaded datasets using Pandas
- Displayed first and last few records
- Analyzed dataset structure using `df.info()`
- Generated statistical summaries using `df.describe()`
- Identified numerical, categorical, ordinal, and binary features
- Analyzed categorical value distributions
- Identified target variables and input features
- Checked dataset size and machine learning suitability
- Observed data quality issues such as missing values and imbalance

---

## Key Observations

### Titanic Dataset
- Contains missing values in columns like `Age` and `Cabin`
- Mix of numerical and categorical features
- Target variable `Survived` is binary
- Dataset is suitable for classification models after preprocessing

### Students Performance Dataset
- No missing values
- Clean and well-structured dataset
- Suitable for regression-based machine learning models

---

## Files in This Repository
- `dataset_analysis.ipynb` – Jupyter Notebook with complete analysis
- `titanic.csv` – Titanic dataset
- `StudentsPerformance.csv` – Students performance dataset
- `README.md` – Project documentation

---

## Conclusion
This task helped in understanding how to explore datasets, identify feature types, assess data quality, and evaluate machine learning readiness before building models.

---

## Author
**Rajesh Degala**
