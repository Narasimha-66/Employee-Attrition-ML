# Employee Attrition Prediction using Machine Learning

This capstone project analyzes employee data to understand the reasons behind attrition and predict which employees are likely to leave using Machine Learning techniques.

---

## Project Objectives

When skilled employees leave an organization, it affects productivity, knowledge retention, and hiring costs.  
This project helps HR teams:
- Analyze employee exit patterns
- Visualize important insights
- Build a predictive model to flag potential exits early

---

## Dataset Overview

- **Source:** Provided in Infosys Springboard course
- **Records:** ~15,000 employees
- **Target Variable:** `left` (1 = employee left, 0 = stayed)
- **Features:**
  - Satisfaction level
  - Last evaluation score
  - Average monthly hours
  - Department
  - Salary level
  - Promotions in the last 5 years

File: `employee_attrition.csv`

---

## Exploratory Data Analysis (EDA)

- Employees with **low satisfaction** and **high workload** were more likely to leave.
- Departments with **no recent promotions** had higher attrition.
- **Low salary groups** showed a high turnover rate.

Visualizations used:
- Correlation heatmap
- Department-wise attrition count
- Salary vs Exit distribution
- Scatter plots for satisfaction vs work hours

---

## Machine Learning Model

- **Algorithm:** Random Forest Classifier
- **Train/Test Split:** 80/20
- **Accuracy Achieved:** *[98.83%]*

---

### Evaluation Metrics:
- Accuracy
- Confusion matrix
- Classification report


# Libraries used:
python
pandas, matplotlib, seaborn, scikit-learn

# Folder Structure
Employee-Attrition-ML
├── Capstone_Employee_Attrition.ipynb   # Main notebook
├── employee_attrition.csv              # Dataset
├── README.md                           # Project documentation

---

# Learning Outcomes:

Applied end-to-end ML pipeline: data cleaning → EDA → modeling → evaluation
Understood how HR features impact attrition
Created a sharable GitHub and LinkedIn-ready project

# Author

Narasimha Jaladurgam  

[GitHub Repository](https://github.com/Narasimha-66) 

[LinkedIn Profile](https://www.linkedin.com/in/narasimha-jaladurgam-90266624b)  

Capstone Project - Infosys Springboard.




  
