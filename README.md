# 💼 Data Analyst Salary Prediction

This project predicts the **salaries of Data Analysts** using **Machine Learning models**.
It involves **data preprocessing, exploratory data analysis (EDA), encoding, scaling, and model building** with regression algorithms.

---

## 🚀 Project Overview

The notebook performs the following steps:

1. **Importing Libraries** – Loading required Python libraries (pandas, numpy, sklearn, matplotlib, seaborn, etc.)
2. **Exploratory Data Analysis (EDA)** – Analyzing salary trends across features such as company size, sector, and location.
3. **Encoding Data** – Converting categorical features into numerical values using Label Encoding.
4. **Scaling Data** – Normalizing features for better model performance.
5. **Model Building** – Training machine learning models for salary prediction:

   * Linear Regression
   * Random Forest Regressor
6. **Model Evaluation** – Comparing models using metrics such as **R² Score, Adjusted R², and MAE**.

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Linear Regression, Random Forest)
* Jupyter Notebook

---

## 📂 Dataset

The dataset `DataAnalyst.csv` contains information about **job postings for Data Analysts**, with features such as:

* **Job Title** – Title of the job (e.g., Data Analyst, Senior Data Analyst)
* **Salary Estimate** – Estimated salary range (target variable)
* **Rating** – Company rating out of 5
* **Company Name** – Employer name
* **Location** – Job location
* **Headquarters** – Company headquarters
* **Size** – Company size (employee count)
* **Founded** – Year the company was founded
* **Type of ownership** – Ownership type (Private, Public, Nonprofit, etc.)
* **Industry** – Industry classification
* **Sector** – Business sector
* **Revenue** – Revenue range of the company

---

## 📈 Expected Insights

* **Top locations and company sizes** significantly impact salaries.
* Certain **industries and sectors** offer higher salary ranges.
* **Random Forest Regressor** is expected to perform better than Linear Regression due to its ability to handle categorical and non-linear patterns.

---
