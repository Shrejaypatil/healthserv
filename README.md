# 🏥 HealthServ - AI-Powered Disease Prediction Platform

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Flask](https://img.shields.io/badge/Flask-2.0.3-green.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Sklearn-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

HealthServ is an AI-powered web application that leverages machine learning to predict various health conditions including cancer, diabetes, heart disease, kidney disease, liver disease, and Parkinson’s. The platform is built using Flask and integrates several pre-trained machine learning models to provide quick and reliable health assessments.

## 📝 Features
- **Disease Prediction**: Predicts the likelihood of multiple health conditions using advanced ML models.
- **User-Friendly Interface**: Clean and intuitive UI for easy navigation.
- **Secure Login**: User authentication with secure login and registration system.
- **Responsive Design**: Fully responsive interface accessible across devices.

## 📂 Project Structure
```plaintext
healthserv-main/
│
├── app.py                        # Main Flask application
├── requirements.txt              # Python dependencies
├── Procfile.txt                  # Deployment configurations (Heroku)
├── ML Models/                    # Pre-trained machine learning models
│   ├── cancer.pkl
│   ├── diabetes.pkl
│   ├── heartPKL.pkl
│   ├── kidneyPKL.pkl
│   ├── liver.pkl
│   └── parkinsons.pkl
├── templates/                    # HTML templates
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── ...
├── static/                       # Static assets (images, CSS, JS)
│   ├── css/
│   ├── img/
│   └── vendor/
└── remotemysql_com.sql           # SQL script for database setup
```

🚀 Getting Started
Prerequisites
Python 3.8+
Flask
Scikit-learn
Virtual environment (recommended)


The project is a health service platform, including machine learning models for predicting diseases (cancer, diabetes, heart conditions, kidney issues, liver problems, Parkinson's) along with various static assets and HTML templates.


✨ Thank you for using HealthServ! Your health, our priority. ✨
