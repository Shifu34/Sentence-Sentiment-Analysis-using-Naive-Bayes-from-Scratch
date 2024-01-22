<H1 align="center">Sentence Sentiment Analysis using Naive Bayes from Scratch</H1>
In this repository you will get the sentence sentiment analysis using naive baye's which is created from scratch.
I will guide you through this code implementation step by step. 
# Steps:
- Import necessary libraries
- Initilize your vocabulary, positive and negative vocabularies.
- Lemmetize your vocabularies using the WordNetLemmatizer. Basic Code for WordNetLemmatizer is:

```
from nltk.stem import WordNetLemmatizer
nltk.download("wordnet")
lem = WordNetLemmatizer()
```
- Now making Naive Bayes from scratch. It consist of three functions which are
  1. probability Calculator
  2. Predict
  3. Display
 
# 1. Probability Calculator
probability_calculator() is basically getting test list and then calculating the negative and positive probablity and storing it.

# 2. Predict
predict() is predicting the positive/negative sentiment of the sentence. It also print negative for negative sentence and positive for positive probability.

# 3. Display
display() function is basically displaying positive and negative probabilities.
