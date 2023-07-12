# Credit Card Fraud Classification Using Statistical Methods

## Project Overview
Banks and financial institutions are consistently seeking ways to enhance their measures against credit card fraud. With scammers employing a variety of methods to illegally obtain credit card information and conduct unauthorized transactions, it is crucial for such institutions to stay one step ahead.

In this project, we examine a dataset of credit card transactions and construct predictive models to identify potentially fraudulent activities. We'll utilize the Credit Card Fraud Detection dataset from Kaggle, which encompasses credit card transactions made by European cardholders. This dataset contains a total of 284,807 transactions, 492 of which are classified as fraudulent.

To maintain confidentiality, the dataset comprises numerical input variables that have been transformed through Principal Component Analysis (PCA). The features include 'Time', 'Amount', 'V1' through 'V28', and the 'Class' variable, which indicates whether a transaction is fraudulent (1) or not (0).

## Methodology
Our project begins with exploratory data analysis (EDA) to gain deeper insights into the data. This is followed by data processing and modeling, during which we'll construct various classification models to predict instances of fraudulent transactions.

We'll employ several methods including:

- Logistic Regression
- Support Vector Machines (SVM)
- Naive Bayes
- Random Forest
- Dummy Classifier
As the dataset is heavily imbalanced, we'll also address this issue by using undersampling techniques to ensure our models can better generalize across different types of transactions.

Finally, we'll assess the performance of our models and select the most suitable one based on evaluation metrics such as AUC, precision, recall, F1-score, and accuracy.
