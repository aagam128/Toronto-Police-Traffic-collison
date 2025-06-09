# Traffic Collision Analysis and Visualization

This project analyzes real-world traffic collision data from Ontario, aiming to uncover patterns and predict fatal outcomes. It leverages machine learning models for prediction, handles missing and biased data, and provides interactive visualizations through Power BI and an Angular-based frontend.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Visualization Dashboard](#visualization-dashboard)
- [License](#license)

---

## Overview
This project provides insights into traffic collision patterns using Ontario's public dataset. The focus is on predicting fatal collisions, with visualizations that show contributing factors such as weather, time of day, and location. By analyzing these factors, the goal is to uncover key insights to improve traffic safety and prevent fatal accidents.

---

## Features
- **Predict Fatal Collisions**: Utilizes classification models to predict fatal traffic collisions.
- **Data Handling**: Addresses missing data and mitigates bias during preprocessing.
- **Power BI Dashboard**: Provides interactive and detailed visual analysis of traffic data.
- **Hyperparameter Tuning**: Optimizes machine learning models for better performance.

---

## Technologies Used
- **Python**: Used for data analysis, modeling, and preprocessing.
- **Jupyter Notebook**: Used for exploration, model development, and experimentation.
- **Scikit-learn**: Implements machine learning models such as Random Forest, XGBoost, and KNN.
- **Power BI**: Creates interactive and detailed visual dashboards for data analysis.
- **Pandas, NumPy, Seaborn, Matplotlib**: Essential libraries for data handling and exploratory data analysis (EDA).

---

## Setup and Installation

### Prerequisites
- **Python 3.8+**
- **Angular CLI**
- **Power BI Desktop** (Optional, only required for dashboard visualization)


## Usage 
Run the Notebook:

Open the traffic-collision.ipynb notebook to train and evaluate the models.

Launch the Angular Frontend:

Use the Angular frontend to input traffic parameters and receive fatality predictions.

Explore Power BI Dashboard:

Open the Power BI dashboard to analyze trends by weather, road type, lighting conditions, and time of day.

## Model Training
Data Cleaning:

Missing values and outliers were handled using imputation and transformation methods.

Addressing Class Imbalance:

The class imbalance was tackled using various sampling strategies to ensure balanced training.

Trained Models:

Random Forest

XGBoost

K-Nearest Neighbors (KNN)

Hyperparameter Tuning:

Performed hyperparameter tuning to achieve the best model performance.

Model Evaluation:

Evaluated the models using accuracy, F1-score, and confusion matrix.



## Power Bi 
Visualization Dashboard
The Power BI report includes:

Heatmaps by time and day
Weather and lighting condition breakdowns
Fatality trends by road surface and collision type
