# iris-flower-classification
The goal of this project is to create a machine learning model to classify the species for iris flower given its features (sepal lentgh, sepal width, petal length, petal width).


## Software and Libraries
* Anaconda
* Python 3+ version
* Numpy
* Pandas
* Matplotlib
* Scikit-Learn

## Dataset
The iris dataset can be downloaded from the [UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/Iris).

## Approach

After analyzing and visualizing the data, I have created Logistic Regression, KNearest Neighbor, Decision Tree, Naive Bayes and Support Vector Machine machine learning models. To evaluate these machine learning models, I have used KFold cross-validation technique to split the data into train and test set, and accuracy score performance metric.

After evaluating all these machine learning models, I see that Support Vector Machine gives best accuracy (93.33%) on our test set. So I chose Support Vector Machine as my final model and again trained it on whole dataset.
