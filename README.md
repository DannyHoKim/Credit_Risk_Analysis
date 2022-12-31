# Credit Risk Analysis

## Overview

In this analysis, we are applying machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. This is the case with the dataset used in this analysis. Because of this, this analysis will use different techniques to train and evaluate models with unbalanced classes. 

## Results

### Naive Random Oversampling Results:

![ROS](Starter_Code/Resources/ROS.png)

![rosresults](Starter_Code/Resources/rosresults.png)

- Balanced Accuracy: 63%
- Precision High/Low: 0.01/1.00
- Recall: 57% of high risk applicants are identified as high risk and 68% of low risk applicants are identified as low risk.

### SMOTE Oversampling:

![smote](Starter_Code/Resources/smote.png)

![smoteresults](Starter_Code/Resources/smoteresults.png)

- Balanced Accuracy: 63%
- Precision High/Low: 0.01/1.00
- Recall: 62% of high risk applicants are identified as high risk and 63% of low risk applicants are identified as low risk.

### Cluster Centroids Undersampling:

![undersampling](Starter_Code/Resources/undersampling.png)

![undersamplingresults](Starter_Code/Resources/undersamplingresults.png)

- Balanced Accuracy: 63%
- Precision High/Low: 0.01/1.00
- Recall: 59% of high risk applicants are identified as high risk and 44% of low risk applicants are identified as low risk.

### SMOTEENN Combination Sampling:

![combination](Starter_Code/Resources/combination.png)

![combinationresults](Starter_Code/Resources/combinationresults.png)

- Balanced Accuracy: 51%
- Precision High/Low: 0.01/1.00
- Recall: 70% of high risk applicants are identified as high risk and 58% of low risk applicants are identified as low risk.

### Balanced Random Forester Classifer:

![brfc](Starter_Code/Resources/brfc.png)

![brfcresults](Starter_Code/Resources/brfcresults.png)

- Balanced Accuracy: 79%
- Precision High/Low: 0.03/1.00
- Recall: 70% of high risk applicants are identified as high risk and 87% of low risk applicants are identified as low risk.

### Easy Ensemble AdaBoost Classifer:

![eeac](Starter_Code/Resources/eeac.png)

![eeacresults](Starter_Code/Resources/eeacresults.png)

- Balanced Accuracy: 93%
- Precision High/Low: 0.09/1.00
- Recall: 92% of high risk applicants are identified as high risk and 94% of low risk applicants are identified as low risk.

