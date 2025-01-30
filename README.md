# lung-cancer-prediction

## Overview
This project explores the use of Python libraries for data visualisation, machine learning, and statistical analysis in creating predictive models.

## Problem Statement
Lung cancer is the third most common cancer across both genders in Singapore. Moreover, lung cancer incidence is expected
to rise greatly over the next decade. Hence to prevent it, we must investigate its causes by analysing factors such as age, lifestyle choices and symptoms.

The primary dataset is "lung cancer survey.csv". It is a survey dataset of individuals with or without lung cancer and their respective attributes. The data is originally retrieved from [Kaggle](https://www.kaggle.com/datasets/wajahat1064/lung-cancer-survey-data) which was in turn retrieved from an online website on lung cancer prediction systems. Thereafter, JR passed the data through a series of training models and a synthetic dataset of 10,000 observations was eventually generated.  

The schema of the dataset used is as follows:

| Column Name           | Values            | Question                                      |
|-----------------------|------------------|----------------------------------------------|
| **GENDER**           | Male=1, Female=0 | What is your gender?                         |
| **AGE**              | Age of patient   | What is your age?                            |
| **SMOKING**          | YES=1, NO=0      | Do you smoke?                                |
| **YELLOW_FINGERS**   | YES=1, NO=0      | Do you have yellow fingers?                  |
| **ANXIETY**         | YES=1, NO=0      | Do you have anxiety issues?                 |
| **PEER_PRESSURE**    | YES=1, NO=0      | Have you been pressured by your peers to smoke? |
| **CHRONIC DISEASE**  | YES=1, NO=0      | Do you suffer from any chronic disease?     |
| **FATIGUE**         | YES=1, NO=0      | Do you feel tired easily?                   |
| **ALLERGY**         | YES=1, NO=0      | Do you have any allergy?                    |
| **WHEEZING**        | YES=1, NO=0      | Do you suffer from wheezing problems?       |
| **ALCOHOL CONSUMING**| YES=1, NO=0      | Do you consume alcohol?                     |
| **COUGHING**        | YES=1, NO=0      | Do you suffer from coughing problems?       |
| **SHORTNESS OF BREATH** | YES=1, NO=0  | Do you easily get short of breath?         |
| **SWALLOWING DIFFICULTY** | YES=1, NO=0 | Do you face difficulty swallowing?         |
| **CHEST PAIN**       | YES=1, NO=0      | Do you feel any chest pain?                 |
| **LUNG_CANCER**      | YES=1, NO=0      | Do you have lung cancer?                    |


## Objectives
There are three objectives to this project:

1) Produce insightful and clear data visualisations to raise public awareness of lung cancer. These visualisations would be incorporated into a written report.
2) Create a predictive model using different machine-learning approaches to determine the likelihood of developing lung cancer.
3) Present your findings in a coherent and clear presentation.

## Methodology

For this project, we would separate into three parts as follows:

### Part 1: Data Visualisation of Public Awareness

We would use both the survey data and data extracted from the National Cancer Registry 2022 and the World Health Orgnisation data to produce data visualisations that help meet Objective 1. This would mean using packages such as Pandas, Matplotlib, and Seaborn.

These visualisations would be subsequently incorporated into a written report for public awareness. The report may use secondary information for arguments made.

### Part 2: Predictive Machine Learning

Using the survey data, we would create different machine-learning models using supervised learning methods. Model selection will based on their F1-Score, as the target variable is binary, on the same training-validation slot.

The machine learning models used are Logistic Regression, Decision Trees, K-Nearest Neighbour, and Dense Neural Networks. Where applicable, we would conduct hyperparameter tuning while training the model and conduct statistical assumptions for the best model. Through this process, we would use libraries such as Sci-kit Learn, Keras and Pandas.

The best model will be fitted into the entire "lung cancer survey.csv" and this model will then be evaluated on a new dataset called "lung cancer survey_test.csv". This is to evaluate the model on a dataset that it has never seen before. Subsequently, we would get the F1-Score of this evaluation.

### Part 3: Results Presentation

We would consolidate the findings of Part 1 and Part 2 into a coherent presentation to communicate our results effectively to stakeholders.


