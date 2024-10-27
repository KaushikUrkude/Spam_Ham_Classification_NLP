
# Spam/Ham Classification using CountVectorizer

The project uses CountVectorizer, a basic NLP technique, to transform text data into numerical features suitable for machine learning algorithms. By analyzing word frequency in each message, the classifier can predict whether a message is spam or ham.



## Installation

```bash
git clone https://github.com/KaushikUrkude/Spam_Ham_Classification_NLP.git
cd Spam_Ham_Classification_NLP
```

## Dataset

**The dataset used in this project contains labeled examples of spam and ham messages.Each message is:**

1.Preprocessed for text cleaning.

2.Transformed into a numerical feature vector using CountVectorizer for use in model training.

**Common sources for datasets include:**

1.SMS Spam Collection Dataset on UCI

2.Public datasets on Kaggle
## Text Preprocessing with CountVectorizer

**CountVectorizer** is a technique that converts a collection of text documents into a matrix of token counts. Each document is represented by the frequency of each word, preparing the data for machine learning models.

Steps include:

1.Tokenizing messages.

2.Converting messages to lowercase.

3.Removing punctuation and common stopwords.

4.The CountVectorizer matrix represents each message as a vector, where each element indicates the frequency of a specific word.
