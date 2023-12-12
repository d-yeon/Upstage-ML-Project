# Summary of 110_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.15
- **depth**: 5
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

17.4 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.846418 |   0.866667  |    0.788473 |   0.828303 |    0.833852 |       0.827708 |  0.454402 |
| recall    |    0.918531 |   0.0673575 |    0.737864 |   0.828303 |    0.574584 |       0.828303 |  0.454402 |
| f1-score  |    0.881002 |   0.125     |    0.762329 |   0.828303 |    0.589444 |       0.814866 |  0.454402 |
| support   | 3486        | 193         | 1854        |   0.828303 | 5533        |    5533        |  0.454402 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3202 |                1 |              283 |
| Labeled as 1 |               96 |               13 |               84 |
| Labeled as 2 |              485 |                1 |             1368 |

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
