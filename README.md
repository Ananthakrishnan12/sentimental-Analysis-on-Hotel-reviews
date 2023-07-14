# Sentimental Analysis on Hotel Reviews::
Abstarct: With the development of e-commerce, a large number of hotel reviews have been produced. According to the short text features of hotel reviews, sentiment classification method based on emotion dictionary needs a lot of emotional database resources, while machine learning method needs complex artificial design features and feature extraction process. In this model, long short term memory is proposed. The text classification algorithm is used to analyze the sentiment tendency. Firstly, Data cleaned Text are used to process the short comment text into the LSTM network, and dropout algorithm is added to prevent over fitting to get the final classification model, Using the unique characteristics of short-term memory of LSTM network, it has achieved a good effect on sentiment classification of hotel reviews.

# To install Required Dependency:
Type pip install -r requirnments.txt 

 # Steps which are Implemented in this Model:
1.Data collection (https://www.kaggle.com/code/jonathanoheix/sentiment-analysis-with-hotel-reviews/input)

2.Data Description

3.Data Preprocessing: a) check duplicates in the data b) cleaning /?@ symbol form the URL

4.Data Transformation: a) Converting Text into Numerical using Tokenization

5.Model Training: a) Logistic Regression b) Random Forest Classifier

6.Evaluation Metrics: a)ConfusionMatrix,precision score,recall score,accuracy score

7.convert to h5 file.

8.Prediction.