# Traffic Collision Analysis and Visualization
This project aims to analyze real-world traffic collision data from Ontario, uncovering patterns and predicting fatal outcomes. It utilizes machine learning models for predictions, handles missing and biased data, and delivers interactive visualizations through Power BI and an Angular-based frontend.

Table of Contents
Overview

Features

Technologies Used

Project Structure

Setup and Installation

Usage

Model Training

Visualization Dashboard

License

Overview
This project provides insights into traffic collision patterns using Ontario's public dataset. Its primary focus is on predicting fatal collisions, offering visualizations of contributing factors such as weather, time, and location.

Features
Predicts fatal traffic collisions using classification models

Handles missing data and mitigates bias during preprocessing

Power BI dashboard for detailed visual analysis

Hyperparameter tuning for optimized model performance

Technologies Used
Python: For data analysis, modeling, and preprocessing

Jupyter Notebook: For exploration and model development

Scikit-learn: Implements machine learning models (e.g., Random Forest, XGBoost, KNN)

Power BI: For creating visualization dashboards

Pandas, NumPy, Seaborn, Matplotlib: Used for data handling and exploratory data analysis (EDA)

Project Structure
bash
Copy
Edit
├── Traffic_collison.ipynb       # Jupyter notebook for the entire pipeline
├── train.csv                    # Cleaned dataset used for training         
└── powerbi/                     # Power BI dashboard files
Setup and Installation
Prerequisites
Python 3.8+

Power BI Desktop (optional, for dashboard visualization)

Installation Steps
Python environment
Run the following command to install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Navigate to the Angular frontend directory and run:

bash
Copy
Edit
cd angular-frontend
npm install
ng serve --port 4200
Usage
Run the traffic-collision.ipynb notebook to train and evaluate models.

Launch the Angular frontend to input traffic parameters and receive fatality predictions.

Open the Power BI dashboard to explore insights related to weather, road type, light conditions, and time of day.

Model Training
Addressed missing values and outliers with imputation and transformation.

Tackled class imbalance through sampling strategies.

Trained and evaluated various classification models:

Random Forest

XGBoost

K-Nearest Neighbors (KNN)

Applied hyperparameter tuning for optimal model performance.

Evaluated models using metrics like accuracy, F1-score, and confusion matrix.

Visualization Dashboard
The Power BI dashboard includes:

Heatmaps based on time and day

Breakdown of weather and lighting conditions

Trends in fatalities categorized by road surface and collision type

License
This project is licensed under the MIT License.
