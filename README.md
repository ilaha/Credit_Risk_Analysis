# Credit_Risk_Analysis
Analyzing Credit Card Risk by using Machine Learning


# Overview: 

By using the data set from the LendingClub (*a lending service company*) I've analysed the credit risks for the customers. In this project, six different machine learning models have been used, such as RandomOverSampler, SMOTE, RandomUnderSampler, SMOTEENN, especially, BalancedRandomForestClassifier, and EasyEnsembleClassifier in order to reduce the bias and predict the credit risk.



## Results:

### RandomOverSampler:

![Screenshot](/images/RandomOverSampler.png "img1")

### Smote:

![Screenshot](/images/smote.png "img1")

### RandomUnderSampler:

![Screenshot](/images/RandomUnderSampler.png "img1")

### Combination (Over and Under) Sampling - Smoteen:

![Screenshot](/images/smoteen.png "img1")

### BalancedRandomForestClassifier:

![Screenshot](/images/brc.png "img1")

### EasyEnsembleClassifier:

![Screenshot](/images/eec.png "img1")



## Summary:

Most of the ML models were not much successful to predict the high risk customers. Because if we look at the results, it appears that most of the customers are not in high risk, which is of course not accurate. This tells me that it wass probably not the best idea to use logistic regression for this type of data analysis. 

Out of all models, Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier made the most sense, but yet still not too accurate due to having the low precision score and the predictions of the high risk and the low risk loans being heavily skewed.

