# Room Occupancy Prediction (PySpark)

A Big Data–driven machine learning project for predicting room occupancy using environmental sensor data (temperature, humidity, light, CO₂).

Built using PySpark to demonstrate scalable data processing, distributed computation, and real-world smart building applications.

## Features

- Data processing with PySpark
- Exploratory Data Analysis (EDA)
- Machine learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation (Accuracy, F1 Score)
- Big Data scaling experiments
- Simulated large-scale dataset processing

##  Project Structure

```
├── data/ # raw and processed datasets
├── notebooks/ # exploratory and modeling notebooks
├── src/ # reusable project code
├── models/ # saved trained models
├── reports/ # figures and outputs
├── scripts/ # runnable pipeline scripts
├── README.md
├── requirements.txt
└── .gitignore
```

##  Setup

### 1. Open any of the notebooks in Google Colab

### 2. Generate GitHub Token

Go to https://github.com/settings/personal-access-tokens
Create a new fine grained token
- Default settings should be fine
Save off the token for later

### 3. Fetch your Google Drive path to the Google Drive folder

Should be something like "Spring 2026/CIS 5570/Big-data-group-1/Room-Occupancy-Detection/"

### 4. Define your Google Colab secrets

BIG_DATA_TOKEN {GitHub Token}
GIT_NAME {Your Full Name}
GIT_EMAIL {Your Email}
BIG_DATA_PATH /content/drive/MyDrive + {Your Google Drive path to the shared drive}

### 5. If you swap notebooks you will need to re-enable these secrets

## Dataset

UCI Occupancy Detection Dataset:
https://archive-beta.ics.uci.edu/dataset/357/occupancy+detection

## Goal

Predict whether a room is occupied using sensor readings and demonstrate how distributed systems like Spark can scale to real-world smart building scenarios.

## Team
- Andrew Luwaga
- Prince Kwarteng Amaning
- Spencer Novaco
- Israel Sanchez
