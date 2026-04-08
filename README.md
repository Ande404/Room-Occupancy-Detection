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

### 1. Install dependencies

```bash
pip install -r requirements.txt
```
### 2. Run project

```bash
python scripts/run_pipeline.py
```

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
