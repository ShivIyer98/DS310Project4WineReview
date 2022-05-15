# Introduction

In this project, you need to implement models to predict the variety of the wine based on its description/review, location, and price. This is a multi-class classification problem with 10 types of wine in total.

For this project, there are no constraints to the machine learning model. You should try to apply the models we have learned from this course so far.

You will be evaluated over the accuracy score on the private leaderboard. Note that you will not see your private leaderboard score before the submission deadline. This competition will close on December 8th, 11:59 pm.

# Suggestions

This dataset contains missing values. Consider imputing the data before training the model.

To process the text features (e.g., description in the data), you can consider using the bag of words representation (e.g., Word Counting, TFIDF). This scikit learn document is a good starting point for learning feature extraction for text.

I would probably not recommend you to directly apply deep learning models for this classification project. However, you are free to try any model you like.
