# 🎓 Student Performance Prediction System — Samsung Innovation Campus Project

This project predicts **student academic performance (Low / Medium / High)** using **Machine Learning (Supervised Learning — Classification)**.  
The goal of the system is to identify students who may need academic support early and improve the overall learning outcome.

---

## 🚀 Project Features
✔ Machine Learning model trained on **500 student records**  
✔ **Logistic Regression** selected after model comparison  
✔ **95% Test Accuracy** — no overfitting / underfitting  
✔ **Deployed using Streamlit** for real-time prediction  
✔ Clean and production-ready folder structure  

---

## 📂 Folder Structure
student_performance_project/
├── app/
│   └── streamlit_app.py
├── data/
│   └── raw/student_performance_500.csv
├── models/
│   ├── best_model.joblib
│   ├── scaler.joblib
│   └── encoder.joblib
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_model_training.ipynb
├── README.md
└── requirements.txt


**🚀 How to Run the Project (Very Simple)**

1️⃣ Open PowerShell / Command Prompt

2️⃣ Go to the project folder:

cd D:\student_performance_project


3️⃣ Activate virtual environment (if you are using venv):

.\venv\Scripts\activate


4️⃣ Install required libraries:

pip install -r requirements.txt


5️⃣ Run the Streamlit app:

streamlit run app/streamlit_app.py