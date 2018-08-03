# StackOverflow_Tag_Predictor
Predicting the tag in StackOverflow queries
![StackOverflow](https://pattonwebz.info/wp-content/uploads/2017/03/stackoverflow_stickers.jpg)  

Requirements:
python-3.0
conda-2.7
numpy-1.15.0
pandas-0.23.2
sqlite-3.24.0 
sklearn-0.19.2

We can have the data from https://www.kaggle.com/stackoverflow/stacklite

In this our objective is to predict the tag with the question being asked by the user.
We used TF-IDF representation of the words and we took upto 3 grams for featurizing and then applied OnevsRest Classifier with 
Logistic Regression and SVM with hyperparameter tuning to improve micro-averaged-f1-score.
