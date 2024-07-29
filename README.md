# Data Science | Internship 

# Iris Flower Classification 🌸
## Overview
The Iris flower dataset is a classic dataset introduced by the British statistician and biologist Ronald Fisher in his 1936 paper, The Use of Multiple Measurements in Taxonomic Problems. The dataset is often referred to as Anderson's Iris data set due to Edgar Anderson’s collection of the data. It consists of 150 samples from three species of Iris flowers: Iris-setosa, Iris-virginica, and Iris-versicolor. Four features were measured for each sample: sepal length, sepal width, petal length, and petal width, all in centimeters. This dataset is commonly used for classification tasks in machine learning, including support vector machines and other classification techniques.

## Objective 🎯
The objective of this project is to develop a machine learning model that can classify Iris flowers into their respective species based on their sepal and petal measurements. Using this dataset, the goal is to create a model that accurately predicts the species of Iris flowers, making it a great introductory project for classification tasks.

## Dataset 📊
The dataset used in this project is the well-known Iris dataset. It consists of the following columns:

sepal_length: Length of the sepal in cm
sepal_width: Width of the sepal in cm
petal_length: Length of the petal in cm
petal_width: Width of the petal in cm

species: The species of the Iris flower (Iris-setosa, Iris-versicolor, Iris-virginica)

## Steps

Import Libraries 📚
Read and Explore Dataset 🔍
Data Wrangling 🧹
Exploratory Data Analysis (EDA) 📈
Feature Engineering & Data Pre-processing 🛠️
Model Implementation & Evaluation 🤖

### Import Libraries

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

### Exploratory Data Analysis (EDA) 🔍
The EDA involves visualizing the data to understand the distributions and relationships between features. This includes:

Histograms of feature distributions 📊
Scatter plots of feature relationships 🌐
Pair plots and correlation heatmaps 🔥
Feature Engineering & Data Pre-processing 🛠️
Encoding Categorical Data 🔠
Data Scaling and Splitting 🧪
Model Implementation & Evaluation 🤖

### Different classification models were implemented and evaluated, including:

Logistic Regression
Decision Tree Classifier
K-Nearest Neighbors Classifier
Support Vector Machine
Gaussian Naive Bayes
Random Forest Classifier

Each model was evaluated using metrics such as accuracy, precision, recall, and confusion matrices.

## Results 📈
The models were compared based on their performance metrics. Key results include accuracy scores for each model, confusion matrices, and classification reports.
