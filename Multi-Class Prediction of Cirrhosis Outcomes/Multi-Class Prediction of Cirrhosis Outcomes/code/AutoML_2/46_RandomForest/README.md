# Summary of 46_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.6
- **min_samples_split**: 20
- **max_depth**: 4
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

14.5 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.818022 |   0 |    0.797289 |   0.812218 |    0.538437 |       0.782541 |  0.503553 |
| recall    |    0.934882 |   0 |    0.666127 |   0.812218 |    0.53367  |       0.812218 |  0.503553 |
| f1-score  |    0.872557 |   0 |    0.72583  |   0.812218 |    0.532796 |       0.792955 |  0.503553 |
| support   | 3486        | 193 | 1854        |   0.812218 | 5533        |    5533        |  0.503553 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3259 |                0 |              227 |
| Labeled as 1 |              106 |                0 |               87 |
| Labeled as 2 |              619 |                0 |             1235 |

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
