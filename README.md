# Data-Cleaning-Pipeline-using-Pandas

**🔨 What I Did**
In this project, I built a complete data cleaning pipeline for a loan approval dataset using Pandas. My main goal was to ensure the dataset was clean, consistent, and ready for analysis or machine learning modeling. Here’s a breakdown of the key steps I performed:

**Exploratory Data Assessment:** Analyzed dataset shape, data types, and summary statistics to understand column properties, identify missing values, and detect potential data quality issues.

**Missing Value Imputation:**

Filled missing values in categorical columns using the mode (most frequent value).

Filled missing values in numerical columns using the median, which is robust to outliers.

**Data Type Optimization:**

Converted string-based categorical features to the category data type for better memory efficiency and compatibility with ML models.

**Text Standardization:**

Removed leading/trailing whitespaces.

Converted text data to lowercase to maintain uniformity across entries.

**Outlier Handling:**

Capped extreme values in LoanAmount and ApplicantIncome at the 99th percentile to reduce the influence of outliers and improve distribution balance.

**Function Modularization:**

Encapsulated the entire cleaning workflow into a reusable function for scalability and ease of use in future projects.

**Exported Cleaned Dataset:**

Saved the cleaned version of the dataset as a CSV file for downstream tasks like feature engineering or model training.

This project showcases my ability to design a robust data preprocessing pipeline that is both systematic and efficient, an essential step in real-world data science workflows.
