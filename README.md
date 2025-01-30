# lung-cancer-prediction

## Overview
This project explores the use of Python libraries for data visualisation, machine learning, and statistical analysis in creating predictive models.

## Problem Statement
Lung cancer is as serious national comcern in Singapore and it is now the third most
common cancer across both genders. lung cancer as the number o is expected
to rise greatly over the next decade. Hence, we must investigate its causes by
analysing different factors such as age, lifestyle choices and symptoms.

The primary dataset used are from a given survey data of indiviauas with or without lung cancer.

The schema of the dataset used is as follows:

| Column Name | Description |
| --- | --- |
| CustomerNo | An identification number for each unique customer |
| TransactionNo | An identification number for each unique transaction |
| Date | The date on which the transaction was made |
| ProductNo | An (alpha)numeric code for each unique product |
| ProductName | Name of Product |
| Price | Unit Price of the specific product |
| Quantity | Quantity purchased for a single product within the transaction
| Country | Country where the customer is based in

## Objectives
There are three objectives to this project:

1) Produce isnisghtful and clear data visualisations to raise public awareness of lung cancer. This visualisations would be incorporated in a written report.
2) Create a predictive model using diffferent machine learning approaches to determine the likelihood of developing lung cancer.
3) Present your findings in a coherent and clear presentation.

## Methodology

For this project, we would seperate into three parts as follows:

### Part 1: Data Visualtion of Public Awareness

We would use both the survey data and data extracted from the National Cancer Survey to produce data visualisations that help meet Objective 1. This would mean using packages such as Pandas, Matplotlib, and Seaborn.These visualstions would be subsequently incorporated in a written report for public awareness. The report my use secodnary information for agruments made.

### Part 2: Predictive Machine Learning

Using the survey data, we would create different machine learning models using supervised learning methods. We would do model selection based on their F1-Score on the save training-valisation solot as the target variable is binary. We would then use the best model and train it on the enture data set. The machine learning models to be used are Logistic Regression, Decision Trees, K-Nearest Neighbour, and Dense Neural Networks. Where applicable, we would condict hyperparemter tuning while trainng the model and conduct statistical assumptions for the best model.
Through this process, we would use libraries such as Sci-kit Learn,Keras and Pandas.

### Part 3: Results Presentation

We would consolidate the findings or Part 1 and Part 2 into a coherent presentation so as to communicate our results effectively for stakeho.


