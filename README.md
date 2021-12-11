# WeatherPrediction

This is the final project for the course of Artificial Intelligence(Fall-2021). This project is implemented by Naresh Panguluri and Siva Sai Parchuri.

## Requirements
Codes are run on Windows. It is based on Python 3.6. Required packages are stated below.

- numpy
- pandas
- sklearn

Install the packages by below way

pip install - <<package>>

## Pipeline for quick start.
All raw data are in Archive_data.csv , Latest_data.csv where it is used to split data into Train and Test data.

Or you want to download the dataset by yourself, then you can go to https://challenger.ai/competition/wf2018. to downlowd 2 datasets (You can switch to English from top-right corner):

**Train Models**
We used DecisionTreeRegressor machine learning algorithms to train the data set.

## What is Decision tree
  
Decision tree is one of the well known and powerful supervised machine learning algorithms that can be used for classification and regression problems. The model is based on decision rules extracted from the training data. In regression problem, the model uses the value instead of class and mean squared error is used to for a decision accuracy

## How it works
  
This is a tree-structured classifier with three types of nodes. The root node is the starting node that represents the entire sample and can be further divided into  nodes. Internal nodes represent the characteristics of the dataset, and  branches represent  decision rules. Finally, the leaf node represents the result. This algorithm is very helpful in solving decision-related problems.

At a given data point, it goes through the  tree  answering true / false questions completely until it reaches the leaf node. The final prediction is the average of the values of the dependent variables for that particular leaf node. Through a few iterations, the tree can predict the appropriate value for the data point.

The advantages of decision trees are that they are easy to understand, require less data cleansing, non-linearity does not affect model performance, and the number of hyperparameters to adjust is close to zero.

## How this Algorithm used in project
 
- Preparing the data
- Training the Decision Tree Regression model on the training set
- Predicting and accuracy check
- Comparing the Real Values with Predicted Values
