# Finding Donors for *CharityML*

I help to identify potential donors for a charity organization.

### Overview

Company reports that most of its donors have income above $50,000. The goal then is to find the best model to identify these individuals using US census data. To achieve this, I explore supervised learning algorithms.

### Methods

* Logistic regression
* Naive Bayes classifier
* Random forest

### Technologies

* Python
* Matplotlib
* NumPy
* Pandas
* Scikit-learn

## How to use

To take a look at the notebook, just click on `finding-donors.ipynb` and it should open automatically.

Alternatively you can download the file `finding-donors.html` and open it in your browser to see the results.

## Dataset

The dataset for the project comes from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). It was modified a bit by removing missing data and a variable `fnlwgt`.

#### Size

The dataset contains 32 000 observations, each one having 13 features and an outcome variable `income`. Each record describes a single person.
