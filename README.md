# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to predict credit risk using different models.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Naive Random Oversampling
![NaiveBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/NaiveBA.PNG)
![Naive](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/Naive.PNG)

- Balanced Accuracy: 64%
- Precision: 1% for high risk and 100% for low risk
- Recall: 69% for high risk and 59% for low risk

### SMOTE Oversampling
![SMOTEBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/SMOTEBA.PNG)
![SMOTE](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/SMOTE.PNG)

- Balanced Accuracy: 66%
- Precision: 1% for high risk and 100% for low risk
- Recall: 63% for high risk and 69% for low risk

### Undersampling
![UndersamplingBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/UndersamplingBA.PNG)
![Undersampling](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/Undersampling.PNG)

- Balanced Accuracy: 54%
- Precision: 1% for high risk and 100% for low risk
- Recall: 69% for high risk and 40% for low risk

### Combination (Over and Under) Sampling
![CombinationBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/CombinationBA.PNG)
![Combination](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/Combination.PNG)

- Balanced Accuracy: 64%
- Precision: 1% for high risk and 100% for low risk
- Recall: 72% for high risk and 57% for low risk

### Balanced Random Forest Classifier
![BRFCBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/BalancedRandomForestClassifierBA.PNG)
![BRFC](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/BalancedRandomForestClassifier.PNG)

- Balanced Accuracy: 79%
- Precision: 3% for high risk and 100% for low risk
- Recall: 70% for high risk and 87% for low risk

### Easy Ensemble AdaBoost Classifier
![EEABCBA](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/EasyEnsembleAdaBoostClassifierBA.PNG)
![EEABC](https://github.com/bernardinoe/Credit_Risk_Analysis/blob/main/EasyEnsembleAdaBoostClassifier.PNG)

- Balanced Accuracy: 93%
- Precision: 9% for high risk and 100% for low risk
- Recall: 92% for high risk and 94% for low risk


## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
Out of all the models, the most recommended model for this type of analysis would be the "Easy Ensemble AdaBoost Classifier". This model provided not only the biggest balanced accuracy, but also the highest presicion and recall for high risk and low risk.