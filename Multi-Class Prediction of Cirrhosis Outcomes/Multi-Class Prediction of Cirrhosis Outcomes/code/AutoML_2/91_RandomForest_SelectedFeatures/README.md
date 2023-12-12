# Summary of 91_RandomForest_SelectedFeatures

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
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

20.1 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.830067 |   0 |    0.78429  |   0.816374 |    0.538119 |       0.785774 |  0.484488 |
| recall    |    0.923408 |   0 |    0.700108 |   0.816374 |    0.541172 |       0.816374 |  0.484488 |
| f1-score  |    0.874253 |   0 |    0.739812 |   0.816374 |    0.538022 |       0.798709 |  0.484488 |
| support   | 3486        | 193 | 1854        |   0.816374 | 5533        |    5533        |  0.484488 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3219 |                0 |              267 |
| Labeled as 1 |              103 |                0 |               90 |
| Labeled as 2 |              556 |                0 |             1298 |

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
