# Sparkfiy Churn Prediction

## Table of Contents
- [Installation](#Installation)
- [Project Motivation](#Project-Motivation)
- [File Description](#File-Description)
- [Results](#Results)
- [Licensing, Authors, Acknowledgements](#Licensing,-Authors,-Acknowledgements)

## Installation

To run this project, make sure you have the following libraries installed:

- NumPy
- Pandas
- Seaborn
- Matplotlib
- PySpark SQL
- PySpark ML

No additional installations beyond the Anaconda distribution of Python and Jupyter notebooks are required.

## Project Overview

For this project, I focused on predicting customer churn for a fictional music streaming company called Sparkify. The key steps involved were:

1. **Data Loading and Cleaning**: I worked with a small subset of the full dataset (128MB) to understand and clean the data for analysis. This subset was a representation of a much larger dataset (12GB).

2. **Exploratory Data Analysis (EDA)**: EDA was conducted to gain insights into the data and identify features that would be crucial for predicting churn. This phase involved understanding customer behavior and interactions with the Sparkify app.

3. **Feature Engineering**: I created new features that would be utilized in the modeling process. This step involved transforming and engineering the data to extract meaningful insights.

4. **Modeling with Machine Learning Algorithms**: I applied various machine learning algorithms including Logistic Regression, Random Forest, Gradient Boosted Trees, Linear SVM, and Naive Bayes to predict customer churn.

5. **Model Evaluation and Tuning**: The models were evaluated using metrics like accuracy and F1 score. The Random Forest model was further fine-tuned to optimize its performance.

Overall, this project aimed to develop an effective churn prediction model for Sparkify, which would ultimately help in retaining valuable customers.

## File Description
You can find the exploratory notebook and its corresponding HTML file. The notebook contains detailed explanations in markdown cells to showcase the step-by-step process of predicting churn.

## Results
The main findings of the code can be found at the post available [here]([https://medium.com/@althorman/what-is-the-overall-diversity-profile-of-the-organization-f4eaf1280492](https://medium.com/@althorman/revitalizing-customer-engagement-predicting-churn-with-pyspark-fa90dba28c3e))

## Licensing, Authors, Acknowledgements
I would like to acknowledge Udacity for providing the project idea and workspace.
