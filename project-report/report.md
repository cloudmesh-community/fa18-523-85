# Analytics in Consumer Behaviors in Black Friday with TensorFlow :hand: fa18-523-85

:o: format not followed

Bo Li
Indiana University Bloomington
1130 N Union Ct
Bloomington, Indiana
bl15@iu.edu

| github: [:cloud:](https://github.com/cloudmesh-community/fa18-523-83/blob/master/project-report/report.md)


## Abstract

As internet developed, online shopping has become part of our daily life. Black Friday- a traditional deal day, has also transformed as a big day for online shopping. The internet retailers, such Amazon, also developed their specific strategy for the combat in online shopping, Amazon Prime Day. The developed internet techniques allow us collect and store the trading data, which could be the most valuable materials for researching customer behaviors. In this article, we get the dataset of trading data in Black Friday and use TensorFlow to analysis the data in different dimensions. The dataset has several features, some of them are valuable for the research and some are not, some meaningful insights are behind the dataset, by using TensorFlow, we are able to explore the dataset in details with models.

## Keywords

Behavior big data, human behavior, TensorFlow, data mining, deep learning
 
## Introduction

Behavioral big data (BBD) refers to very large and rich multidimensional data sets on human and social behaviors, actions, and interactions, which have become available to companies, governments, and researchers. A growing number of researchers in social science and management fields acquire and analyze BBD for the purpose of extracting knowledge and scientific discoveries [1]. Besides, the online retailers also want to figure out the profound meanings behind the consumer’s actions. So the behavioral big data comes across with research area and industry area, which results in different research methods. We use the methods in research area to analysis the dataset with specific models designed to the dataset from Kaggle.

Why we use big data method to conduct the analytics? The answer lies on the character of the real dataset generated in the real trading system. The system records the deal with some specific fields, which could be some information of price, time, discount, product information, product status, etc. The user behavior could also be recorded such as the action of adding to list, the time between order to payment, etc. If a user has the habit of adding many products to the list but only buy a few of them, you may observe the data and draw the conclusion that the user is rational and could hardly be affected by the advertisement. But if you have huge amount of data, maybe it is real time data, the only way to picture those consumers is establishing models and define the features, then use the big data methods to research them. 




## Data Description 

The dataset here is a sample of the transactions made in a retail store. The store wants to know better the customer purchase behavior against different products. Specifically, here the problem is a regression problem where we are trying to predict the dependent variable (the amount of purchase) with the help of the information contained in the other variables.

Classification problem can also be settled in this dataset since several variables are categorical, and some other approaches could be "Predicting the age of the consumer" or even "Predict the category of goods bought". This dataset is also particularly convenient for clustering and maybe find different clusters of consumers within it [2].

## Technologies

TensorFlow is a framework to perform computation very efficiently, and it can tap into the GPU (Graphics Processor Unit) in order too speed it up even further. This will make a huge effect as we shall see shortly. TensorFlow can be controlled by a simple Python API, which we will be using in this Article [3].

Tensorflow is one of the widely used libraries for implementing Machine learning and other algorithms involving large number of mathematical operations. Tensorflow was developed by Google and it’s one of the most popular Machine Learning libraries on GitHub. Google uses Tensorflow for implementing Machine learning in almost all applications. For example, if you are using Google photos or Google voice search then you are using Tensorflow models indirectly, they work on large clusters of Google hardware and are powerful in perceptual tasks [4].

## Algorithms and Methology


### knn

In pattern recognition, the k-nearest neighbors algorithm (k-NN) is a non-parametric method used for classification and regression [5]. In both cases, the input consists of the k closest training examples in the feature space. The output depends on whether k-NN is used for classification or regression:
*	In k-NN classification, the output is a class membership. An object is classified by a majority vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
* In k-NN regression, the output is the property value for the object. This value is the average of the values of its k nearest neighbors.
k-NN is a type of instance-based learning, or lazy learning, where the function is only approximated locally and all computation is deferred until classification. The k-NN algorithm is among the simplest of all machine learning algorithms.

### Naive Bayes Classifier

In machine learning, naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naive) independence assumptions between the features.

Naive Bayes classifiers are highly scalable, requiring a number of parameters linear in the number of variables (features/predictors) in a learning problem. Maximum-likelihood training can be done by evaluating a closed-form expression, which takes linear time, rather than by expensive iterative approximation as used for many other types of classifiers [6].

## Data Analytics

### Data Cleaning

### Data Exploration and Processing

### Data Analysis

### Data Visualization 


## Conclusion

The conclusion drawn by the previous analytics, which could be the picture of owned consumers, the predict of the consumer’s preferences.

## Limitations

The limitations in the analytics caused by the selection of research method, algorithms, models or the character of the dataset.



## Reference

:o: will be supplemented and transferred to bibtex

* [1] Shmueli, G. (2017). Research dilemmas with behavioral big data. Big Data, 5(2), 98.
* [2] https://www.kaggle.com/mehdidag/black-friday/home
* [3] https://hackernoon.com/introduction-of-tensorflow-with-python-f4a9624f2ab2
* [4] https://towardsdatascience.com/a-beginner-introduction-to-tensorflow-part-1-6d139e038278
* [5] https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm
* [6] https://en.wikipedia.org/wiki/Naive_Bayes_classifier
