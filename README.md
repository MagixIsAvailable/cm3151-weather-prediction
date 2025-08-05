# 🌧️ Rain Prediction in Australia – CM3151 Machine Learning Coursework

This project is submitted as part of the resit coursework for CM3151 (Machine Learning) at RGU.

## 📌 Objective

To build a supervised machine learning classification model to predict whether it will rain tomorrow (`RainTomorrow`) based on historical weather data across Australia.  
The project follows a structured data science workflow from data exploration through to model evaluation and improvement.

---

## 📊 Dataset

- **Name:** Rain in Australia
- **Source:** [Kaggle - weather-dataset-rattle-package](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
- **Shape:** ~145,000 rows × 23 features
- **Target:** `RainTomorrow` – binary classification (Yes/No)

---

## 🧠 ML Techniques Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- Data Balancing (optional)
- Grid Search CV (model improvement)

---

## 🛠️ Project Structure

```bash
CM3151_WeatherPrediction/
├── weatherAUS.csv              # Dataset
├── rain_prediction.ipynb       # Jupyter Notebook (main submission)
├── README.md                   # Project documentation
└── requirements.txt            # Dependencies (optional)
