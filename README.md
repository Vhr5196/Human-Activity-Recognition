# Human-Activity-Recognition

Human Activity Recognition (HAR) is a process of classifying activity of a person using data received from Accelerometer and Gyroscope sensor of a smartphone that is affected from human movement.Classifying the physical activities performed by a user based on accelerometer and gyroscope sensor data collected by a smartphone in the user’s pocket. The activities to be classified are: Standing, Sitting, Stairsup, StairsDown, Walking and Cycling.

## GOAL: 
The goal is to understand in detail about the working of the various classifiers on Human Activity Recognition Dataset

## Experiments:
The experiments have been carried out with a group of 25 volunteers within age brackets 19-48 years. Each person performed six activities (SITTING, STANDING, LYING, WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS). The six activities as six classes corresponds to each data point with 551 features.

## Dataset link :
https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition

## Libraries used :
Keras, Scikit-Learn, Numpy, Matplotlib and Pandas

## Approaches used:
The Approaches used are: Linear Discriminant Analyses (LDA); Multinomial Logistic Regression; Support Vector Machines (SVM) and kNN.

## Comparison:
The comparison is performed based on the confusion matrix of those classification results on the test data using the different training classifiers, presented by confusion matrices.

## Conclusion:
SVM with linear kernel approach is the best fit classifier with an accuracy of 96.4% to our dataset. It gives the best performance for all the accuracies and error rates. SVM with linear kernel being a flexible approach which is capable to reduce overfitting.



