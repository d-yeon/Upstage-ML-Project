# Summary of 74_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.1
- **max_depth**: 7
- **min_child_weight**: 25
- **subsample**: 0.9
- **colsample_bytree**: 0.7
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

11.1 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.849351 |   0.548387  |    0.798261 |   0.831737 |    0.732    |       0.821734 |  0.448453 |
| recall    |    0.920252 |   0.0880829 |    0.742718 |   0.831737 |    0.583685 |       0.831737 |  0.448453 |
| f1-score  |    0.883382 |   0.151786  |    0.769489 |   0.831737 |    0.601552 |       0.819699 |  0.448453 |
| support   | 3486        | 193         | 1854        |   0.831737 | 5533        |    5533        |  0.448453 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3208 |                6 |              272 |
| Labeled as 1 |              100 |               17 |               76 |
| Labeled as 2 |              469 |                8 |             1377 |

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
