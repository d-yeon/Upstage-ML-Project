# Summary of 54_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 40
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

16.3 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.809619 |   0 |    0.787151 |   0.803362 |    0.532257 |       0.77385  |  0.526185 |
| recall    |    0.927137 |   0 |    0.654261 |   0.803362 |    0.527133 |       0.803362 |  0.526185 |
| f1-score  |    0.864402 |   0 |    0.71458  |   0.803362 |    0.526328 |       0.784048 |  0.526185 |
| support   | 3486        | 193 | 1854        |   0.803362 | 5533        |    5533        |  0.526185 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3232 |                0 |              254 |
| Labeled as 1 |              119 |                0 |               74 |
| Labeled as 2 |              641 |                0 |             1213 |

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
