# Sentiment Analysis Project

## Overview

This project involves sentiment analysis using various machine learning classifiers such as Naive Bayes, SVM, Random Forest, Gradient Boosting, and Decision Tree. The goal is to classify movie reviews as either positive or negative based on their content.


## Dependencies

Make sure to install the required dependencies before running the code. You can use the following commands:

```bash
pip install nltk
pip install sklearn
pip install textblob

Usage

Open and run the sentiment_analysis.ipynb notebook in a Jupyter environment.
The notebook contains step-by-step instructions for loading the dataset, preprocessing the data, and training different classifiers.
The accuracy of each classifier is printed, and the best-performing model is identified.
Visualizations, such as a bar chart comparing training and testing accuracies, are included.
The confusion matrix for the best model is plotted and displayed.

Model Selection
The project compares the performance of the following classifiers:

Naive Bayes
Support Vector Machine (SVM)
Random Forest
Gradient Boosting
Decision Tree
The best model is selected based on its accuracy on the validation set.

Results
The project provides insights into the performance of different classifiers and visualizations to aid in understanding the results.

Acknowledgments
The dataset used in this project is from the review_polarity dataset available at Cornell University.