# 💻 Laptop Price Prediction | Data Analysis & Machine Learning

---

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Problem Statement](#Problem-Statement)
3. [Dataset Description](#dataset-description)
4. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Exploratory Data Analysis](#exploratory-data-analysis)
7. [Model Building](#model-building)
8. [Model Evaluation](#model-evaluation)
9. [Key Learnings](#key-learnings)
10. [Future Improvements](#future-improvements)
11. [About Me](#about-me)
12. [Author](#author)
---

## 📌 Project Overview

This project focuses on predicting **laptop prices** based on their specifications using **data analysis and machine learning techniques**.  
The aim is to understand how different hardware and display features influence the price of a laptop.

The project follows an end-to-end **data science workflow**, starting from raw data cleaning to feature engineering and model preparation.

---

##  Problem Statement

Laptop prices vary significantly based on specifications such as processor, RAM, storage, screen resolution, and display quality.  
The objective of this project is to build a machine learning-ready dataset that can accurately predict laptop prices based on these features.

---

##  Dataset Description

The dataset contains laptop specifications such as:

- Company
- Laptop Type
- Screen Size (Inches)
- Screen Resolution
- CPU
- RAM
- Storage
- GPU
- Operating System
- Weight
- Price (Target Variable)

---

##  Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary and redundant columns  
- Converted text-based numeric columns into proper numerical formats  
- Handled inconsistent values and formats  
- Cleaned resolution values by removing commas and extra text  

---

##  Feature Engineering

Several meaningful features were created to improve model performance:

- **Screen Resolution Extraction**
  - Extracted `x_res` (width) and `y_res` (height)

- **PPI (Pixels Per Inch)**
  - Calculated using screen resolution and screen size to represent display quality

- **CPU Name Simplification**
  - Reduced noisy CPU descriptions to simplified categories

- **Processor Categorization**
  - Intel Core i3 / i5 / i7  
  - Other Intel Processors  
  - AMD Processors  

These transformations helped reduce noise and improve feature relevance.

---

##  Exploratory Data Analysis (EDA)

EDA was performed to:

- Analyze price distribution  
- Understand relationships between features and price  
- Identify important features influencing laptop prices  
- Detect outliers and patterns  

---

##  Model Building

The cleaned and engineered dataset is prepared for machine learning models such as:

- Linear Regression  
- Ridge & Lasso Regression  
- Random Forest Regressor  

The focus is on understanding how feature engineering impacts model performance.

---

##  Model Evaluation

Models are evaluated using metrics such as:

- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  

These metrics help assess prediction accuracy and model reliability.

---

##  Key Learnings

- Importance of feature engineering in price prediction  
- Handling real-world messy datasets  
- Transforming text-heavy data into ML-ready numerical features  
- Understanding the relationship between hardware specifications and price  

---

##  Future Improvements

- Hyperparameter tuning  
- Feature selection optimization  
- Trying advanced models like XGBoost  
- Model deployment using Flask or Streamlit  

---

##  About Me

I am actively exploring the **Data Analytics and Data Science** field by working on real-world datasets.  
This project reflects my hands-on learning approach and growing interest in building practical machine learning solutions.

---

##  Author

**Sanjeet Jaiswal**  
**Aspiring Data Scientist / Data Analyst / ML Engineer**

📧 Email: sanjeet221601@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/sanjeetjaiswal/

---
