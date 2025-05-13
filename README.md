**TWITTER SENTIMRNT ANALYSIS- USING MACHINE LEARNING**
Project Overview
This project focuses on performing sentiment analysis on Twitter data using machine learning techniques in Python. The goal is to *classify tweets as either positive or negative* based on their content, allowing us to understand public sentiment on various topics.

**Key Features:-**
-Data Collection: Utilizes the Sentiment 140 dataset, which contains 1.6 million tweets, to train and evaluate the machine learning model.
Data Preprocessing: Converts textual data into a numerical format suitable for machine learning algorithms. This includes:
Removing special characters, numbers, and stop words.
Implementing stemming to reduce words to their root forms.
Model Training: Employs logistic regression as the classification model to predict tweet sentiment.
Model Evaluation: Splits the dataset into training and test sets to evaluate the model's accuracy and performance.

**Technologies Used:-**
Python,
Jupyter Notebook,
Pandas,
NLTK (Natural Language Toolkit),
Scikit-learn,

**Dataset Loading:-**
Dataset Link- [(https://www.kaggle.com/datasets/kazanova/sentiment140)]


**Usage:-**
The project includes a step-by-step guide to load the dataset, preprocess the data, train the logistic regression model, and evaluate its performance.
After training, the model can be used to predict the sentiment of new tweets.

**Most Usefull Concept:-**
 Stemming: Stemming is a natural language processing (NLP) technique used to reduce words to their root or base form, known as the "stem.
 " The purpose of stemming is to simplify the analysis of text data by consolidating different forms of a word into a single representation. 
 For example, the words "running," "runner," and "ran" can all be reduced to the root word "run."
 Implementation in the Project:-
 In this project, stemming is implemented using the **Porter Stemmer** from the NLTK (Natural Language Toolkit) library. The process involves the following steps:

1.Text Preprocessing: Before stemming, the text undergoes several preprocessing steps:
Removal of special characters, numbers, and punctuation.
Conversion of all text to lowercase to ensure uniformity.
Splitting Words: The cleaned text is split into individual words, creating a list of words from each tweet.

2.Applying Stemming: Each word in the list is processed using the Porter Stemmer. The stemming function checks if a word is not a stop word (common words that do not add significant meaning)
and then applies the stemming algorithm to reduce it to its root form.

3.Rejoining Words: After stemming, the processed words are joined back together to form the cleaned tweet text, which is then stored in a new column in the DataFrame.
 

**Conclusion:-**
This project demonstrates the application of machine learning techniques to analyze and classify sentiments in social media data, providing insights into public opinion and trends. Feel free to explore and modify the code to suit your needs!
