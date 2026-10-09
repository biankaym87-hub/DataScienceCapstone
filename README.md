# SpaceX Falcon 9 First-Stage Landing Prediction

## Project Overview

This project investigates whether SpaceX Falcon 9 first-stage booster landings can be predicted using historical launch data and machine learning.

Completed as the capstone project for the IBM Data Science Professional Certificate, this project applies the data science workflow from data collection and exploratory analysis through interactive visualization and predictive modeling.

## Objectives

- Collect launch data using the SpaceX REST API and web scraping.
- Clean, transform, and prepare data for analysis.
- Explore launch trends and relationships using Python, SQL, and data visualization.
- Build an interactive dashboard to explore launch outcomes by launch site and payload mass.
- Train and evaluate machine learning classification models to predict first-stage landing success.

## Project Workflow

### 1. Data Collection
Collected SpaceX launch data through the REST API and extracted additional information through web scraping.

### 2. Data Wrangling
Cleaned and prepared datasets for exploratory analysis and predictive modeling.

### 3. Exploratory Data Analysis (EDA)
Used Python visualizations and SQL queries to investigate launch outcomes, payloads, and launch-site patterns.

### 4. Interactive Dashboard
Developed a Plotly Dash application with interactive filters and visualizations to explore launch outcomes by launch site and payload mass.

### 5. Predictive Analysis
Trained and evaluated four classification algorithms:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

All four models achieved **83.33% accuracy on the held-out test set**. The Decision Tree achieved the highest cross-validation score among the models in this experiment.

## Repository Structure

- `notebooks/` — Jupyter notebooks covering data collection, web scraping, data wrangling, SQL, exploratory analysis, launch-site mapping, and machine learning.
- `data/` — Datasets used for analysis and dashboard development.
- `screenshots/` — Screenshots and visual evidence of the project.
- `spacex-dash-app.py` — Python source code for the interactive dashboard.

## Tools and Technologies

Python · Pandas · NumPy · SQL · Scikit-learn · Plotly · Dash · Folium · Jupyter Notebook · REST APIs · Web Scraping

## Key Takeaway

This project demonstrates an end-to-end data science workflow, combining data collection, data preparation, exploratory analysis, interactive visualization, and machine learning model evaluation to investigate SpaceX Falcon 9 landing outcomes.

---

*Completed as part of the IBM Data Science Professional Certificate.*
