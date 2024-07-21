# Weather Type Classification

## Project Overview

This project aims to classify weather types based on various meteorological features. The dataset contains information on weather conditions with the goal of predicting the type of weather (e.g., Rainy, Cloudy, Sunny, Snowy). The project employs various machine learning algorithms to achieve this classification.

## Dataset

Title : Weather Type Classification
<br>Owner : Nikhil Narayan
<br>Link  : https://www.kaggle.com/datasets/nikhil7280/weather-type-classification
<br>Collected on 21/07/2024 at 15.13

### Features

The dataset used in this project consists of the following 10 features:

1. **Temperature**: Temperature in degrees Celsius (float64)
2. **Humidity**: Humidity percentage (int64)
3. **Wind Speed**: Wind speed in km/h (float64)
4. **Precipitation (%)**: Precipitation percentage (float64)
5. **Cloud Cover**: Cloud cover description (object) - e.g., partly cloudy, clear, overcast, cloudy
6. **Atmospheric Pressure**: Atmospheric pressure in hPa (float64)
7. **UV Index**: UV index (int64)
8. **Season**: Season of the year (object) - e.g., Winter, Spring, Summer, Autumn
9. **Visibility (km)**: Visibility distance in kilometers (float64)
10. **Location**: Location description (object) - e.g., inland, mountain, coastal

### Output

The target variable to be predicted is:

- **Weather Type**: Type of weather (object) - e.g., Rainy, Cloudy, Sunny, Snowy

## Machine Learning Models

The project explores and evaluates several machine learning algorithms, including:

1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Support Vector Machine (SVM)**
4. **Naive Bayes Classifier**
5. **Logistic Regression**
6. **Random Forest Classifier**

### Model Evaluation

Models are evaluated using metrics such as precision, recall, and F1-score. The performance of each model is visualized using bar charts to compare the metrics across different classifiers.

## Data Preprocessing

- **Categorical Features**: Categorical variables like Cloud Cover, Season, and Location are encoded using One-Hot Encoding.
- **Numerical Features**: Numerical features are scaled using Standard Scaler.
- **Target Variable**: The target variable (Weather Type) is label-encoded.

## Installation

To run this project, you'll need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib scikit-learn

