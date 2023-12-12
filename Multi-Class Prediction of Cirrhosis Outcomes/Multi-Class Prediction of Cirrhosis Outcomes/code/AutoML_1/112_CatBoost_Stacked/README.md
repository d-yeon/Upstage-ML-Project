# Summary of 112_CatBoost_Stacked

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.15
- **depth**: 4
- **rsm**: 0.7
- **loss_function**: MultiClass
- **eval_metric**: MultiClass
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

33.2 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.849272 |   0.574468 |    0.798948 |   0.831375 |    0.740896 |       0.822824 |  0.448696 |
| recall    |    0.919679 |   0.139896 |    0.737325 |   0.831375 |    0.598967 |       0.831375 |  0.448696 |
| f1-score  |    0.883074 |   0.225    |    0.7669   |   0.831375 |    0.624991 |       0.821192 |  0.448696 |
| support   | 3486        | 193        | 1854        |   0.831375 | 5533        |    5533        |  0.448696 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3206 |                9 |              271 |
| Labeled as 1 |               93 |               27 |               73 |
| Labeled as 2 |              476 |               11 |             1367 |

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
