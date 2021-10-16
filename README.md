# Bank Retention Prediction

## Project Description
In this project the fictive customer Beta Bank observes that customers are leaving little by little, chipping away every month.  
The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones. 
To be able to bind customers which are willing to leave to the bank the bank requests model which predicts whether a customer will leave the bank soon.  
Therefore the Bank supplied the data on clients’ past behaviour and termination of contracts with the bank.  

The bank requests a model, where the F1 score should be maximized and must be at least 0.59 for the test set.  
Additionally, the AUC-ROC score should be measured and compared with the F1-score.

## Content
Within the project the following steps have been carried out:

- Loading and checking the data
- Data preprocessing
- Exploratory Data Analysis
- Different approaches on dealing on class imbalance and the evaluation of each approach wit crossvalidation
- Encoding categorical features
- Scaling of features
- Model building, training and evaluation
- Hyperparameter tuning

## Observations
- In final a model with an accuracy of around 61% has been developed by using random forests with the downsampled dataset
- Random forests in general are better for this project (min 55%, logreg 50% tops an.)
- For logistic regression the imbalances of the classes has a higer impact on the f1 score than for random forests (compare standard imbalanced model)
- In order to train the model the following steps have been carried out 
- Tuning the hyperparamerters increased the model accuracy of 2-3%
