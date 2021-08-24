# Supervised Machine Learning Homework - Predicting Credit Risk

* [General info](#general-info)
* [Predictions] (#predictions)
* [Technologies](#technologies)
* [Results](#results)
* [References](#references)


## General info
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. I will be using an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020).

## Predictions
Before running the unscaled data on the logisticRegression and Random Forest Classifier models, I believe that Logistic Regression will not be a good model for these data sets because of the differing variables.

## Technologies
* GitBash
* Jupyter Notebook
* pd.get_dummies()
* LogisticRegression
* RandomForestClassifier

## Results
Based on the training and testing score comparison, the LogisticRegression model makes better predictions after the data has been scaled, featured selected and then scaled again.


## References

LendingClub (2019-2020) _Loan Stats_. Retrieved from: [https://resources.lendingclub.com/](https://resources.lendingclub.com/)

- - -

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
