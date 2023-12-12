# Summary of 96_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
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

15.9 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.817696 |   0 |    0.779375 |   0.806615 |    0.532357 |       0.776333 |  0.514774 |
| recall    |    0.922547 |   0 |    0.6726   |   0.806615 |    0.531716 |       0.806615 |  0.514774 |
| f1-score  |    0.866963 |   0 |    0.722061 |   0.806615 |    0.529675 |       0.788168 |  0.514774 |
| support   | 3486        | 193 | 1854        |   0.806615 | 5533        |    5533        |  0.514774 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3216 |                0 |              270 |
| Labeled as 1 |              110 |                0 |               83 |
| Labeled as 2 |              607 |                0 |             1247 |

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
