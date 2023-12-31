# Iris Flower Classification Predictor

## Project Overview

This project focuses on building a predictive model for classifying Iris flowers into different species based on their sepal and petal characteristics. The Iris flower dataset is a well-known dataset in the field of machine learning and is often used for practicing classification algorithms.

The goal of this project is to develop a robust machine learning model that can accurately classify Iris flowers into their respective species, namely:

 * Iris-setosa
 * Iris-versicolor
 * Iris-virginica
   
I provide Python code for training the model, making predictions, and evaluating the model's performance using various metrics.

## Functions and Features

### Classification_for_Flower_Predictions

The "Classification_for_Flower_Predictions" function is a comprehensive utility for performing Iris flower classification. It takes four input parameters representing sepal and petal measurements and provides two key outputs: model accuracy and predicted flower species.

### Function Workflow

The function performs the following steps in its workflow:

1.Data Loading and Cleaning:

* Load the Iris flower dataset using the Pandas library.
* Perform data cleaning to handle missing values, duplicates, or any other data quality issues.

2.Data Visualization:

* Utilize Matplotlib and Seaborn to create data visualizations, including scatter plots and pair plots. These visualizations help users understand the relationships between different features and the distribution of data points.

3.Model Training:

* Train a machine learning classifier on the cleaned dataset. The classifier's goal is to predict the species of Iris flowers based on sepal and petal measurements.

4.Making Predictions:

* Use the trained classifier to make predictions on new data. The input parameters for prediction are SepalLengthCm, SepalWidthCm, PetalLengthCm, and PetalWidthCm.

4.Model Evaluation:

* Evaluate the performance of the trained model using accuracy.

## Video Presentation

To see a demonstration of our Iris Flower Classification Predictor project in action, please watch the following video:

[Demo Video](https://youtu.be/J0X7zjQr20c)

In this video, we provide a step-by-step walkthrough of how to use our project's features, objectives, and results. Feel free to watch the video to get a better understanding of our project.

## Dataset

The dataset used for this project is the [Iris Flower Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-BD0231EN-SkillsNetwork/datasets/iris.csv), which contains measurements of 150 Iris flowers from three different species. The dataset includes four features (sepal length, sepal width, petal length, and petal width) and the target variable (species).

## Dependencies

This project requires the following Python libraries:

NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn (for visualization)

You can install these dependencies using pip:

      pip install numpy pandas scikit-learn matplotlib seaborn


## Usage

To use this project, follow these steps:

1. Ensure you have Python installed on your machine.
2. Clone the project repository to your local machine:

     ```bash
     git clone https://github.com/mominurr/Iris-Flower-Classification-Predictor.git
     cd Iris-Flower-Classification-Predictor
     python flower_classifications_predictor.py

##Author:
[Mominur Rahman](https://github.com/mominurr)
