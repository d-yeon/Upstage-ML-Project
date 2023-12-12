# Summary of 97_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
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

15.8 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.825263 |   0 |    0.786503 |   0.813844 |    0.537255 |       0.783489 |  0.507411 |
| recall    |    0.923982 |   0 |    0.691478 |   0.813844 |    0.538487 |       0.813844 |  0.507411 |
| f1-score  |    0.871837 |   0 |    0.735936 |   0.813844 |    0.535924 |       0.795888 |  0.507411 |
| support   | 3486        | 193 | 1854        |   0.813844 | 5533        |    5533        |  0.507411 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3221 |                0 |              265 |
| Labeled as 1 |              110 |                0 |               83 |
| Labeled as 2 |              572 |                0 |             1282 |

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
