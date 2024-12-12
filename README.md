# Car Price Prediction Using Linear Regression and K-Nearest Neighbors

## Introduction
This repository demonstrates the implementation of **Linear Regression** and **K-Nearest Neighbors (KNN)** algorithms using the **Scikit-Learn** library to predict car prices based on various features such as mileage, age, fuel type, and more. The primary objective is to showcase machine learning techniques for regression tasks with the widely used **Car Price Dataset**.

## Description
The project involves preprocessing the **Car Price Dataset** and applying two machine learning models:
1. **Linear Regression:** For understanding the linear relationships between features and predicting prices.
2. **K-Nearest Neighbors (KNN):** For non-linear regression tasks, predicting prices based on the closest data points.

The models are evaluated for their performance, and the results are visualized to compare their effectiveness.

### Key Features:
- **Data Preprocessing:** Handles missing values, encodes categorical features, and normalizes numerical data.
- **Algorithm Implementation:** 
  - Linear Regression: Captures linear relationships in the dataset.
  - KNN: A flexible model for non-linear regression tasks.
- **Evaluation Metrics:** Uses metrics like Mean Squared Error (MSE) and R-squared to evaluate model performance.
- **Visualization:** Visualizes predictions and actual values for better insights.

## Tools and Technologies
- **Languages:** Python
- **Libraries and Frameworks:**
  - Scikit-Learn
  - Pandas
  - NumPy
  - Matplotlib and Seaborn (for visualization)

## How It Works
1. **Data Preprocessing:**
   - Load the **Car Price Dataset**.
   - Handle missing values, encode categorical features, and normalize numerical values.
2. **Model Training:**
   - Train the **Linear Regression** and **KNN** models on the processed dataset.
   - Tune hyperparameters for KNN, such as the number of neighbors.
3. **Evaluation:**
   - Evaluate model performance using metrics like MSE and R-squared.
   - Compare the performance of Linear Regression and KNN.
4. **Visualization:**
   - Plot the predicted vs actual prices for both models.
   - Analyze the results using scatter plots and residual plots.
