# Summary of 14_Xgboost_KMeansFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.1
- **max_depth**: 7
- **min_child_weight**: 25
- **subsample**: 0.9
- **colsample_bytree**: 0.6
- **eval_metric**: mlogloss
- **num_class**: 3
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 10

## Optimized metric
logloss

## Training time

18.7 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.844591 |   0.764706  |    0.790267 |   0.827399 |    0.799854 |       0.823601 |  0.457336 |
| recall    |    0.918244 |   0.0673575 |    0.735707 |   0.827399 |    0.573769 |       0.827399 |  0.457336 |
| f1-score  |    0.879879 |   0.12381   |    0.762011 |   0.827399 |    0.588567 |       0.814011 |  0.457336 |
| support   | 3486        | 193         | 1854        |   0.827399 | 5533        |    5533        |  0.457336 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3201 |                1 |              284 |
| Labeled as 1 |              102 |               13 |               78 |
| Labeled as 2 |              487 |                3 |             1364 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
