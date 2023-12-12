# Summary of 56_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.5
- **min_samples_split**: 50
- **max_depth**: 5
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

14.9 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.805521 |   0 |    0.791005 |   0.801554 |    0.532175 |       0.772559 |  0.540911 |
| recall    |    0.929145 |   0 |    0.645092 |   0.801554 |    0.524746 |       0.801554 |  0.540911 |
| f1-score  |    0.862928 |   0 |    0.710636 |   0.801554 |    0.524521 |       0.781797 |  0.540911 |
| support   | 3486        | 193 | 1854        |   0.801554 | 5533        |    5533        |  0.540911 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3239 |                0 |              247 |
| Labeled as 1 |              124 |                0 |               69 |
| Labeled as 2 |              658 |                0 |             1196 |

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
