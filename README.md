# Disaster Tweet Classification

This repository contains a small natural language processing project based on the Kaggle competition Natural Language Processing with Disaster Tweets. The goal is to classify tweets as disaster related or non disaster related.

## Overview

The project builds a text classification pipeline that predicts whether a tweet describes a real disaster. The workflow includes data cleaning, feature engineering with TF IDF, model training with logistic regression, evaluation, and generation of a Kaggle submission file.

The detailed description, code listings, figures, and results are documented in the PDF report.

## Repository structure

reports  
Disaster_Tweet_Classification_Report.pdf  

results  
submission.csv  

data  
Placeholder only. The original Kaggle datasets (train.csv and test.csv) are not included because of size and licensing restrictions.

## Method summary

Text data is cleaned by filling missing keywords and locations, removing URLs and punctuation, normalizing whitespace, and converting all text to lowercase. TF IDF is used to convert the tweet text into numerical features using the most frequent terms.

A logistic regression classifier is trained on the TF IDF features to distinguish disaster tweets from non disaster tweets. Model performance is evaluated using accuracy, the classification report, and the confusion matrix.

## Notes

The original code was executed in a notebook environment, and the full pipeline is preserved in the PDF report rather than in a separate .ipynb file. This repository serves as a record of the project report and the final submission file.

## Author

Hsiang Chen Yeh
