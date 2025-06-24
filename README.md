# ⚡ Machine Learning–Enabled Analysis of On-the-Road EV Charging Infrastructure

### 📊 Predicting Accessibility and Optimizing Deployment
## 📝 Project Overview

This project leverages Machine Learning and Data Analysis techniques to evaluate the accessibility of Electric Vehicle (EV) charging infrastructure and propose optimized deployment strategies. With the rapid global adoption of EVs, ensuring that charging stations are publicly accessible and strategically located is critical for supporting sustainable transportation.

Our focus is to:

- ✅ Analyze the current EV charging station dataset  
- ✅ Predict the accessibility status (Public vs Restricted) using classification models  
- ✅ Generate data-driven insights for optimizing future EV infrastructure deployment  

---

## 💡 Business Impact

This project provides actionable insights for:

- ✔ **Government & Policy Makers**: Identify underserved regions with limited public access to charging stations, supporting evidence-based infrastructure investment.  
- ✔ **EV Infrastructure Providers**: Optimize placement of new charging stations to maximize accessibility and meet growing EV demand.  
- ✔ **Sustainability Initiatives**: Contribute to reducing range anxiety, encouraging EV adoption, and advancing environmental goals.  
- ✔ **Data-Driven Decision Making**: Empower stakeholders with geospatial visualizations and machine learning predictions to guide infrastructure planning.  

---

## 🛠️ Key Components

- ✅ Data Cleaning & Preprocessing  
- ✅ Exploratory Data Analysis (EDA) with professional visualizations  
- ✅ Geospatial mapping of station locations and accessibility gaps  
- ✅ Classification Models:
  - Random Forest  
  - XGBoost  
  - Logistic Regression  
- ✅ Model Performance Comparison  
- ✅ Business insights to guide optimal EV charging station deployment  

---

## 📊 Model Performance Comparison

The following classification models were used to predict the accessibility (Public vs Restricted) of EV charging stations:

| Model               | Accuracy | Precision (Public) | Recall (Public) | F1-Score (Public) |
|---------------------|----------|--------------------|-----------------|-------------------|
| Random Forest       | **86.09%** | 0.88              | 0.90            | 0.89              |
| XGBoost             | **86.32%** | 0.87              | 0.92            | 0.89              |
| Logistic Regression | 81.63%   | 0.83              | 0.88            | 0.86              |

### 📌 Summary:

- Both **Random Forest** and **XGBoost** provided strong performance, with XGBoost slightly outperforming in recall for public stations.  
- **Logistic Regression**, while interpretable, showed lower accuracy, confirming the advantage of tree-based models for this complex problem.  

---

## 📦 Technologies Used

- Python (Pandas, NumPy, Scikit-learn)  
- XGBoost  
- Seaborn, Matplotlib, Plotly, Folium for Visualizations  
- Jupyter Notebook  
- Machine Learning Classification Algorithms  

---

## 🌍 Future Enhancements

- Incorporating traffic and EV adoption rate data for more advanced deployment recommendations  
- Predictive modeling for optimal locations of new stations using clustering & optimization algorithms  
- Web dashboard for interactive visualization and decision support  


