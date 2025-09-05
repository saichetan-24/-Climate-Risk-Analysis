# 🌍 Climate Risk Analysis – Rainfall & Water Resource Project

This repository contains my Week 1 and Week 2 projects for **Climate Disaster Management**, focused on analyzing **rainfall patterns** and **water resource quality**.

---

## 📂 Week 1 – Exploratory Data Analysis (EDA)

**Tasks Completed:**
- Loaded rainfall and water quality datasets.
- Performed initial cleaning (encoding issues, missing values).
- Conducted **Exploratory Data Analysis**:
  - Rainfall patterns across states and months.
  - Annual rainfall distribution.
  - Seasonal rainfall trends.
  - Water quality parameter overview (pH, BOD, Nitrate, Coliform levels).
- Visualized results using **Matplotlib** and **Seaborn**.

📊 **Key Insights:**
- North-Eastern states show the highest annual rainfall.
- Clear seasonal spikes during **June–September** monsoon.
- Water resource datasets highlight pollution indicators in some states.

---

## 📂 Week 2 – Data Transformation & Feature Selection

**Tasks Completed:**
- **Data Transformation:**
  - Merged rainfall and water quality datasets by `STATE`.
  - Cleaned missing/invalid values.
  - Scaled numeric features using `StandardScaler`.
- **Feature Selection:**
  - Applied `SelectKBest (f_regression)` to identify top factors.
  - Visualized most important features influencing rainfall.

📊 **Key Insights:**
- Certain water quality parameters (pH, Dissolved Oxygen, BOD, Nitrate) show moderate correlation with rainfall.
- Dataset is now ready for predictive modeling in upcoming weeks.

---

## 📌 How to Navigate
- `Week1/` → Jupyter Notebook with rainfall & water EDA.  
- `Week2/` → Jupyter Notebook with data transformation + feature selection.  

---

## 🚀 Next Steps (Week 3 Preview)
- Build predictive models to analyze the relationship between rainfall and water resource parameters.  
- Compare model performances (Regression, Random Forest, etc.).  
