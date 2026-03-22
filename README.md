# 📘 Predicting Voluntary Turnover Using Machine Learning Classification Methods for Strategic Retention Planning  
## Ramiro Ribadeneira
Toronto Metropolitan University

Data Analytics, Big Data, and Predictive Analytics Certificate

The Chang School of Continuing Education

Capstone Project (2026)

---

## 📌 Overview  
Voluntary employee turnover is one of the most costly and disruptive challenges facing modern organizations. As noted in the project proposal, replacing an employee can cost **up to 213% of their annual salary**, and traditional HR methods tend to be reactive rather than predictive. Machine learning (ML) offers a proactive alternative by identifying employees at risk of leaving and uncovering the key drivers behind attrition.

This capstone project develops and compares multiple ML classification models to predict voluntary turnover using the **IBM HR Analytics Employee Attrition Dataset**. The project emphasizes:

- Predictive accuracy  
- Interpretability  
- Strategic HR application  

---

## 🎯 Research Objectives  
This project answers four core research questions:

1. **RQ1 - Which employees are most likely to voluntarily leave the organization?**  
2. **RQ2 - Which employee characteristics are most predictive of voluntary turnover?**  
3. **RQ3 - Which ML classification methods provide the most accurate and reliable predictions?**  
4. **RQ4 - How can model outputs be translated into practical retention strategies?**

These questions bridge technical modeling with real-world HR impact.

---

## 📂 Dataset  

**Source:** IBM HR Analytics Employee Attrition Dataset (IBM Watson Analytics, 2016)  
**Records:** 1,470 employees  
**Features:** 35 variables including:

- Age  
- Gender  
- Job Role  
- Monthly Income  
- Job Satisfaction  
- Work-Life Balance  
- Overtime  
- Years at Company  
- Distance from Home  
- Performance Rating  
- **Attrition (Yes/No — target variable)**  

### Why This Dataset?
- Realistic HR variables  
- Clean and structured  
- Widely used in academic research  
- Supports feature engineering and interpretability  
- Avoids privacy concerns associated with real HRIS data  

### Limitations
- Synthetic (not real HRIS data)  
- No temporal dimension  
- Does not distinguish voluntary vs. involuntary attrition  
- Some self-reported variables may introduce bias  

---

## ⚙️ Methodology  
This project follows the **CRISP‑DM** framework to ensure alignment between business needs and technical execution.

### **1. Data Preprocessing & EDA**
- Missing value review  
- One‑hot encoding of categorical variables  
- Correlation analysis and multicollinearity checks  
- Feature scaling (Standard or Robust)  
- Class imbalance handling using **SMOTE**  
- Optional dimensionality reduction via **PCA**

### **2. Predictive Modeling**
Three tiers of models are compared:

| Tier | Model | Purpose |
|------|--------|----------|
| Baseline | Logistic Regression | Interpretability benchmark |
| Ensemble | Random Forest | Captures nonlinear relationships |
| Boosting | XGBoost / LightGBM | High‑performance classification |

Hyperparameter tuning is performed using Grid Search or Random Search.

### **3. Model Evaluation**
Metrics selected based on HR relevance:

- **Recall (Sensitivity)** — critical for identifying at‑risk employees  
- **F1‑Score** — balances precision and recall  
- **ROC‑AUC** — overall classification performance  

### **4. Explainability & Strategic Insights**
To answer RQ2 and RQ4:

- **SHAP values** quantify how each feature contributes to predictions  
- **Feature importance rankings** identify global drivers of turnover  
- Insights are translated into **retention strategies** for workforce planning  

---

## 🧰 Tools & Technologies  
| Category | Tools |
|----------|--------|
| Programming | Python 3.x |
| Data Manipulation | Pandas, NumPy |
| Machine Learning | Scikit‑Learn |
| Boosting | XGBoost, LightGBM |
| Interpretability | SHAP, LIME |
| Visualization | Matplotlib, Seaborn |

---

---

## 📈 Expected Outcomes  
- A validated ML model capable of predicting voluntary turnover  
- A comparison of classification methods  
- SHAP‑based explanations of key attrition drivers  
- Actionable HR recommendations grounded in model insights  

---

## 👤 Author  
**Ramiro Ribadeneira**  

Toronto Metropolitan University  

Data Analytics, Big Data, and Predictive Analytics Certificate 

The Chang School of Continuing Education 

Capstone Project (2026)

---

## 📚 References  
Full APA references are included in the project design proposal.
