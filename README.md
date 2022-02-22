# GiveMeSomeCredit

How to build a classification model to predict the probability that somebody will experience financial distress in the next two years.

Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions. For markets and society to function, individuals and companies need access to credit.

Credit scoring algorithms, which make a guess at the probability of default, are the methods banks use to determine whether or not a loan should be granted by predicting the probability that somebody will experience financial distress in the next two years.

The goal is to build a model that can be used to help make the best financial decisions.

You can download the dataset for this tutorial https://www.kaggle.com/c/give-me-some-credit-20210326/data. Make sure to have the following libraries installed before getting started: pandas, numpy, matplotlib, seaborn, scikit-learn.

I started by printing a concise summary about a DataFrame including the index dtype and column dtypes, non-null values and memory usage.

 I will try to choose a model that can predict well financial distress in the next two years( target) based on the dataset I have.
 Because SeriousDlqin2yrs(target) is a discrete value, I decided to choose some classifier for this dataset like: LogisticRegression,DecisionTreeClassifier,KNeighborsClassifier,DecisionTreeClassifier(). I applied some feature engineering to my datasets like standardizing variables to get them around the same scale.
 The purpose was to improve the performance of the classifier with the new dataset that I have obtained after getting the features around the same scale. I applied cross-validation, which means evaluating classifier performance.
 I choose LogisticRegression classifier for this dataset.
 I train the dataset and have a logistic regression model.
I applied a confusion matrix that is used to describe the performance of a classifier on a set of test data for which the target test dataset are known.



![Opera Snapshot_2022-02-22_115541_github com](https://user-images.githubusercontent.com/30430563/155108213-e9a48890-8618-430b-9dad-12afd0ae39e5.png)
![Opera Snapshot_2022-02-22_115602_github com](https://user-images.githubusercontent.com/30430563/155108233-fbe24fa2-86e5-4b40-8f0b-65c601383761.png)
![Opera Snapshot_2022![Opera Snapshot_2022-02-22_115638_github com](https://user-images.githubusercontent.com/30430563/155108255-e18829bd-f5d0-4293-bd9d-567a4de84a92.png)
-02-22_115618_github com](https://user-images.githubusercontent.com/30430563/155108240-6146f11d-1660-431c-b566-ca71bba4ecb3.png)
