### Twitter-Data-Analytics

Computed the sentiment of Twitter tweets to gain insights into the Canadian 2019. Data cleaning and EDA were conducted to identify tweets relevant to specific parties. BOW, TF-IDF, and N-grams were used for model preparation. Logistic regression, KNN, SVM, and Random Forest classifiers were implemented for model results and predicting election outcomes.

The purpose of this repository is to compute the sentiment of tweets posted recently about the Canadian Elections, gain insight into the Canadian Elections, and answer the research question What public opinion on Twitter tell about the Canadian political landscape in 2019?

### BACKGROUND:

Sentiment Analysis is a branch of Natural Language Processing (NLP that allows to determine algorithmically a statement or document is “positive” or “negative.” It is a technology of increasing importance in modern society as it enables individuals and organizations to trends in public opinion by analyzing social media. Staying informed about socio-political is especially important during periods policy shifts such as election years when both electoral candidates and can benefit from sentiment analysis by appropriate changes to their campaigning and business strategies, respectively.

### REQUIREMENTS:

Numpy, Scipy, Scikit, Matplotlib, Pandas, NLTK.

### APPROACH:

Data cleaning: Design a procedure that prepares the Twitter data for analysis

Remove all HTML tags and (i.e., /<[^>]+>/)
Replace HTML character codes (i.e., &...;) with ASCII equivalent
Remove all URLs
 all in the text to lowercase
Remove all stop wordsPreserve empty tweets after pre-processing

Exploratory analysis: determine the political party of a given tweet Bag of Words, TF-IDF, N-grams

Model preparation: multiple algorithms for generic tweets (logistic regression,-NN, Naive Bayes, SVM,
