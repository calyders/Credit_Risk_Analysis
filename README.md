# Credit_Risk_Analysis
## Overview
In this analysis, we trained and evaluated models with unbalanced classes using the imbalanced-learn and scikit-learn libraries. Utilizing these libraries, we built and evaluated models using resampling. The purpose of this was to eventually use different machine learning models to predict credit risk and further decide whether these models should be used in the future to predict credit risk.
## Results
- In the Naive Random Oversampling model the balanced accuracy test came back with 66%, the precision for high risk at 1%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 72%, low risk at 60%, and the avg/total was 60%.

![Naive Random Oversampling](https://user-images.githubusercontent.com/115501756/222326682-cdf784a6-432b-4eca-bddd-15132f9088d7.png)

- In the SMOTE Oversampling model the balanced accuracy test came back with 66%, the precision for high risk at 1%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 61%, low risk at 70%, and the avg/total was 70%.

![SMOTE Oversampling](https://user-images.githubusercontent.com/115501756/222327008-8979ffe5-3163-4f32-8984-2d4ccd415302.png)

- In the Undersampling model the balanced accuracy test came back with 66%, the precision for high risk at 1%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 69%, low risk at 40%, and the avg/total was 40%.

![Undersampling](https://user-images.githubusercontent.com/115501756/222327347-e1a1dd06-2d9e-475e-8af7-039bfd9d8d35.png)

- In the Combination model the balanced accuracy test came back with 54%, the precision for high risk at 1%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 72%, low risk at 57%, and the avg/total was 57%.

![Combination](https://user-images.githubusercontent.com/115501756/222328346-8ad3b19b-0995-476c-8d19-d55e41c6e050.png)

- In the Balanced Random Forest Classifier model the balanced accuracy test came back with 78%, the precision for high risk at 4%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 67%, low risk at 89%, and the avg/total was 89%.

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/115501756/222328591-2271e97e-3323-440c-9b6f-9ec20a551099.png)

- In the Easy Ensemble AdaBoost Classifier model the balanced accuracy test came back with 92%, the precision for high risk at 9%, low risk at 100%, and the avg/total was 99%. The recall score for high risk was 89%, low risk at 94%, and the avg/total was 94%.

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/115501756/222328791-c7618480-ac0a-4a0e-80c9-a2bd82b9f95a.png)

## Summary
The oversampling, undersampling, and combination models all came back with low accuracy scores when compared to the ensemble classifiers. Because of this I would recommend using the ensemble classifiers and not the first four models we tried out.

In terms of the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier, I would go with the AdaBoost Classifier. This is due to the 94% recall accuracy as opposed to the 88% in the Random Forest Classifier.
