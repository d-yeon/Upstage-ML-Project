# Summary of 115_RandomForest_SelectedFeatures

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
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

20.6 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.830399 |   0 |    0.777977 |   0.814567 |    0.536125 |       0.783868 |  0.479759 |
| recall    |    0.919966 |   0 |    0.701187 |   0.814567 |    0.540384 |       0.814567 |  0.479759 |
| f1-score  |    0.872891 |   0 |    0.737589 |   0.814567 |    0.536826 |       0.797106 |  0.479759 |
| support   | 3486        | 193 | 1854        |   0.814567 | 5533        |    5533        |  0.479759 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3207 |                0 |              279 |
| Labeled as 1 |              101 |                0 |               92 |
| Labeled as 2 |              554 |                0 |             1300 |

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
