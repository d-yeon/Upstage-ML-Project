# Summary of 40_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
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

15.1 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.832385 |   0 |    0.784643 |   0.818001 |    0.539009 |       0.787353 |  0.482394 |
| recall    |    0.923121 |   0 |    0.705502 |   0.818001 |    0.542874 |       0.818001 |  0.482394 |
| f1-score  |    0.875408 |   0 |    0.742971 |   0.818001 |    0.53946  |       0.800495 |  0.482394 |
| support   | 3486        | 193 | 1854        |   0.818001 | 5533        |    5533        |  0.482394 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3218 |                0 |              268 |
| Labeled as 1 |              102 |                0 |               91 |
| Labeled as 2 |              546 |                0 |             1308 |

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
