# Task1
# Task 1 – Data Cleaning & Preprocessing (AI/ML)

## 📌 Objective
This task focuses on preparing raw Titanic dataset data for machine learning by handling missing values, encoding categorical features, scaling numerical features, and removing outliers.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📁 Dataset
[Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
Used file: Titanic-Dataset.csv

---

## 📊 Steps Performed

### 1. Data Exploration
- Loaded the dataset using pandas.
- Displayed basic info (shape, info(), describe()).
- Checked for null values.

### 2. Handling Missing Values
- Filled missing values in Age with the *median*.
- Filled missing values in Embarked with a default value 'S'.
- Skipped dropping 'Cabin' as it wasn't in the dataset.

### 3. Encoding Categorical Features
- Encoded Sex and Embarked columns using *Label Encoding*.

### 4. Feature Scaling
- Standardized numerical columns (Age, Fare) using *StandardScaler* from scikit-learn.

### 5. Outlier Detection & Removal
- Used the *IQR method* to detect and print outliers in the Fare column.
- Removed rows with extreme outlier Fare values.

---

## 📌 Notes
- All preprocessing steps were performed carefully with error handling (e.g., column existence checks).
- Cleaned data is ready for modeling tasks like classification or survival prediction.

---
