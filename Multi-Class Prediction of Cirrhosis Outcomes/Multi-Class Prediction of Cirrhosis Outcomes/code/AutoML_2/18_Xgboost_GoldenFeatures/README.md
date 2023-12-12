# Summary of 18_Xgboost_GoldenFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.05
- **max_depth**: 8
- **min_child_weight**: 5
- **subsample**: 0.5
- **colsample_bytree**: 0.8
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

16.0 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.847296 |   0.7       |    0.786904 |   0.827761 |    0.778067 |       0.821922 |  0.456344 |
| recall    |    0.91681  |   0.0725389 |    0.738943 |   0.827761 |    0.576097 |       0.827761 |  0.456344 |
| f1-score  |    0.880683 |   0.131455  |    0.76217  |   0.827761 |    0.591436 |       0.814837 |  0.456344 |
| support   | 3486        | 193         | 1854        |   0.827761 | 5533        |    5533        |  0.456344 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3196 |                4 |              286 |
| Labeled as 1 |               94 |               14 |               85 |
| Labeled as 2 |              482 |                2 |             1370 |

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
