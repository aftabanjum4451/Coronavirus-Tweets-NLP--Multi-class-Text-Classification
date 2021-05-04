# Coronavirus-tweets-NLP---Multi-Text-Classification
The project is about multi classification problem, the data set contained the raw tweets provide by different age group of people. This repository contain the code for pre-processing and applying machine learning techniques to predict sentiments of the user.
## Dataset
(https://www.kaggle.com/datatattle/covid-19-nlp-text-classification)

## Libraries Needed
- sklearn
- numpy
- pandas
- matplotlib
- seaborn
- nltk
- keras
- gensim
- glob
- re

## Description 
In this work, the project is consisting of three variants. After downloading the data from Kaggle I performed the data analysis and data pre-processing. The data pre-processing module include, Lemmatization, stop words and punctuation removal.

## variant 1
The performance of several ML Classifiers is tested:
- **Naive Bayes** 
- **Ada boost (AB)**
- **Gradient Boosting Classifier (GBC)**
- **Random Forest (RF)**

Among those RF and GBC perfume well on this data set. Then I optimized the **hyper-parameters** of RF by using Randomized Search CV.

## variant 2
- [x] In the 2nd variant I used **Deep Learning model (Feed Forward Neural Network)** rather than ML Models. From the graphical illustration of some data analysis techniques, we can see the data set also fall in data imbalance category. In-order to overcome this issue I used the class weights technique. At the end I designed the neural network architecture and trained the model and listed the classification report to see the performance of the model 

## variant 3
In the 3rd variant I did another experiment rather than combining the similar classes into single class that I was doing in the above variants. Instead, I used them as a separate class and trained the deep leering model and check the performance of the model.

## How to Run The Code
All the code and comments are listed the jupyter notbook (NLP-covid-19 -Text Classification.ipynb)


