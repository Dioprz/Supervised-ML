# Overview of Machine Learning

## What is Machine Learning

>Field that gives computers the ability to learn without being explicitly programmed.
>
>Arthur Samuel


## Main types of machine learning

- Supervised learning
- Unsupervised learning
- Recommender systems
- Reinforcement learning

## Supervised learning

The algorithm learns by being trained with previously labeled data, so they can learn which is the most likely tag *Y* (the label) for a given input *X* (the feature vector). In other words, the algorithm learns from being given with the *right answers*

Supervised learning have two types of applications:

### Regression

This type of model tries to approximate the most probable label in a set of **infinite** possible labels. This can be approached by using things such as lines, polynomials, functions, etc.

#### Example

- An algorithm made to predict the price of a house, where the number can be any real number.

- Predict a number. This has infinitely many possible outputs
### Classification

On the other hand, a classification algorithm attempts to give a *Y* label to an *X* input, but where the *Y* label can only belong to a finite set of possible labels, usually called categories or classes.

#### Example

- Classification of cancer tumors on the *benign* or *malignant* categories.

- Predict categories. Have a *finite* number of possible outputs

## Unsupervised learning

This kind of learning model does not require to be given with previously labeled data.
Instead, it attempts to extract interesting things or structure in the data.

### Clustering

This model work by *grouping* or *clustering* sets of similar or related data. The algorithm itself is capable to find patterns on the data to make these distinctions.

#### Example

- Google News algorithm clusters similar news by similarities on, for example, title words, dates, etc.

- Grouping customers by interest while trying to provide a service.


### Anomaly detection

Models specialized on find unusual data points or events.
It is very useful on the financial system to detect fraud, unusual events or transactions.

### Dimensionality reduction

These are used to compress large data sets by reducing the number of features while preserving the maximum amount of information.

