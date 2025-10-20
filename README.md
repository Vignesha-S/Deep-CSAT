# 🧠 Deep-CSAT: Predicting Customer Satisfaction using Deep Learning

### 📋 Project Overview
Deep-CSAT is a deep learning project designed to predict **Customer Satisfaction (CSAT)** scores from customer service data.  
By leveraging historical records and service attributes, the model identifies key operational factors influencing satisfaction levels.

---

### 🎯 Objectives
- **Data Preparation:** Clean and preprocess the dataset  
- **Feature Engineering:** Derive key predictive features  
- **Model Development:** Build and train a deep neural network for CSAT prediction  
- **Evaluation:** Assess model accuracy and performance using classification metrics  
- **Insight Generation:** Identify trends and actionable factors affecting satisfaction  

---

### ⚙️ Workflow Summary
1. **Data Cleaning & Encoding:** Removed nulls, encoded categorical features, and engineered features like `response_time_mins_log`.  
2. **Imbalanced Data Handling:** Used **SMOTE** to balance underrepresented CSAT categories.  
3. **Model Training:** Built a **Deep Neural Network (ANN)** using TensorFlow/Keras.  
4. **Evaluation:** Achieved ~72.5% test accuracy.  
5. **Insights:** Found that supervisor role, sub-category type, and response time were key drivers of satisfaction.

---

### 📊 Model Performance
| Metric | Value |
|--------|--------|
| Test Accuracy | **72.5%** |
| Best Features | Supervisor, Sub-category, Response Time |
| Data Balancing | SMOTE |
| Framework | TensorFlow / Keras |

---

### 💡 Key Insights
- Faster response times significantly improve CSAT.  
- Certain issue categories (Refunds, Cancellations) correlate with lower satisfaction.  
- Supervisors and shift schedules influence response consistency and customer experience.  

---

### 🧩 Tech Stack
- **Python 3.10+**
- **TensorFlow / Keras**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**
- **NumPy, Pandas, Matplotlib, Seaborn**

---

### 📂 Repository Structure
```

Deep-CSAT/
├── eCommerce_Customer_support_data.csv
├── csat_prediction.ipynb
├── deepcsat_scaler.joblib
├── deepcsat_model.h5
├── requirements.txt
└── README.md

```

---

### 📜 License
MIT License © 2025

---

### 👤 Author
**Vignesha S**  
AI Engineer | Data Science Enthusiast
```
