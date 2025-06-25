# 🧠 Mental Health Workplace Analysis

This project explores factors that influence mental health treatment-seeking behavior in workplace environments. Using real-world survey data, it combines data cleaning, visual exploration, and machine learning to uncover key insights about mental health awareness, support systems, and employee behavior.

---

## 📌 Problem Statement

Despite growing awareness, many employees hesitate to seek mental health treatment due to stigma, lack of support, or fear of professional consequences. This project aims to identify the key personal and workplace factors that influence such decisions, using data-driven approaches to inform better workplace policies and mental wellness strategies.

---

## 🎯 Objectives

- Understand how demographics and work conditions impact mental health treatment.
- Identify top predictors of treatment-seeking using machine learning models.
- Visualize patterns across age, gender, geography, and company support systems.
- Help organizations recognize areas for improving mental health support.

---

## 📂 Dataset

- Source: [OSMI Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)  
- Format: CSV  
- Features: Demographics, workplace conditions, mental health history, treatment behavior, etc.

---

## 🔍 Exploratory Data Analysis (EDA)

- Age distribution histogram  
- Gender distribution bar chart  
- Treatment count by country (Top 10)  
- Work interference vs treatment-seeking behavior  
- Remote work and employer support analysis  
- Correlation heatmap and feature importance plot  

---

## 🤖 Machine Learning

- **Algorithm Used**: Random Forest Classifier  
- **Target Variable**: `treatment` (Yes/No → 1/0)  
- **Steps**:
  - Label encoding of categorical variables
  - Feature selection
  - Train-test split (80/20)
  - Model training and evaluation
  - Feature importance visualization

---

## 📊 Key Findings

- Work interference and family history are the strongest predictors of treatment.
- Company support (benefits, open discussion) influences treatment decisions.
- Geographic and cultural factors affect mental health awareness.
- Younger professionals are more represented and more likely to seek treatment.

---

## 📁 Tech Stack

- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Machine Learning)
- Google Colab / Jupyter Notebook

---

## ✅ Conclusion

The project reveals how workplace dynamics, personal background, and organizational culture contribute to mental health treatment-seeking behavior. The findings highlight the need for inclusive and supportive workplace policies and suggest that data-driven strategies can guide effective mental wellness initiatives.

---

## 📌 Future Work

- Use SHAP values for better model interpretability  
- Develop a web-based dashboard (e.g., with Streamlit)  
- Integrate external health/HR datasets for deeper insights  
- Study long-term trends using time-series analysis  

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Shruti Sampat Ghumare**  
_Data Analyst | Machine Learning Enthusiast_

---


