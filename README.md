Purpose of this challenge is to train and evaluate a model to predict risk for loans.

Key notes about the original data provided for this:
Significantly imbalanced data with far more healthy loans (75036 Healthy Loans vs 2500 Unhealth Loans). As such there may be an inherent bias in the data (selection)

Analysis otherwise:
Healthy Loans: Precision - 1.00, Recall 0.99 and F1 1.00
Indicates that in general for healthy loans the prediction rate is highly accurate. Appears to perform incredibly well for predicting healthy loans.

Unhealthy Loans: Precision 0.84, Recall 0.94 and F1 0.89
Indicates that up to 16% of loans predicted as unhealthy are actually healthy, whereas only 6% of healthy loans are misclassified. The F1 score although not perfect, is reasonable.

Overall, the model performs quite well for the purposes of credit-risk assessment for a business. 
Minor caution should be taken when using the model for unhealthy loans and depending on the volume of loans involved misclassification could result in significant
repercussions for clients borrowing. This could impact decision making around lending, and may reduce funds incoming as a result (although noted that only 2500 out of 77000 loans are unhealthy - overall a small proportion)
Despite the small issue above, I would recommend this model for use given the statistical analysis and power within the remits of just the parameters specified. 
Potentially a more detailed model could use additional features for more detailed analysis.
