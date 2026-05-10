# Income Prediction System 🚀

End-to-End Machine Learning project to predict whether a person’s income is **≤50K or >50K** using multiple classification models.

---

# 📌 Overview
This project implements a full ML pipeline including:
- Data cleaning & preprocessing
- Feature engineering
- Model training & hyperparameter tuning
- Model evaluation
- Deployment using a GUI (Streamlit)

---

# 🧠 Models Used
- Decision Tree  
- Random Forest  
- Logistic Regression  
- SVM (RBF Kernel)  
- KNN  

Models were compared after tuning, with special focus on handling **imbalanced data**.

---

# ⚙️ Preprocessing & Feature Engineering
- Handled missing values and categorical noise  
- One-Hot Encoding for categorical features  
- Standard scaling for numerical features  
- Feature engineering:
  - Net Capital  
  - Work Status  
  - Capital Gain Indicator  
- Outlier handling using IQR method  

---

# 📊 Evaluation Metrics
Due to class imbalance, evaluation focused on:
- F1 Score (main metric)
- Recall
- Accuracy
- Confusion Matrix

---

# 🖥️ GUI (Streamlit App)
A simple interactive interface that allows:
- Input user data
- Select model
- Get real-time prediction

---

# 💾 Model Saving
All models are saved as full pipelines using `joblib`, including:
- Feature engineering  
- Preprocessing  
- Trained model  

---

# 🛠️ Tech Stack
- Python  
- Pandas & NumPy  
- Scikit-learn  
- Streamlit  
- Joblib  

---

# ▶️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
