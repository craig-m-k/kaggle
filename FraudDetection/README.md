# Credit Card Fraud Detection

[This](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset contains a PCA transformed
record of credit card transactions where 0.172% are fraudulent. The overall goal is to detect the fraudulent transactions. 

Because the fraudulent transaction make up a tiny portion of the data, the data set is highly imbalanced.  One must be careful using the usual classification metrics on such data sets. The purpose of this notebook is to explore custom training metrics in LightGBM and Keras that are well suited to imbalanced data.
