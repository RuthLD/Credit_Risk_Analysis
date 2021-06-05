# Credit_Risk_Analysis
Evaluate several machine learning models to asses credit card risk.
## Overview:
Use six machine learning models to evaluate which has the highest accuracy and precision in evaluating credit card risk.
## Results:
### Native Random Oversampling Model
* ![NROversampling.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/NROversampling.png)
### SMOTE Model
* ![SMOTE.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
### Undersampling Model
* ![SMOTEENN.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)
### SMOTEENN Model
* ![Undersampling.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)
### Balanced Random Rainforest Model
* ![BRRainforest.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/BRRainforest.png)
### Easy Ensemble Model
* ![EEnsemble.png](https://github.com/RuthLD/Credit_Risk_Analysis/blob/main/Resources/EEnsemble.png)
## Summary:
The summary of model results is presented in order of highest accuracy score to lowest accuracy score.
* The Easy Ensemble model has the highest accuracy score (0.93) and the F-1 score for low risk (0.97) is also the highest. 
  *  The recommended model for credit card analysis would be the Easy Ensemble model.
* The Balanced Random Rainforest model has the second highest accuracy score at 0.79 and the F-1 score is 0.95. 
* The Naïve Random Oversampling model has an accuracy of 0.66 and a F-1 score of 0.80 for low risk. 
* The SMOTE model has an accuracy score of 0.63 and the F-1 score is 0.78 for low risk.
* The SMOTEENN model has an accuracy score of 0.62 and the F-1 score is 70 for low risk.
* UnderSampling has the lowest accuracy score at 0.51 and F-1 score of 0.60. 
  * Because of how low both scores are the Undersampling model is not recommended for credit card risk analysis.
