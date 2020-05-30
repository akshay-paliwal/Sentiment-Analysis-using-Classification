# Project Title
Sentiment Analysis using Classification

## Introduction
I made this Sentiment Classifier after completing my Machine Learning: Classification course on Coursera. For this project, the code was written to predict the sentiment of any review i.e if the review is POSITIVE or NEGATIVE. This code needs to process the available data to a useable format and train various classification models to predict the sentiment. Also, each model is evaluated to check the accuracy of the model.

In this project two types of features are used:
* **Bag of Words -** In this model, a text (such as a sentence or a document) is represented as the bag of its words, disregarding grammar and the order of the words. Only, the count of each word in the review matters.
* **TF-IDF -** In this model, each word of the review is associated with a weight to reflect how important a word is to a document in a collection or corpus. 

The following models are used to predict the sentiment of the review:-
* **Logistic Classifier -** It is a model to predict the class of a discrete target variable (binary or multiclass) based on a model of class probability as a logistic function of a linear combination of the features. 
* **Random Forest -** Random forests is an ensemble learning method for classification and other tasks that operate by constructing a multitude of decision trees at training time and outputting the class of a discrete target variable.
* **SVM model -** A SVM is a supervised learning model that uses classification algorithms for two-group classification problems. After giving an SVM model sets of labelled training data for each category, they're able to categorize new text.

## Install
This project requires Python 3. Also, some of the python libraries like matplotlib, NumPy, turicreate, math, etc.
Installed [Anaconda](https://www.anaconda.com/products/individual), a pre-packaged Python distribution that contains most of the necessary libraries and software for this project. 

[Turi Create](https://pypi.org/project/turicreate/) is an open-source toolset for creating Core ML models. To install turicreate following command can be used...

```!pip install turicreate ```

## Code
The code contains the following parts-
* ` Part 1` Importing the required modules and loading the data set.
* ` Part 2` Pre-processing the data to make it usable.
* ` Part 3` Implementing various Classification models, predicting the sentiment of reviews and evaluating each model.
* ` Part 4` Predicting the sentiment of the reviews provided by the user.

## Data
**SFrame** is the data structure for representing tabular data in turicreate. So, the data used for this project is a CSV file of [IMDB Review Datase](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)which is converted to an SFrame. 





