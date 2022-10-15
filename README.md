# Predicting stock price movements based on news messages

* Target variables: classifying news articles in order to predict whether the closing price of the day is higher (1) or lower or equal than the opening price (0).
* Dataset: Data from https://www.kaggle.com/datasets/gennadiyr/us-equities-news-data?resource=download, which has already been preprocessed to remove punctuation
    * Scope: Apple stock (AAPL) relateed news 
* Key models:
    1. Data Processing: Bag of words (BOW)
    2. Data Reduction: Random Forest Classifier
    3. Best model: GaussianNB
