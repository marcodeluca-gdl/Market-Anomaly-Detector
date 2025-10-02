# Early Warning System – Financial Anomaly Detection

## Overview
This repository implements a **Financial Early Warning System** using advanced machine learning techniques.  
The project focuses on detecting anomalies in **macroeconomic and financial time-series data**, with a particular emphasis on handling sequential patterns and identifying outliers that may indicate financial stress.  

By combining anomaly detection models with explainability techniques, the system provides insights into **risk-on vs. risk-off market regimes**, supporting decision-making and risk management.

---

## Features
- **Anomaly Detection**: Identifies abnormal patterns in financial time-series data.  
- **Deep Learning Models**: Implements Autoencoders and LSTM Autoencoders for sequential anomaly detection.  
- **Benchmark & Traditional Models**: Includes Multivariate Gaussian, Random Forest, and Elliptic Envelope methods for comparison.  
- **Explainability**: Supports **LIME** (local) and **feature perturbation** (global) interpretability.  
- **Visualization Tools**: Uses **UMAP** for dimensionality reduction and market regime visualization (Up vs. Down anomalies).  
- **Customizable Pipelines**: Pre-built training and evaluation pipelines with hyperparameter tuning (Optuna).  

---

## Prerequisites
Before running the project, ensure you have the following installed:

- Python 3.x  
- Required libraries (listed in `requirements.txt`)  
- **Main Notebook**: `Anomaly_Detection_Code.ipynb` – where models are trained, evaluated, and tested  
- **Dataset**: `Dataset.xlsx` – contains the macroeconomic indices and anomaly labels used in this project  
- `README.md` – this documentation  

---

## Project Structure
