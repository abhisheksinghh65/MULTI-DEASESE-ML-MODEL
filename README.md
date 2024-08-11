# 🧑‍⚕️ Health Assistant: Multi-Disease Prediction System

Welcome to the **Health Assistant** project! This web application predicts the likelihood of three diseases using machine learning models: **Diabetes**, **Heart Disease**, and **Parkinson's Disease**. The project is built using **Streamlit** and leverages pre-trained models to provide quick and reliable predictions.

## 🚀 Features

- **Diabetes Prediction** 🩸
- **Heart Disease Prediction** ❤️
- **Parkinson's Disease Prediction** 🧠
- Simple and intuitive user interface built with Streamlit.
- Real-time predictions based on user inputs.


## 🍬 Diabetes Prediction Model
This project is part of a larger Multiple Disease Prediction System, focusing on predicting diabetes using machine learning techniques.

### 🧠 Model
- **Algorithm**: Support Vector Machine (SVM) with a linear kernel
- **Train-Test Split**: 80% training, 20% testing
### 📈 Performance
- **Training Accuracy**: 78.34%
- **Testing Accuracy**: 77.27%

## Heart Disease prediction Model
### 🧠 Model
- **Algorithm**: Logistic Regression
- **Train-Test Split**: 80% training, 20% testing
### 📈 Performance
- **Training Accuracy**: 85.12%
- **Testing Accuracy**: 81.96%

## Parkinsons Disease prediction Model
### 🧠 Model
- **Algorithm**: Support Vector Machine (SVM) with a linear kernel
- **Train-Test Split**: 80% training, 20% testing
### 📈 Performance
- **Training Accuracy**: 87.17%
- **Testing Accuracy**: 87.17%

## 📊 Usage
Open the application in your browser after running the Streamlit command.
Use the sidebar to navigate between different disease prediction pages:
Diabetes Prediction
Heart Disease Prediction
Parkinson's Disease Prediction
Enter the required details and click on the Test Result button to see the prediction.

## 🛠 Technologies Used
Python 🐍
Streamlit 🎈
Scikit-learn 📊

## 🗂 Project Structure

```bash
ML_MODEL/
├── myenv/
├── streamlit_app/
│   ├── pages/
│   │   └── app.py
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
├── train_model/
│   ├── model_diabetes.csv
│   ├── model_heart.csv
│   └── model_parkinsons.csv
└── requirements.txt
|__ diabetes.csv
|__ heart.csv
|__ parkinsons.csv
