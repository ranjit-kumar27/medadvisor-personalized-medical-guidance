# MedAdvisor – Personalized Medical Guidance System

## Overview

MedAdvisor is an AI-powered Personalized Medical Guidance System developed using Machine Learning and Flask. The system predicts possible diseases based on user symptoms and provides personalized medical guidance including:

* Disease Prediction
* Medication Suggestions
* Precaution Recommendations
* Diet Recommendations
* Workout Suggestions

The project uses a trained Support Vector Machine (SVM) model along with multiple healthcare datasets to provide intelligent symptom-based medical recommendations.

---

# Features

* Predict diseases from user symptoms
* Personalized medicine recommendations
* Health precautions and safety guidance
* Diet recommendations for predicted diseases
* Workout and fitness suggestions
* Simple and user-friendly web interface
* Machine Learning–based prediction system

---

# Tech Stack

## Frontend

* HTML
* CSS
* Bootstrap

## Backend

* Python
* Flask

## Machine Learning

* Scikit-learn
* Support Vector Machine (SVM)
* NumPy
* Pandas

---

# Project Structure

```bash
Medical Project/
│
├── main.py
├── svc.pkl
├── columns.pkl
├── label_encoder.pkl
│
├── templates/
│   └── index.html
│
├── description (1).csv
├── diets (1).csv
├── medications (1).csv
├── precautions_df (1).csv
├── workout_df (1).csv
├── Symptom-severity (1).csv
├── symtoms_df (1).csv
└── Training.csv (1).zip
```

---

# Machine Learning Model

The project uses the Support Vector Machine (SVM) algorithm for disease prediction.

## Why SVM?

* High accuracy in classification problems
* Works efficiently with multiple features
* Effective for medical prediction systems
* Handles high-dimensional symptom data effectively

The trained model is stored in:

```bash
svc.pkl
```

---

# Installation & Setup

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/medadvisor-personalized-medical-guidance.git
```

## Step 2: Navigate to Project Folder

```bash
cd medadvisor-personalized-medical-guidance
```

## Step 3: Install Dependencies

```bash
pip install flask numpy pandas scikit-learn
```

## Step 4: Run Application

```bash
python main.py
```

---

# Application Workflow

1. User enters symptoms
2. Symptoms are converted into numerical features
3. SVM model predicts the disease
4. System fetches:

   * Description
   * Precautions
   * Medications
   * Diet plans
   * Workout suggestions
5. Results are displayed on the web interface

---

# Datasets Used

The project uses multiple healthcare-related datasets including:

* Symptom dataset
* Disease description dataset
* Medication dataset
* Diet recommendation dataset
* Workout recommendation dataset
* Precaution dataset

---

# References

The following resources and datasets were used during the development of this project:

- Kaggle Medicine Recommendation Dataset  
  https://www.kaggle.com/datasets/noorsaeed/medicine-recommendation-system-dataset

- WebMD Symptom Checker  
  https://symptoms.webmd.com

- Healthline Medical Resources  
  https://www.healthline.com
