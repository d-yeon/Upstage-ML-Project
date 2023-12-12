# Summary of 40_RandomForest_SelectedFeatures

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

17.4 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.8293   |   0 |    0.785931 |   0.816374 |    0.53841  |       0.78584  |  0.482576 |
| recall    |    0.923982 |   0 |    0.699029 |   0.816374 |    0.541004 |       0.816374 |  0.482576 |
| f1-score  |    0.874084 |   0 |    0.739937 |   0.816374 |    0.538007 |       0.798645 |  0.482576 |
| support   | 3486        | 193 | 1854        |   0.816374 | 5533        |    5533        |  0.482576 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3221 |                0 |              265 |
| Labeled as 1 |              105 |                0 |               88 |
| Labeled as 2 |              558 |                0 |             1296 |

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
