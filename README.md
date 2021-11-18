# Fake_News_Classifier
Build a system to identify unreliable news articles

## 1. Business Problem:

#### 1.1 Problem Statemtent:
Build a system to identify unreliable news articles

#### 1.2 Dataset Description:
1. [Dataset is taken from Kaggle](https://www.kaggle.com/c/fake-news)

2. `train.csv:` A full training dataset with the following attributes:
    - **id:** unique id for a news article
    - **title:** the title of a news article
    - **author:** author of the news article
    - **text:** the text of the article; could be incomplete
    - **label:** a label that marks the article as potentially unreliable
        - **1:** Fake news
        - **0:** Real news

3. `test.csv:` A testing training dataset with all the same attributes at train.csv without the label.

## 2. Data Preparation:
- Remove empty text news
- Checking duplicates news and remove it
- 

## 3. Text Preprocessing:
- Convert everything to lowercase
- Contraction mapping
- Eliminate punctuations and special characters
- Remove stopwords
- Stemming

## 4. Vectorization:
1. TF-IDF Vectorizer:

## 5. Evolution:
![ev](https://user-images.githubusercontent.com/42543380/142424563-6cf30f89-dc8f-4117-a96f-3cb2db91fae5.PNG)

![lg](https://user-images.githubusercontent.com/42543380/142424648-9766986e-6c45-47d0-ba1d-538cf899e22f.PNG)

## 6. Conclusion:
Logistic regression with TF-IDF model is giving good result.

