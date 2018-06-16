# Python for classification and sentiment analysis

Code from two master classes I gave at the Big Data Toronto 2018 conference.

## Classification task: [PythonDataScience.ipynb](./PythonDataScience.ipynb)

This notebook shows a basic pipeline of data analysis:
* Loading data
* Exploring data
* Running a logistic regression classifier.

It uses [data from sensors inside a building](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+) to predict whether the building is occupied.


## Sentiment analysis and natural language processing: [NLP.ipynb](./NLP.ipynb)

This notebook performs sentiment analysis of movie reviews. It performs the entire analysis and focuses on steps that set natural language processing apart from other machine learning tasks:
* Tokenization
* Stemming
* Text to features conversion

The notebook uses SVM classifier, together with a random forest to elicit which features (words) are most predictive of positive and negative sentiment.

A [dataset of labeled IMDB reviews](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences) is used.
