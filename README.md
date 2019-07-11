# Spam or Ham

This  notebook is a summarized version of Spam detection problem using GridSearch and SVC (Support Vector Classifier).
Original problem link:
https://www.kaggle.com/uciml/sms-spam-collection-dataset

For original and comprehensive tutorial guide , please go to below link:
https://www.kaggle.com/dejavu23/sms-spam-or-ham-beginner 

Original tutorial mentioned above uses many classifier and builds a confusion matrix for all for finding the best fit model. 

What this notebook consists:

1. Word clouds for spam and ham messages
2. Bar plots for 30 most common spam and ham messages
3. Pipeline process for model builiding using below components

    a. CountVectorizer
    b. TfidfTransformer
    c. SVC (Support Vector Classifier)
  
4. A gridsearch using all cpu cres for finding best hyper model
5. prediction and accuracy score
6. Classification report for the model
