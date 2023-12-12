# Summary of 73_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.1
- **max_depth**: 7
- **min_child_weight**: 25
- **subsample**: 0.9
- **colsample_bytree**: 0.5
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

17.1 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.847838 |   0.586207  |    0.796729 |   0.830652 |    0.743591 |       0.821586 |  0.446574 |
| recall    |    0.92226  |   0.0880829 |    0.735707 |   0.830652 |    0.582017 |       0.830652 |  0.446574 |
| f1-score  |    0.883484 |   0.153153  |    0.765003 |   0.830652 |    0.600547 |       0.818308 |  0.446574 |
| support   | 3486        | 193         | 1854        |   0.830652 | 5533        |    5533        |  0.446574 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3215 |                4 |              267 |
| Labeled as 1 |               95 |               17 |               81 |
| Labeled as 2 |              482 |                8 |             1364 |

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
