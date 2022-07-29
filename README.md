# Predicting Bulldozer price using machine learning 

This project is about using various python-based machine learning libraries in an attempt to building a machine learning model capable of predicting the sale price of bulldozers.

We are going to take the following approach :

1. Problem Definition 
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definiftion

> How well can we predict the future sale price of bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

## 2. Data

The data is downloaded from the kaggle Bluebook for Bulldozers competition.
https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are three main datasets : 

 * Train.csv is the training set, which contains data through the end of 2011.
 * Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this   set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
 * Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1,     2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evaluation

> The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on evaluation in this project check :
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

**Note : The goal for most regression evaluation metrics is to minimize error. For example our goal for this project will be to buil machine learning model that minimises RMSLE.**


## 4. Features

Kaggle provides a data dictionary detailing all of the features of the dataset.
You can view the data dictionary in https://www.kaggle.com/c/bluebook-for-bulldozers/data
Or with docs.googl on https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing
