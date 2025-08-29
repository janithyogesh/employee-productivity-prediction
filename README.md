# Productivity Prediction of Garment Employees

## Project Overview

This repository contains a data science project focused on predicting the productivity of garment employees. The analysis uses the "Productivity Prediction of Garment Employees" dataset from the UCI Machine Learning Repository. The project's goal is to build a machine learning model that can classify whether a team of workers will meet their targeted productivity for a given day.

The problem, originally a regression task, was reframed as a classification task to predict a binary outcome: `1` if the team meets or exceeds its target, and `0` otherwise.

## Repository Contents

* `garments_worker_productivity.ipynb`: The main Colab notebook containing all the code for the project.
* `garments_worker_productivity.csv`: The dataset used for this analysis.

## Project Structure

The Jupyter notebook is structured into the following sections:

1.  **Introduction and Dataset Description:** An overview of the project, the dataset source, and the goal of the analysis.
2.  **Data Preprocessing:** Steps taken to clean the data, including handling missing values and data type conversions.
3.  **Exploratory Data Analysis (EDA):** Visualizations and statistics to understand the data's characteristics and relationships between features.
4.  **Feature Engineering:** The process of creating the binary target variable and preparing features for modeling.
5.  **Modeling:** Training and evaluation of two classifiers: Logistic Regression and Random Forest.
6.  **Model Improvements:** A brief discussion of how model performance could be further optimized.
7.  **Ensemble Learning:** Implementation and evaluation of a Gradient Boosting Classifier.

## Key Findings

The project compared the performance of three different classification models:

-   **Logistic Regression**
-   **Random Forest Classifier**
-   **Gradient Boosting Classifier**

The results showed that the ensemble methods, particularly the **Gradient Boosting Classifier**, significantly outperformed the simple Logistic Regression baseline. This suggests that the relationship between the features and the target variable is non-linear and complex. The Gradient Boosting model achieved the highest accuracy, making it the best-performing model for this task.

## How to Run the Notebook

To run this project on your local machine or in Google Colab, follow these steps:

1.  Clone this repository to your local machine.
2.  Ensure you have Python installed. The required libraries are listed below.
3.  Open the `garments_worker_productivity.ipynb` file in a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, or Google Colab).
4.  Run all the cells in the notebook.

### Required Libraries

You can install the necessary libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Credits

Dataset Source: UCI Machine Learning Repository: Productivity Prediction of Garment Employees