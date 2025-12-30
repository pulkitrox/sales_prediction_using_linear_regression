# 📊 Sales Prediction Analysis using Advertising Data

## 📌 Project Overview
This project analyzes the relationship between advertising expenditure across different media channels and product sales. Using **multiple linear regression**, the goal is to understand which advertising medium contributes most to sales and to build a predictive model that can estimate sales for new advertising budget scenarios.

---

## 🎯 Objective
- Predict product **sales** based on advertising spend on TV, Radio, and Newspaper  
- Identify the **most influential advertising channel**  
- Evaluate model performance using regression metrics  
- Simulate **what-if advertising scenarios**

---

## 📁 Dataset Description
| Column | Description |
|------|-------------|
| TV | Advertising spend on television |
| Radio | Advertising spend on radio |
| Newspaper | Advertising spend in newspapers |
| Sales | Units sold |

---

## 🔍 Key Insights
- TV advertising shows a **very strong correlation (~0.90)** with sales  
- Radio has a **moderate impact**, while Newspaper has **minimal influence**  
- TV is the **primary sales driver**

---

## 🧠 Modeling Approach
- Algorithm: **Multiple Linear Regression**
- Train-Test Split: **80% / 20%**
- Preprocessing:
  - Missing value imputation
  - Feature scaling (Standardization & Normalization)

---

## 📈 Model Performance
- **R² Score:** ~0.93  
- **MSE:** 2.17  
Both scaling techniques yielded identical results in this dataset.

---

## 🔮 Sample Prediction
**Input:**
- TV: 200  
- Radio: 40  
- Newspaper: 50  

**Predicted Sales:** ~19.82 units

---

## 📂 Repository Structure
```
├── sales_prediction.ipynb
├── Sales-Prediction-Analysis.pptx
├── README.md
├── advertising_sales_data.csv
```

---

## 🛠️ Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

---

## 🚀 Future Work
- Add advanced regression models
- Cross-validation
- Include digital marketing data
- Deploy as a web app
