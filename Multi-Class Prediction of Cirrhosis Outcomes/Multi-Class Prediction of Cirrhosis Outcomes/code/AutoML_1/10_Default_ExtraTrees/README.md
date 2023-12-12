# Summary of 10_Default_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
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

9.8 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.809333 |   0 |    0.782805 |   0.801916 |    0.530713 |       0.772213 |   0.53733 |
| recall    |    0.925416 |   0 |    0.653182 |   0.801916 |    0.526199 |       0.801916 |   0.53733 |
| f1-score  |    0.86349  |   0 |    0.712143 |   0.801916 |    0.525211 |       0.782657 |   0.53733 |
| support   | 3486        | 193 | 1854        |   0.801916 | 5533        |    5533        |   0.53733 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3226 |                0 |              260 |
| Labeled as 1 |              117 |                0 |               76 |
| Labeled as 2 |              643 |                0 |             1211 |

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
