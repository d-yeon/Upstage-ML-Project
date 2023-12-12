# Summary of 43_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 50
- **max_depth**: 3
- **eval_metric_name**: logloss
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

13.7 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.804018 |   0 |    0.804962 |   0.804265 |    0.536327 |       0.776289 |  0.518057 |
| recall    |    0.94148  |   0 |    0.629989 |   0.804265 |    0.523823 |       0.804265 |  0.518057 |
| f1-score  |    0.867336 |   0 |    0.706808 |   0.804265 |    0.524715 |       0.783292 |  0.518057 |
| support   | 3486        | 193 | 1854        |   0.804265 | 5533        |    5533        |  0.518057 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3282 |                0 |              204 |
| Labeled as 1 |              114 |                0 |               79 |
| Labeled as 2 |              686 |                0 |             1168 |

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
