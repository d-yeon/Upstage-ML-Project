# Summary of 49_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
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

11.2 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.822811 |   0 |    0.790654 |   0.813483 |    0.537822 |       0.783335 |  0.508562 |
| recall    |    0.927137 |   0 |    0.684466 |   0.813483 |    0.537201 |       0.813483 |  0.508562 |
| f1-score  |    0.871864 |   0 |    0.733738 |   0.813483 |    0.535201 |       0.795169 |  0.508562 |
| support   | 3486        | 193 | 1854        |   0.813483 | 5533        |    5533        |  0.508562 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3232 |                0 |              254 |
| Labeled as 1 |              111 |                0 |               82 |
| Labeled as 2 |              585 |                0 |             1269 |

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
