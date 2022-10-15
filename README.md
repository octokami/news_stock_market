# Predicting stock price movements based on news messages

* Target variables: classifying news articles in order to predict whether the closing price of the day is higher (1) or lower or equal than the opening price (0).
* Dataset: Data from https://www.kaggle.com/datasets/gennadiyr/us-equities-news-data?resource=download, which has already been preprocessed to remove punctuation
    * Scope: Apple stock (AAPL) relateed news 
* Key models:
    1. Data Processing: Bag of words (BOW)
    2. Data Reduction: Random Forest Classifier
    3. Best model: GaussianNB

There are 2 main folders: model_output containing the results without sentiment analysis and model_output_sem with them.
For each classification model we present:
* The confusion matrix or error matrix, that is, the sum for each class on what was predicted against how they were classified
* Plot of the words that most influenced precision
* The best tuned model
For the Neural network model:
* The hypertuned model
* The figure evaluating the training performance
* Kt_trials folder containing information about each hypertuning trial

results.csv is the aggregation of results from all models, including the ones that did not perform as well as the top 10 presented in this report.

utils contains the .yml file to rebuild the environment.

