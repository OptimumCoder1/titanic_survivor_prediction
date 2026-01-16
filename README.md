# Titanic - Machine Learning from Disaster 🚢

This project implements a **Logistic Regression** model to predict passenger survival on the Titanic using the classic dataset. It involves data cleaning, feature engineering, and binary classification.

## 📊 Project Overview
The goal is to predict whether a passenger survived the Titanic shipwreck (1 for survived, 0 for deceased) based on features like age, sex, passenger class, and more.

## 🛠️ Technologies Used
* **Python 3.10+**
* **Pandas** for data manipulation
* **Scikit-Learn** for Machine Learning
* **NumPy** for numerical computations
* **Jupyter Notebook**

## 🧹 Key Preprocessing Steps
To ensure the model performs accurately and avoids errors, the following steps were taken:
- **Feature Encoding:** Converted categorical data like `Sex` into numerical values (Male: 1, Female: 0).
- **Missing Value Treatment:** Imputed missing values for the `Age` column using the median.
- **Feature Selection:** Dropped non-numeric columns such as `Name`, `Ticket`, and `Cabin` to prevent processing errors.
- **Data Splitting:** Divided the data into training (80%) and testing (20%) sets to validate model performance.

📈 Results
The Logistic Regression model was trained using Scikit-Learn with an increased max_iter setting to ensure convergence. The final model provides a baseline for predicting survival based on the provided passenger demographics.
