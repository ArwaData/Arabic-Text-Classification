## 1.1. Problem 
Newspapers and news are an important part of our day, with them we know the weather, political and 
economic news that affect our country and our neighboring countries, and from them, we know the latest 
news of the issues that are interested in them, such as the Palestine issue and other important issues, and the 
news is not limited to that only, but there is a side It is entertaining, such as football news and sports. 
Due to the multiplicity and variety of news categories and their abundance, we found the problem of 
arranging and classifying them, as the news classification affects many things, including its arrangement in 
newspapers, the distribution and classification of news by section and importance, and other matters that 
affect customers and their reading of it.

## 1.2. Aim
The project aims to classify the data to help people access the News easily and in less time by searching 
the name of the interesting news. At the end of the report, all data will be correctly categorized for 40 goals 
to help easy search.

## 1.3. Project steps
The project will start with the NLP Pipeline: 
We start with Text cleaning which is cleaning the data by removing all extra space and repeated 
Characters. After that the pre-processing, for example: remove punctuations remove Tashkeel, 
Normalization, remove stop words, remove numbers also Tokenization and Stemming. Then the feature 
engineering, we added some features which are word density and sentence density. After all the previous 
steps we did the word embedding, we use N-grams, Aravec, TF-IDF to train it with models, In the 
modeling, we use SVM, Logistic regression, KNN. In the end, we evaluate the models with accuracy, 
Precision, Recall, and F-score.

## 2. Dataset
The data that we were dealt with is a group of data containing 23,000 news items in the Arabic 
language 15 thousand news for training and 8 thousand news for testing), classified according to 
their titles. It consists of two columns (Text and category) as shown in (figure:1). The “category” 
column contains 40 different classifications, including (sports, music, economics, and others). we 
will be using it to analyze the news and to know its correct category.
Data Description
Text: News in the Arabic language. 
Category: News Category

## 3. Text Cleaning and Preprocessing
We use CAMeL Tools for pre-processing, which is a collection of open-source tools for Arabic natural 
language processing in Python developed by the CAMeL Lab at New York University Abu Dhabi. 
CAMeL

## 4. Feature Engineering
• TF IDF
• N-Gram
• AraVec

## 5. Modeling
• KNN
• SVM
• Logistic Regression














