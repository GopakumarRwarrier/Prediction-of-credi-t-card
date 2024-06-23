# Prediction-of-credi-t-card
Predicting a credit transaction is legit or fraud
# **Credit Card Fraud Detection**
**This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used for this project is highly imbalanced, which is typical for fraud detection problems.**   

## **Introduction**      

A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 


## **Dataset**  

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## **Features**    

**Time**: Number of seconds elapsed between this transaction and the first transaction in the dataset.   

**V1-V28**: Result of a PCA transformation. These are the principal components. 

**Amount**: Transaction amount.

**Class**: Target variable (1 for fraudulent transactions, 0 for genuine transactions)    

## **Requirements**    

* Python 3.6+    
* Jupyter Notebook       
* pandas    
* numpy   
* scikit-learn    
* imbalanced-learn   
* matplotlib   
* seaborn   

## Model Training and Evaluation    
* **Algorithms used:**     

* Logistic Regression   
* Decision Tree    
* Random Forest    

**Evaluation Metrics:**

* Accuracy     
* Precision    
* Recall    
* F1-Score    
* ROC-AUC
## **Results**    
The model achieved the following results on the test dataset before tuning:    

* Accuracy: 93.29%   
* Precision: 96.29%      
* Recall: 89.65%     
* F1-Score: 92.85%
    
The model achieved the following results on the test dataset before tuning:

* Accuracy: 94.41%     
* Precision: 90.00%    
* Recall: 100.00%     
* F1-Score: 95.00%
* ROC-AUC: 94.25%

## **Conclusion**     

The project successfully demonstrates the application of various machine learning techniques to detect fraudulent credit card transactions.







