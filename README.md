

# CreditCard_Fraud_Detection

This project is  developed as a part of CMPE 255 Data Mining Course.

**Description**

The dataset includes credit card transactions carried out by European cardholders in September 2013. It contains information on transactions made in two days, with 492 fraudulent transactions out of 284,807 transactions. This means that the dataset is significantly imbalanced, with only 0.172% of transactions being classified as fraud. 

The dataset only contains numerical features that have undergone a PCA transformation, with the exception of 'Time' and 'Amount'. The 'Time' feature indicates the time elapsed between the first transaction and each subsequent transaction, while the 'Amount' feature represents the transaction amount. The response variable is 'Class', which takes a value of 1 for fraud and 0 for legitimate transactions.

Due to the class imbalance, it is recommended to evaluate the model performance using the Area Under the Precision-Recall Curve (AUPRC) instead of the confusion matrix accuracy. The latter is not meaningful in unbalanced classification problems. Unfortunately, the original features and more details about the data cannot be disclosed due to confidentiality concerns.

**Tasks performed**

Task 1: Data preprocessing and Data balancing of the dataset.
Task 2: Used 5 algorithms for Binary Classification .
Task 3: Model Evaluation

**Algorithms used**


Logistic Regression	
Support Vector Classifier	
Decision Tree Classifier:
Random Forest Classifier
K-Nearest Neighbors

**Instructions to run**

You will require Jupyter Notebook or any Python IDE with Python 3.0 or later installed to run the code.
Change the directory of the data while loading it.
