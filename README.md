# Credit Card Fraud Classification Using Statistical Methods

## Project Overview
Banks and financial institutions are greatly concerned about the occurrence of credit card fraud. Scammers employ diverse methods to illicitly obtain credit card details and conduct unauthorized transactions. This undertaking involves examining a dataset comprising credit card transactions and constructing predictive models to identify fraudulent activities.

We will utilize the Credit Card Fraud Detection dataset from Kaggle, which encompasses credit card transactions executed by cardholders in Europe. The dataset encompasses a total of 284,807 transactions, of which 492 are identified as fraudulent. To maintain confidentiality, the dataset solely comprises numerical input variables resulting from Principal Component Analysis (PCA) transformations. The included features consist of 'Time', 'Amount', 'V1' through 'V28', and the 'Class' variable, which signifies whether a transaction is fraudulent (1) or not (0).

The project will commence with exploratory data analysis (EDA) to gain deeper insights into the data. Subsequently, data processing and modeling will be conducted, entailing the construction of various classification models to forecast instances of fraudulent transactions. Furthermore, we will address the issue of imbalanced classes by employing undersampling techniques. Lastly, we will assess the models' performance and select the most suitable one based on evaluation metrics such as precision, recall, F1-score, and accuracy.

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
