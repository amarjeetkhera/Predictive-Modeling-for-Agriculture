# 🌱 Predictive Modeling for Agriculture

## 📄 Project Overview

This project is focused on building a predictive model to classify different crops based on the soil conditions. The contextual idea behind this project is to leverage data analysis and machine learning methods to help farmers choose the best crops suitable for the chemical composition of their soil. The inspiration is based on the un-guided project offered by DataCamp. Although DataCamp instructs the users to implement this project using the Sci-kit learn library for model building, in this repository a different approach has been implemented which utilises a custom-built function for the Logistic Regression model.

## 📂 Description

The dataset used this project is sourced from DataCamp. It contains information on different chemical elements which play a vital role in forming the soil composition which influences the selection of crops.
Given below is the context and Use-case description sourced from DataCamp:

![17346145983872091104595490281314](https://github.com/user-attachments/assets/b5589b06-6772-44f6-8387-0163cea123d9)

_Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints._

_Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield._

_A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for his field. They've provided you with a dataset called soil_measures.csv, which contains:_

_"N": Nitrogen content ratio in the soil_

_"P": Phosphorous content ratio in the soil_

_"K": Potassium content ratio in the soil_

_"pH" value of the soil_

_"crop": categorical values that contain various crops (target variable)._

_Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field._

_In this project a multi-class classification model will be built to predict the type of "crop" and identify the single most importance feature for predictive performance._


Total Samples: 2200

Labels: Multi-class (22 different types of crops)

Data Split: 80 (training) - 20 (testing) split.


## 📊 Key Features

- Logistic Regression model implemented entirely from scratch (without Scikit-learn or similar libraries).
- Gradient Descent optimization for weight updates.
- Softmax activation function for multi-class classification.
- Calculation of performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Feature importance analysis using mean absolute weights.
- Data visualizations:
  - Confusion Matrix
  - Feature Importance Bar Chart

## 🛠️ Tools & Technologies

Programming language: Python

Development environment: Jupyter Notebook

### Libraries:
- Core mathematical operations and array handling: `numpy`
- Data visualization: `matplotlib` & `seaborn`
- For comparison metrics like confusion matrix and accuracy score: `scikit-learn`

## 📈 Results

The Logistic Regression model achieved:

Accuracy: 88%

Precision: 87%

Recall: 89%

F1-Score: 88%
