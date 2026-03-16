# Fake-vs-Real-News-Analysis

Fake vs Real News Analysis

Authors: Federica Gianoglio, Nanditha Lekshmy, Esha More

GitHub Repository: https://github.com/Nanditha-Lekshmy/Fake-vs-Real-News-Analysis/

## Project Summary

This project investigates differences between fake and authentic news articles through exploratory, analytical, and predictive methods. The analysis focuses on identifying linguistic patterns, examining sentiment characteristics, and building machine learning models capable of classifying articles as fake or real.

Using a dataset of nearly 79,000 news articles, the study performs several stages of analysis including data preparation, statistical exploration, sentiment evaluation, and predictive modeling. The final stage compares the performance of multiple classification algorithms to determine the most effective model for detecting misinformation.

All three authors contributed equally to the development of the project. In the code, each cell includes the first name of the contributor responsible for that section.

## Project Workflow

The analysis is organized into four major phases: data preparation, descriptive analysis, diagnostic analysis, and predictive modeling. Visualizations are included throughout the notebook to support interpretation of the results.

* Data Cleaning and Preparation

* Initial preprocessing was performed to ensure the dataset was suitable for analysis and modeling. Key steps include:

* Removing missing values (NaN)

* Assigning appropriate column labels

* Tokenizing the article text

* Filtering out non-alphabetic characters and stop words

* Applying stemming to normalize words

## Descriptive Analysis

Basic statistical analysis was conducted to better understand the textual characteristics of the dataset. This stage includes:

* Computing statistical measures such as mean, median, standard deviation, and mode

* Examining skewness and kurtosis of the distributions

* Creating frequency distribution plots of the top 30 most common words

* Generating word clouds for the top 100 frequent terms

## Diagnostic Analysis

Further analytical methods were used to explore relationships within the data:

* Correlation analysis between variables

* Sentiment analysis to determine polarity scores of articles

* Multiple linear regression to evaluate relationships between features

## Predictive Modeling

Three supervised machine learning algorithms were trained and evaluated to classify news articles as fake or real. Both textual and numerical features were used during model training.

The models tested include:

* Support Vector Machine (SVM)

* Naive Bayes

* Logistic Regression

Model performance was compared to determine which approach provided the most accurate classification results.

## Dataset Information

The dataset used for this project contains approximately 79,000 news articles separated into two files:

* MisinfoSuperset_TRUE.csv – 34,975 articles labeled as real news

* MisinfoSuperset_FAKE.csv – 43,642 articles labeled as misinformation, propaganda, or fake news

Dataset source:
https://www.kaggle.com/datasets/stevenpeutz/misinformation-fake-news-text-dataset-79k/data

To execute the project code successfully, both datasets must be downloaded and loaded into the working environment.

## Dataset Columns

* ID -	Unique identifier assigned to each article
* text - Full textual content of the news article

## Required Libraries

The project was implemented using Python 3.x and relies on the following libraries:

* pandas – data manipulation and analysis

* numpy – numerical operations

* matplotlib – data visualization

* seaborn – statistical plotting

* nltk – natural language processing tasks

* swifter – faster execution of pandas apply functions

* wordcloud – visualization of frequent words

* scikit-learn – machine learning algorithms and evaluation metrics

* scipy – scientific computing and statistical utilities

* statsmodels – statistical modeling and regression analysis

