# Predictive Maintenance System using Apache Spark

This repository hosts a **mini-project** focused on building a **Predictive Maintenance System**, leveraging **Apache Spark** for scalable data processing and analysis. The system aims to **predict potential equipment failures** and recommend **maintenance actions**, thereby reducing downtime and optimizing operational efficiency.

---

## Overview

The project is developed as part of a **Scalable-Distributed-Computing** course at **VNUHCM - International University**. It demonstrates an **end-to-end solution** for predictive maintenance, from **data processing** and **model training** to **alert generation** and **user interface presentation**.

---

## Features

- **Data Processing & Analysis**  
  Utilizes Apache Spark for efficient handling and analysis of large datasets related to equipment performance and historical failures.

- **Predictive Modeling**  
  Implements machine learning models (e.g., **XGBoost**) to predict equipment failures.

- **Alert System**  
  Generates alerts based on predicted failures, enabling proactive intervention.

- **Maintenance Recommendation**  
  Provides recommendations for maintenance actions to prevent impending failures.

- **User Interface (UI)**  
  A front-end interface for visualizing data, model predictions, and managing alerts/recommendations.

---

## Technologies Used

- **Apache Spark**: For distributed data processing and analytics  
- **Python**: Primary programming language for development  
- **Jupyter Notebook**: For data exploration, model prototyping, and analysis  
- **XGBoost**: A gradient boosting framework, likely used for the predictive model (`xgb_model.joblib`)

---

## Project Structure

```text
.
├── Alert System/
├── Data Processing & Analysis/
├── Maintenance recommendation/
├── Predictive-Maintenance-System-using-Apache-Spark/
├── UI/
└── xgb_model.joblib
