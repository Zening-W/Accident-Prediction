# road-safety
Trains a scikit learn model from the data in [fall_data.csv](fall_data.csv) and [acc_data.csv](acc_data.csv) to be able to detect if the accelerometer is dropped or in a crash.

The model to be trained is a [Gaussian Naive Bayes classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Relation_to_logistic_regression) and is written in the [nb.py](nb.py) file.

The [fall_data.csv](fall_data.csv) file and [acc_data.csv](acc_data.csv) files are created from [PHONE FALL DATA FILE.xls](PHONE%20FALL%20DATA%20FILE.xls) and [ACCIDENTAL DATA FILE.xlsx](ACCIDENTAL%20DATA%20FILE.xlsx) files.
