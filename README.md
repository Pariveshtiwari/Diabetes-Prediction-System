# 🩺 Diabetes Prediction System

An AI-powered web application for predicting diabetes risk using machine learning.
The model analyzes key health metrics and outputs a prediction to help with early risk assessment.

---

## 🚀 Features

* Machine learning–based risk prediction
* Clean and interactive UI built with Streamlit
* Real-time input evaluation
* Data processing and model training pipeline
* Exported trained model for reuse

---

## 📂 Project Structure

```
📁 Diabetes Prediction
│── app.py                   # Streamlit web app
│── diabetes_model.pkl       # Saved ML model
│── diabetes.csv             # Dataset
│── requirements.txt         # Dependencies
│── venv/                    # Virtual environment (ignored)
└── README.md
```

---

## 🧠 Model Details

* Algorithm: **Random Forest Classifier / SVM / (your choice)**
* Frameworks used:

  * NumPy
  * Pandas
  * Scikit-learn
  * Joblib

Dataset used: **PIMA Indians Diabetes Dataset**

---

## 🏗️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```

### 1️⃣ Create virtual environment

```bash
python -m venv venv
```

Activate:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🧾 Training the Model (Optional)

If using notebook:

```bash
python diabetes_prediction.py
```

This generates:

```
diabetes_model.pkl
```

---

## 🌐 Run the Application

Launch Streamlit app:

```bash
streamlit run app.py
```

Open browser at:

```
http://localhost:8501
```

---

## 📊 Input Parameters

The model accepts the following fields:

* Pregnancies
* Glucose Level
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

---

## 📦 Requirements

Listed in `requirements.txt`:

```
streamlit
pandas
numpy
scikit-learn
plotly
joblib
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit PRs.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgements

* Dataset: UCI Machine Learning Repository
* Tools used: Python, Scikit-learn, Streamlit, Plotly

---

Made with ❤️ by **Parivesh Tiwari**
