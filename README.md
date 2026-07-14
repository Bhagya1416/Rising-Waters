# 🌊 Rising Waters: Flood Risk Prediction System

## Overview

Rising Waters is a Machine Learning-based Flood Risk Prediction System that predicts the likelihood of flooding using weather-related data. The application helps demonstrate how machine learning can support early flood risk assessment through a simple web interface.

## Features

- Predicts flood risk using weather parameters
- Flask-based web application
- Compares multiple Machine Learning algorithms
- Automatically selects the best-performing model
- Simple and user-friendly interface

## Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib
- HTML
- CSS

## Machine Learning Models

The project evaluates multiple classification algorithms:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- XGBoost

The best-performing model is saved and used for prediction in the Flask application.

## Input Features

- Annual Rainfall
- Cloud Visibility
- Seasonal Rainfall

# Home Page

The home page provides an intuitive interface for users to access the Flood Risk Prediction System and enter weather-related parameters.

<p align="center">
  <img src="5. Project development phase/Output Images/home-page.png" width="700"/>
</p>

---

# Prediction Form

Users enter weather-related parameters such as annual rainfall, cloud visibility, and seasonal rainfall to predict the likelihood of flooding.

<p align="center">
  <img src="5. Project development phase/Output Images/prediction-form.png" width="700"/>
</p>

---

# Prediction Result

The application analyzes the input data using the trained machine learning model and displays the predicted flood risk based on the provided values.

<p align="center">
  <img src="5. Project development phase/Output Images/prediction-result.png" width="700"/>
</p>

---

## Demo Video

🎥 **Project Demo:** [Watch Demo Video](https://drive.google.com/file/d/1q9LbigeDHZ7A8307QUIjbj2azmB1Rvt8/view?usp=sharing)

## Project Structure

```
Rising Waters/
│
├── 1. Brainstorming & Ideation phase/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project development phase/
├── 6. Project testing/
├── 7. Project documentation/
└── 8. Project Demonstration/
```

## Installation

```bash
git clone https://github.com/Bhagya1416/Rising-Waters.git

cd Rising-Waters/5.\ Project\ development\ phase

pip install -r requirements.txt

python train_model.py

python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

## License

This project was developed as part of the APSCHE Skill Wallet Internship Program in collaboration with SmartBridge for educational and academic purposes.
