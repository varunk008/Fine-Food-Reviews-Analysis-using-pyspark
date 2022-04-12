Amazon Review Prediction using Machine Learning algorithms in pyspark

Please follow this blog

Applying machine learning algorithms to very large datasets is challenging today. most of the company are using spark to analyze large data, train machine learning models, and extract information from massive datasets. in this blog, I explained all the necessary steps to build a machine learning model for text classification in pyspark.
I have used the Amazon Fine Food Review dataset. This dataset consists of reviews of fine foods from Amazon.

Objective:
[Q] How to determine if a review is positive or negative?

I have divided the classification problem into the below steps:
1. Importing Libraries
2. Exploratory Data Analysis
3. pre-processing text data

     -  Removing Punctuations,special characters, etc
     -  Performing stemming
     -  Removing Stopwords
     -  convert text into lower case 
4. Converting text data into the vector using 
     - Count Vectors
     - TF-IDF
     - Word2Vec
5. Training machine learning models using different algorithms.
     -  OneVsRest
     -  LinearSVC
     -  Naive Bayes
     -  Random Forest Classifier
     -  GBT Classifier
     -  Decision Tree Classifier
     -  Multilayer Perceptron Classifier
6. Results

