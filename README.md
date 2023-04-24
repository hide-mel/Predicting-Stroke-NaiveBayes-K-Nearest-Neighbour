# Predicting-Stroke-NaiveBayes-K-Nearest-Neighbour
 
Project: Naive Bayes and K-Nearest Neighbour for Predicting Stroke

# Overview:
In this project, I will implement Naive Bayes and K-Nearest Neighbour (K-NN) classifiers. I will explore inner workings and evaluate behavior on a data set of stroke prediction, and on this basis respond to some conceptual questions.

# Implementation:
I implement my Naive Bayes classifier from scratch. I use Python libraries for implementing K-NN, evaluation metrics, procedures and data processing.
I have function called preprocess(), which opens the data file, and converts it into a usable format. It  also define the following functions:
• split_data(), where I split our data sets into a training set and a hold-out test set.
• train(), where I build Naive Bayes and K-NN classifiers from the training data. I can create train our data as I answer the related question.
• predict(), where I use a trained model to predict a class for the test data. I can also do prediction as I answer the related question.
• evaluate(),where I will output the accuracy of our classifiers, or sufficient information so that it can be easily calculated by hand.

# Packages:
I utilise the packages to the fol-lowing packages in this project:
• pandas to read, split and preprocess the data
• sklearn to develop K-NN model and evaluate models
• numpy to implement scientific computing
• math to access to the mathematical functions
• matplotlib to create plots and visualizations

# Data:
For this project, I have adapted the Stroke data that have been used for stroke prediction [1], available online at (https://data.mendeley.com/datasets/x8ygrw87jw/1):
Some critical information:
1. File name: stroke_update.csv
2. 2740 instances
3. 10 attributes that include numeric and nominal attributes. The attributes avg_glucose_- level, bmi and age are numeric. the rest of attributes are nominal.
4. The file stroke_features.txt explains each attribute
5. 2 classes, corresponding to the stroke outcomes: {0: No stroke, 1: Having stroke}


## Question 1
a Explore the data and summarise different aspects of the data. Can you see any interesting characteristic in features, classes or categories? What is the main issue with the data? Considering the issue, how would the Naive Bayes classifier work on this data? Discuss your answer based on the Naive Bayes’ formulation [2]. 
b Is accuracy an appropriate metric to evaluate the models created for this data? Justify your answer. Explain which metric(s) would be more appropriate, and contrast their utility against accuracy. [no programming required] 

## Question 2
a Explain the independence assumption underlying Naive Bayes. What are the advantages and disadvantages of this assumption? Elaborate your answers using the features of the provided data. [no programming required] 
b Implement the Naive Bayes classifier. You need to decide how you are going to apply Naive Bayes for nominal and numeric attributes. You can combine both Gaussian and Categorical Naive Bayes (option 1) or just using Categorical Naive Bayes (option 2). Ex- plain your decision.
For Categorical Naive Bayes, you can choose either epsilon or Laplace smoothing for this calculation. Evaluate the classifier using accuracy and appropriate metric(s) on test data. Explain your observations on how the classifiers have performed based on the met- ric(s). Discuss the performance of the classifiers in comparison with the Zero-R baseline.
c Explain the difference between epsilon and Laplace smoothing. [no programming required] 

## Question 3
a Implement the K-NN classifier, and find the optimal value for K. 
b Based on the obtained value for K in question 4 (a), evaluate the classifier using accuracy and chosen metric(s) on test data. Explain your observations on how the classifiers have performed based on the metric(s). Discuss the performance of the classifiers in compari- son with the Zero- R baseline.
c Compare the classifiers (Naive Bayes and K-NN) based on metrics’ results. Provide a comparatory discussion on the results. [no programming required] 
