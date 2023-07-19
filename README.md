Sentiment Analysis for Amazon Alexa Reviews

This repository contains code for sentiment analysis of Amazon Alexa product reviews using three different classification algorithms: Logistic Regression, Naive Bayes, and a hybrid approach. 
The goal of this project was to predict the sentiment (positive or negative) expressed in the reviews and achieve high test accuracy.

DATA:

The dataset used in this project consists of a large collection of Amazon Alexa product reviews, including corresponding sentiment labels (positive/negative). 
The data was preprocessed to remove noise and irrelevant information.

APPROACH:

-Logistic Regression: We implemented the logistic regression algorithm using scikit-learn's LogisticRegression module. 
The features were extracted using a bag-of-words representation, and the model was trained on the training set.

-Naive Bayes: The Naive Bayes algorithm was implemented using scikit-learn's MultinomialNB class. 
We utilized the same bag-of-words representation for feature extraction and trained the model on the same training set.

-Hybrid Approach: We explored a hybrid approach that combined the predictions from both the logistic regression and Naive Bayes models. The final sentiment label was determined based on a voting mechanism.
Results

After extensive experimentation and hyperparameter tuning, we achieved a test accuracy of 92%-94% for both logistic regression and Naive Bayes models. The hybrid approach showed promising results, improving accuracy to 94%. We evaluated the models using various metrics such as precision, recall, and F1-score, and provided the results in the Jupyter notebook.

USAGE:

To run the sentiment analysis on your own dataset, follow the instructions in the Jupyter notebook. Make sure to have the required dependencies installed, such as scikit-learn, pandas, and numpy. The dataset should be formatted similarly to the one provided in the data/ directory.

CONCLUSION:

This project demonstrates the effectiveness of logistic regression and Naive Bayes algorithms in sentiment analysis for Amazon Alexa reviews. The hybrid approach further enhances the accuracy by leveraging the strengths of both models. Users can build upon this work to develop more sophisticated sentiment analysis models for different product categories or domains.

Feel free to contribute to this project by suggesting improvements or implementing other state-of-the-art algorithms for sentiment analysis. Happy analyzing!


