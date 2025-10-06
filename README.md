# 📊 Insurance Cost Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-🐍-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Data%20Modeling-F7931E?logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-11557C?logo=plotly&logoColor=white)


##  Project Overview
This project builds a **Linear Regression model** to predict **medical insurance costs** based on features like **age, BMI, smoker status, number of children, and region**.  

The goal is to understand how different factors influence medical charges and to demonstrate regression modeling using **Python (scikit-learn, pandas, matplotlib, seaborn)**.

---

##  Tech Stack
- **Python 3**
- **Pandas** – Data handling  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning (Linear Regression)  

---

## 📂 Dataset
The dataset includes the following features:
- `age` → Age of the insured  
- `sex` → Gender  
- `bmi` → Body Mass Index  
- `children` → Number of dependents  
- `smoker` → Smoking status  
- `region` → Residential region  
- `charges` → Medical insurance cost (Target variable)  

---

##  Workflow
1. **Data Preprocessing**
   - Handle categorical features (`sex`, `smoker`, `region`) using encoding  
   - Scale numerical features if required  

2. **Model Training**
   - Train a **Linear Regression model** using scikit-learn  

3. **Prediction**
   - Use the trained model to predict insurance charges for new data  

4. **Evaluation**
   - Compare **actual vs. predicted charges**  
   - Metrics: R² Score

5. **Visualization**
   - Regression line for single-variable regression  
   - **Actual vs Predicted** scatter plot for multivariable regression  

---
