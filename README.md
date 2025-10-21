# 🚍 Predicting Urban Transport Accessibility (SDG 11.2.1)

## 🌍 Project Overview
This project focuses on **SDG 11.2 — Sustainable Cities and Communities**, specifically **Indicator 11.2.1**, which measures:

> "The proportion of the population that has convenient access to public transport, by sex, age, and persons with disabilities."

The goal is to use **Machine Learning** to predict and analyze public transport accessibility patterns globally using data from the **UN-Habitat Urban Indicators Database**.

---

## 🧠 Objectives
- Analyze urban transport accessibility data across countries.
- Build a regression model to predict public transport access percentages.
- Evaluate model performance using MAE, RMSE, and R² metrics.
- Reflect on ethical implications related to data fairness and bias.

---

## 🧰 Tools & Technologies
- **Language:** Python  
- **Environment:** Google Colab  
- **Libraries:**  
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - joblib  

---

## 🗂️ Dataset
**Source:** [UN-Habitat Urban Indicators Database (SDG 11.2.1)](https://data.unhabitat.org/)  
**File:** `Indicator_11_2_1.xls`  

**Key Columns Used:**
- Country or Territory Name  
- SDG Region  
- SDG Sub-Region  
- Data Reference Year  
- Share of urban population with convenient access to public transport (%)  

---

## ⚙️ Workflow
1. **Data Loading** — Read Excel data into pandas.  
2. **Data Cleaning** — Handle missing values and encode categorical variables.  
3. **Feature Selection** — Choose relevant columns for model training.  
4. **Model Training** — Use a **Random Forest Regressor**.  
5. **Evaluation** — Measure performance using MAE, RMSE, R².  
6. **Visualization** — Plot feature importance and actual vs predicted values.  
7. **Model Saving** — Save trained model as `sdg11_2_model.pkl` using joblib.  

---

## 📊 Results
| Metric | Value (Example) |
|:--|:--|
| MAE | 3.45 |
| RMSE | 5.27 |
| R² Score | 0.82 |

The model shows strong predictive performance and helps identify trends in public transport accessibility.

---

## ⚖️ Ethical Reflection
**Potential Bias:**
- Underrepresentation of smaller or low-income regions.
- Historical inequalities may influence model outcomes.

**Fairness & Sustainability:**
- Promotes equitable planning by highlighting underserved areas.
- Encourages transparent, data-driven urban policy aligned with SDG 11.

---

## 🚀 Future Improvements
- Compare multiple ML algorithms (Random Forest, XGBoost, Linear Regression).  
- Integrate real-time mobility data from APIs.  
- Build a **Streamlit dashboard** for interactive visualization.  
- Add interpretability metrics (e.g., SHAP values) for explainability.

---

## 🎓 Author
**Name:** Gloria Nzivo
**Project:** SDG 11.2.1 — Predicting Urban Transport Accessibility  
**Institution:**PLP Academy
**Date:21st October 2025  

---

## 💡 Quote
> “AI isn’t just about code — it’s a tool to solve humanity’s greatest challenges.” 🌏
