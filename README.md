# Cardiovascular Risk Prediction
Cardiovascular disease (CVD) is a general term for conditions affecting the heart or blood vessels. It's usually associated with a build-up of fatty deposits inside the arteries (atherosclerosis) and an increased risk of blood clots. It can also be associated with damage to arteries in organs such as the brain, heart, kidneys and eyes.

## Table of Content
  * [Objective](#objective)
  * [Dataset](#dataset)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Project Structure](#project-structure)
  * [Tools Used](#tools-used)
  * [Performed Model Result](#performed-model-Result)
  * [Project Summary](#project-summary)
  * [Conclusion](#conclusion)

## Objective
The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD) or not.

## Dataset
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. These attributes are demographic, behavioral and medical risk factors. 
More details of the dataset can be found in the kaggle website.https://www.kaggle.com/datasets/captainozlem/framingham-chd-preprocessed-data#CHD_preprocessed.csv

## Technical Aspect
This project is divided into three parts.
1. Exploratry Data Analysis
      - Exploratory data analysis is an important step that starts once business hypothesis is ready. This step takes 40-50% of total project time as the model outcome depends on the quality of input data being fed to train the model. Exploratory data analysis involves data attributes identification, data preprocessing and feature engineering.
2. Feature Engineering 
      - Feature engineering is the pre-processing step of machine learning, which is used to transform raw data into features that can be used for creating a predictive model using Machine learning or statistical Modelling. Feature engineering in machine learning aims to improve the performance of models. 
2. Model Building
      - Building an ML Model requires splitting of data into two sets, such as ‘training set’ and ‘testing set’ in the ratio of 80:20 or 70:30; A set of supervised (for labelled data) and unsupervised (for unlabeled data) algorithms are available to choose from depending on the nature of input data and business outcome to predict.

## Installation
This project requires python 3.6 or any other higher versions of python.
This project need software to run this python notebook "Jupyter Notebook" or "Google colab". It is highly recommended that you install the Anaconda distribution of Python or use "Google Colab" https://colab.research.google.com/, which already has most of the above packages and more included.
 

## Project Structure
```
├── README.md
├── Dataset 
│   ├── data_cardiovascular_risk.csv
│
│
├── EDA
|   ├── Data Cleaning
│       ├── Duplicated values
│       ├── NaN/Missing values
│   ├── Numeric & Categoric features
│   ├── Treating Skewness
│   ├── Treating Outlier
│   ├── Univariate & Bivariate Analysis
│   ├── Multivariate Analysis
│
├── Feature Engineering
│   ├── Handling Multicollinerity
|       ├── Correlation
│   ├── Encoding
|       ├── Label Encoding
|       ├── One-Hot Encoding
|   ├── Feature Selection
|       ├── ExtraTree Classifier
|       ├── Fisher Score
|       ├── Chi-Square Test
|       ├── Iformation Gain
│
├── Model Processing
│   ├── Train Test Split
│   ├── Scaling - Standrdization
│   ├── Model selection
│   ├── Hyperparameter Tunning
│   ├── Model Explainability
|
│   
├── Report
├── Presentation
├── Result
└── Reference
```

## Tools Used
![image](https://user-images.githubusercontent.com/112171582/205482290-ed2f9a20-5bb6-494e-aed4-6a8fb29fdb7e.png)
