# Credit_Risk_Analysis

# Overview of the Project


Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


# Results

Below are the results from the various techniques used as predictive models for High-Risk loans:


# SMOTEENN:

![Resample SMOTEENN](https://user-images.githubusercontent.com/101373142/178127350-2a237b91-c13a-44ac-97a0-5a588402acc9.png)


# SMOTE:

![Resample SMOTE](https://user-images.githubusercontent.com/101373142/178127358-1e7274f8-c88e-4c87-8315-7128c562b5a4.png)


# Random Over Sample:


![Random Over Sampler](https://user-images.githubusercontent.com/101373142/178127374-c4704e1e-d040-4672-83c6-83775f9abb17.png)


# Cluster Centroid:


![Cluster Centroids Resampler](https://user-images.githubusercontent.com/101373142/178127383-9793b395-5eab-47d2-8d53-df38a9535253.png)


# Easy Ensamble Classifier:


![Easy Ensamble](https://user-images.githubusercontent.com/101373142/178127400-0b397c1b-381a-4c35-aa4d-347ad1c7f537.png)


# Balanced Random Forest Classifier:


![Balanced Random Forest](https://user-images.githubusercontent.com/101373142/178127418-a2617368-d8b8-404f-bd72-591ef73e2681.png)


# Summary

For all models, utlizing the Easy Ensemble Classifier is most effective. This model provides the highest score for all high risk loans, and identifies high risk loans with greater precision.
