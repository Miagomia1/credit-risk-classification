# credit-risk-classification
#Loan Prediction Model Analysis
#Overview
#This project involves building and evaluating a logistic regression model to classify loans as either healthy (0) or high-risk (1). The purpose of this analysis is to assist the company in making informed decisions regarding loan approvals by leveraging machine learning techniques to minimize financial risks and improve operational efficiency.

#Results
#The logistic regression model was evaluated on key performance metrics, with the following outcomes:

#Accuracy:

#The model achieved an accuracy score of 99%, meaning it correctly classified 99% of all loan statuses.
#Precision:

#For 0 (healthy loans): 1.00 – All loans predicted as healthy were accurate.
#For 1 (high-risk loans): 0.86 – 86% of loans predicted as high-risk were accurate.
#Recall:

#For 0 (healthy loans): 0.99 – 99% of actual healthy loans were correctly identified.
#For 1 (high-risk loans): 0.94 – 94% of actual high-risk loans were correctly identified.
#Summary
#The logistic regression model provides a reliable solution for classifying loans:

#Strengths:

#Near-perfect performance for healthy loans with 1.00 precision and 0.99 recall.
#Strong recall for high-risk loans, ensuring 94% of actual high-risk loans are identified.
#Weaknesses:

#Precision for high-risk loans could be improved. While the model achieves 86% precision for high-risk loans, 14% of predictions in this category are false positives.
#Recommendation:

#Recommended for deployment: The model’s exceptional accuracy and reliable performance make it suitable for use by the company in its current state. To further enhance precision for high-risk loans, additional optimization or inclusion of more features is suggested.
#Instructions
#Data: Prepare your dataset with the following columns:

#loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status.
#Model Training:

#The logistic regression model was trained using the sklearn library with an 80/20 train-test split.
#Evaluation:

#Confusion matrix and classification report metrics were used to assess model performance.
#Next Steps:

#Further refine the model by exploring alternative algorithms or incorporating additional features to improve high-risk loan precision.














