# IMDBReviewsSentimentAnalysis

This project is a sentiment analysis of 50k movie reviews on Internet Movie Database (IMDB) and the dataset is available on: [IMDB dataset of 50k movie reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

[SentimentAnalysis_IMDBReviews.ipynb](https://github.com/AnitaSoroush/IMDBReviewsSentimentAnalysis/blob/main/SentimentAnalysis_IMDBReviews.ipynb) consists of the following steps:

> **Preprocessing**: 
> - Lowercasting
> - Removing URLs
> - Removing Punctuations
> - Removing Stopwords
> - Handling Emogies
> - stemming

> **vectorizing using TF-IDF**

> **building, training and testing the model using 3 methods**:
> - Logistic Regression
> - Random Forest Classifier
> - Decision Tree Classifier

At the end, **Logistic Regression** turned out to be the best model, with **accuracy score of 0.8941**
