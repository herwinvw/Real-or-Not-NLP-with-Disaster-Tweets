# Real-or-Not-NLP-with-Disaster-Tweets
Real or Not? NLP with Disaster Tweets Kaggle competition from Kaggle (https://www.kaggle.com/c/nlp-getting-started/overview).

## Data Exploration
The data is analyzed to determine several cleanup and feature engineering steps: [Data exploration](explorative_analysis.ipynb).

## Baseline Model
A [random baseline model](baseline_model.ipynb) is developed to determine the minimum score. It achieves an f1-score of 0.46.

## Data cleanup
[Data cleanup](data_cleanup.ipynb)

## First simple model
A simple [bag of words](bag_of_words.ipynb) model is trained on the tweet text only. It performs surprisingly well (public score: 0.79), but seems overfitted on the data.

## Docvec model
Docvecs are learned from the tweet text and used as a feature in a classifier. [This approach](docvec.ipynb) does not outperform the bag of words model (public score: 0.75). Perhaps there is not enough data to the docvecs.

## Average wordvec model
