# Predicting Cooling System Power Consumption using SLR and MLR

This repository contains an analysis of IoT sensor data, focusing on implementing and comparing simple linear regression and multilinear regression models. The goal is to understand the dataset features, choose appropriate models, and evaluate them using a metric that aligns with the company's requirements.

## Steps

### 1. Importing the Dataset

- The dataset is imported into a Pandas dataframe for further analysis and model training.

### 2. Examining Dataset Features

- A detailed examination of the dataset features is performed to identify categorical and continuous variables.

### 3. Creating a Pairplot

- A pairplot is generated for the dataset to visualize relationships between different features and observe any patterns.

### 4. Dropping Categorical Variables

- Categorical independent variables are dropped from the dataset to prepare it for regression modeling.

### 5. Simple and Multilinear Regression Models

- A simple linear regression model is implemented using only the 'Temperature' feature to address the company's preference for minimizing computational power.
- A multilinear regression model is then implemented using all the features obtained after step 4.

### 6. Metric Selection

- To address the company's concern about noisy sensor readings, a metric that provides a solid baseline understanding of the average error magnitude without excessively penalizing large errors is chosen. The selected metric aligns with scenarios where all errors are treated equally and the influence of large errors is not disproportionately impactful.

## Getting Started

To run the analysis and regression models locally, follow these steps:
Clone this repository:

   ```bash
   git clone https://github.com/mohammedbilalkhan/predict-the-Cooling-System-Power-Consumption-using-using-MLR.git
   ```
