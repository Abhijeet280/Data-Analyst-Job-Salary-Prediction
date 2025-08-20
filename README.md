# Data Analyst Salary Prediction

This project predicts the salaries of **Data Analysts** based on job-related features such as company size, sector, location, and more. It involves **exploratory data analysis, feature engineering, and machine learning models** to estimate salaries.

---

## 📑 Dataset

The dataset (`DataAnalyst.csv`) contains job postings for **Data Analyst roles** along with company information and estimated salaries.

### Key Columns

* **Job Title** – Title of the job (e.g., Data Analyst, Senior Data Analyst).
* **Salary Estimate** – Estimated salary range from Glassdoor.
* **Job Description** – Text describing the role and responsibilities.
* **Rating** – Company rating (out of 5).
* **Company Name** – Name of the employer.
* **Location** – Job location.
* **Headquarters** – Company headquarters.
* **Size** – Company size (number of employees).
* **Founded** – Year the company was founded.
* **Type of ownership** – Ownership structure (Private, Public, Nonprofit, etc.).
* **Industry** – Industry classification.
* **Sector** – Business sector.
* **Revenue** – Revenue range of the company.
* **Competitors** – Competitor companies listed.
* **Easy Apply** – Indicates if the job supports quick apply.

## 📂 Project Workflow

1. **EDA & Data Cleaning** – Handling missing values, duplicates, and irrelevant columns.
2. **Feature Engineering** – Encoding categorical variables and scaling numerical features.
3. **Data Analysis** – Visualizing salary trends by company size, sector, and location.
4. **Model Development** – Implemented:

   * Linear Regression
   * Random Forest Regressor
5. **Evaluation** – Performance measured with R², Adjusted R², and Mean Absolute Error (MAE).

---

## 🚀 Technologies Used

* **Python** (NumPy, Pandas, Matplotlib, Seaborn)
* **Scikit-learn** (Linear Regression, Random Forest, Train-Test Split, Evaluation Metrics)

---

## 📊 Key Insights

* Top locations and company sizes significantly impact salary.
* Random Forest performed better than Linear Regression in prediction accuracy.

---
