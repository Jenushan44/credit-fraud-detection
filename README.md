# Credit Card Fraud Detection 

This project uses a Credit Card Fraud dataset to detect fraudulent transactions. 
The datasets is very imbalanced with there being very few fraud cases compared to non-fraud cases. 

## Steps 
1. Cleaned the dataset and split into training/testing sets
2. Trained two models: Logistic Regression and Random Forest with balancing for fraud cases
3. Checked how well the models worked using confusion matrix, precision, recall, F1-score and ROC-AUC
4. Compared the models with ROC curves and a simple results table

## Results 
- Logistic Regression: Higher recall, caught more fraud cases but more false alarms
- Random Forest: Higher precision, fewer false alarms but missed more fraud cases
- Both models were able to achieve high ROC-AUC (> 0.95)
