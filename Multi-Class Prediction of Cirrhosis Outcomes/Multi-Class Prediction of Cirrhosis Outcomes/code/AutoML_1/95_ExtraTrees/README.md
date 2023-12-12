# Summary of 95_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 40
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

15.5 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.826187 |   0 |    0.785104 |   0.814025 |    0.537097 |       0.783602 |  0.506695 |
| recall    |    0.923121 |   0 |    0.693635 |   0.814025 |    0.538919 |       0.814025 |  0.506695 |
| f1-score  |    0.871969 |   0 |    0.736541 |   0.814025 |    0.53617  |       0.796174 |  0.506695 |
| support   | 3486        | 193 | 1854        |   0.814025 | 5533        |    5533        |  0.506695 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3218 |                0 |              268 |
| Labeled as 1 |              109 |                0 |               84 |
| Labeled as 2 |              568 |                0 |             1286 |

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
