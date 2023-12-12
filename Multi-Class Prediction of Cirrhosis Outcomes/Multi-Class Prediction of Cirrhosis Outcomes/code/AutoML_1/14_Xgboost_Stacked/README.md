# Summary of 14_Xgboost_Stacked

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

44.4 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.847417 |   0.58     |    0.79274  |   0.828122 |    0.740052 |       0.819768 |  0.452854 |
| recall    |    0.917671 |   0.150259 |    0.730313 |   0.828122 |    0.599414 |       0.828122 |  0.452854 |
| f1-score  |    0.881146 |   0.238683 |    0.760247 |   0.828122 |    0.626692 |       0.818225 |  0.452854 |
| support   | 3486        | 193        | 1854        |   0.828122 | 5533        |    5533        |  0.452854 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3199 |               10 |              277 |
| Labeled as 1 |               87 |               29 |               77 |
| Labeled as 2 |              489 |               11 |             1354 |

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
