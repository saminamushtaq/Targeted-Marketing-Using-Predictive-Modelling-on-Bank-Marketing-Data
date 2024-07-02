# Targeted Marketing Using Predictive Modelling on Bank Marketing Data

## Overview

Welcome to the GitHub repository for the project **Targeted Marketing Using Predictive Modelling on Bank Marketing Data**. This project aims to leverage supervised machine learning techniques to analyze customer data from a direct marketing campaign conducted by a Portuguese banking institution. The goal is to predict customer responses to marketing offers and identify significant factors that influence acceptance. This repository contains all the necessary files, scripts, and documentation to understand and reproduce the project.

## Repository Structure

The repository is organized as follows:

- **data/**: This directory contains the dataset used for the project. Please note that the actual dataset is not included in the repository due to size constraints. You can download it from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).
- **notebooks/**: Jupyter notebooks used for data exploration, preprocessing, model building, and evaluation. Each notebook is named according to the specific task it performs.
- **reports/**: Contains the final project report, literature review, and any other related documentation.
- **figures/**: Visualizations and plots generated during the data analysis and modeling process.
- **models/**: Serialized machine learning models (in `.pkl` format) that have been trained and evaluated.
- **README.md**: This file, providing an overview of the project and guidance for users.

### Data

1. **Download the Dataset**: Download the Bank Marketing dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).
2. **Place the Dataset**: Place the downloaded dataset (`bank-full.csv`) into the `data/` directory.

## Project Workflow

The project workflow consists of the following main stages:

1. **Data Exploration**: Understanding the dataset, exploring statistical properties, and visualizing distributions.
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and normalizing numerical features.
3. **Feature Selection**: Identifying significant features that influence customer decisions.
4. **Model Building**: Training and evaluating three supervised learning models: Logistic Regression, Decision Tree, and Random Forest.
5. **Model Comparison**: Comparing the models based on evaluation metrics to identify the best-performing model.
6. **Reporting**: Documenting the entire process, findings, and final recommendations in a comprehensive report.
