# Climate Change Tweet Classifier 
This repository belongs to JHB_ss3_classification team. It contains notebooks which were used to create classification models that can be used to classify climate change tweets into different classes.

The structure of the notebook is as follows:

#### 1  Background

#### 2  Introduction
Thus, the aim of this project is to build a classification model that can predict which category a tweet falls into. Since seeing that this project is focused on climate change, the categories are Pro (i.e. supports the belief in man-made climate change), Anti (does not support the belief in man-made climate change), Neutral (is neither for or against the belief in climate change) and Factual news.

#### 3  Libraries
##### standard libraries

pandas

numpy 

##### plotting libraries

matplotlib

wordcloud

seaborn

##### text analysis libraries

re

spacy

string

emoji

##### model building and valuation libraries

sklearn

nltk

#### 4  Data
The collection of this data was funded by a Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo. The dataset aggregates tweets pertaining to climate change collected between Apr 27, 2015 and Feb 21, 2018. In total, 43943 tweets were collected.
The training data is categorised into four classes: 
2	News: the tweet links to factual news about climate change
1	Pro: the tweet supports the belief of man-made climate change
0	Neutral: the tweet neither supports nor refutes the belief of man-made climate change
-1	Anti: the tweet does not believe in man-made climate change


#### 5  Exploratory Data Analysis
Visualisations were done to understand the characteristics of the data. Some preprocessing was used on the data

#### 6  Modeling
A Term Frequency Inverse Document Frequency Vectorizer was used to convert the text into numbers. 
Multiple classification machine learning models were tested (Logistic regression, Linear SVC, SVC, KNearest Neighbors, Multinomial Naive Bayes, Complement Naive Bayes and Decision Tree). Ensemble methods were also tested (RandomForest, Votingclassifier and BaggingClassifier). 

#### 7  Balancing the data
Three balancing approaches (upsampling,downsampling,SMOTE) were tested as there was a class imbalance in the data. 

#### 8  Results

#### 9  Conclusion
