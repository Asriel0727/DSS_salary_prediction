
# 📊 Team 10 Salary Prediction System

An interactive salary prediction platform based on a Random Forest Regression model, helping job seekers evaluate career paths and salary trends.

<div align="center">

| [Traditional Chinese](README.md) | [English](README_en-us.md) | [Demo Video](https://youtu.be/UVHKSnWRwPY) | [PDF](決策支援系統_13.pdf) |

</div>

---

## 📚 Table of Contents

- Project Overview  
- Environment Requirements  
- How to Run  
- Key Features  
- System Architecture & Technical Overview  
- Results & Expected Benefits  
- Known Issues & Future Improvements  

---

## 🧠 Project Overview

As graduation or career transitions approach, salary becomes one of the most important concerns for new graduates and experienced workers alike. This project aims to assist users in predicting salary levels based on selected job-related inputs such as company, position, and working conditions. 

We built a **salary prediction system using Python and a Random Forest Regression model**, and developed an interactive desktop interface using Tkinter. The dataset was collected from Dcard job-related surveys in the tech industry, preprocessed, and used to train and test the prediction model.

---

## 💻 Environment Requirements

- **Python Version**: 3.9 or above recommended  
- **Package Installation**:
  1. Open terminal and navigate to the project folder  
  2. Run: `pip install -r requirements.txt`

---

## ▶️ How to Run

1. Open the project using Visual Studio Code  
2. Choose the correct Python environment with the installed packages  
3. Run the Jupyter Notebook or the main script file and follow the interface instructions

---

## 🔧 Key Features

- User input fields:
  - Company and position (via dropdowns)
  - Years of relevant and current experience
  - Average monthly working hours and overtime frequency
  - Comfort level and workload rating
- A button triggers the prediction, returning salary directly in the interface
- Input validation with range checking and error messages

---

## 🏗️ System Architecture & Technical Overview

- **Random Forest Regression** used for salary prediction
- **Tkinter GUI** for desktop interaction
- **SQLite** database for storing preprocessed datasets
- Evaluation metrics:
  - **RMSE**: 2.317
  - **R² Score**: 0.502

---

## 🎯 Expected Benefits & Use Cases

- Help new graduates understand salary expectations for desired jobs
- Enable career changers to compare potential salaries across roles
- Analyze correlations between salary, overtime, workload, and experience
- Provide data-driven support for career planning and job evaluation

---

📂 GitHub Repository (code & dataset):  
[https://github.com/School-Project-YZU/DSS_salary_prediction.git](https://github.com/School-Project-YZU/DSS_salary_prediction.git)
