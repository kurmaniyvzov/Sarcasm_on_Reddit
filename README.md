# Sarcasm on Reddit detection

### Project Description:
The aim of this project is to choose and train a model that will classify the comments, that was scraped from Reddit, as sarcastic and non-sarcastic. For this NLP problem the different Word embedding algorithms was used such as Word2Vec and TF-IDF. Moreover, to choose the best model for classification the Logistic Regression, SVM, Gradient Boosting, XGBoosting and LSTM Neural Networks were used.

### Requirements:
The code was written in Python, and the following libraries were used: `numpy`, `sklearn`, `pandas`, `matplotlib`, `torch`.

### Data:
`train-balanced-sarcasm.csv` - dataset that is publicly available on [kaggle.com](https://www.kaggle.com/datasets/danofer/sarcasm). The dataset contains the comments, the date when the comment was posted, subreddit and the score. All the data was gathered by Mikhail Khodak and Nikunj Saunshi and Kiran Vodrahalli for their article "A Large Self-Annotated Corpus for Sarcasm".
