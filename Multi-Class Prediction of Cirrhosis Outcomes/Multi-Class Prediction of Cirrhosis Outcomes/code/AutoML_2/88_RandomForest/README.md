# Summary of 88_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.6
- **min_samples_split**: 30
- **max_depth**: 7
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

21.8 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.828704 |   0 |    0.783587 |    0.81529 |    0.53743  |       0.784679 |   0.48267 |
| recall    |    0.924269 |   0 |    0.695254 |    0.81529 |    0.539841 |       0.81529  |   0.48267 |
| f1-score  |    0.873881 |   0 |    0.736782 |    0.81529 |    0.536888 |       0.79746  |   0.48267 |
| support   | 3486        | 193 | 1854        |    0.81529 | 5533        |    5533        |   0.48267 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3222 |                0 |              264 |
| Labeled as 1 |              101 |                0 |               92 |
| Labeled as 2 |              565 |                0 |             1289 |

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
