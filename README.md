# Servo Motor Performance Prediction

## Overview
This project focuses on predicting the performance of servo motors based on various factors such as motor type, screw type, P-gain, and V-gain using machine learning regression models. The dataset used in this project contains observations of servo motor performance metrics.

## Table of Contents
- [Project Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#eda)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Contributing](#contributing)

## Dataset
The dataset (`servo.csv`) consists of the following columns:-

- **Motor**: Type of motor ('A', 'B', 'C', 'D', 'E')
- **Screw**: Type of screw ('A', 'B', 'C', 'D', 'E')
- **Pgain**: P-gain value (integer)
- **Vgain**: V-gain value (integer)
- **Class**: Performance class (integer)

## Dependencies
This project requires the following dependencies:-

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install these dependencies using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
## Installation
To run the project locally, follow these steps:

Clone the repository:

```bash
git clone https://github.com/your-username/servo-motor-prediction.git
```
Navigate to the project directory:

```bash
cd servo-motor-prediction
```
Ensure all dependencies are installed (see Dependencies).

## Usage
To use the project, follow these steps:-

- Ensure you have Python and the required libraries installed.
- Load the servo.csv dataset.
- Run the main script or Jupyter notebook for EDA and model training.
- Explore different models and evaluate their performance.

## Exploratory Data Analysis (EDA)
Explore the dataset to understand its structure and relationships between variables. Visualizations such as histograms, scatter plots, and heatmaps are used to gain insights into the data.

## Machine Learning Models
Train and evaluate different regression models:-

- Linear Regression
- Ridge Regression
- Decision Tree Regression

## Evaluation Metrics
The performance of models is evaluated using Mean Squared Error (MSE), which measures the average squared difference between predicted and actual values. Lower MSE indicates better model performance.

MSE Results:-

- Linear Regression: 196.13
- Ridge Regression: 195.34
- Decision Tree Regression: 282.28

Based on MSE values, linear regression and ridge regression perform similarly and outperform decision tree regression.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please create a pull request or open an issue in the GitHub repository.
