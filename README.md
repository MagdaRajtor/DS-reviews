# DS-reviews
Distributional semantics project on Allegro Reviews

The aim of this project was to compare how well 3 classifiers perform on a well-known Polish dataset for sentiment analysis - more than 11k product reviews from Allegro, marked with max. 5 stars (https://github.com/allegro/klejbenchmark-allegroreviews). The tested models were:
* KNN classifier with TF-IDF
* fastText
* BERT

I compared the obtained accuracies and the inter-rater reliability of the models. All the results are presented in the main notebook.

What I learned:
* identifying and dealing with missing, duplicated and non-informative data
* transforming data to fit different models
* testing multiple training procedures and hyperparameters
* investigating problematic inputs for the models to classify
