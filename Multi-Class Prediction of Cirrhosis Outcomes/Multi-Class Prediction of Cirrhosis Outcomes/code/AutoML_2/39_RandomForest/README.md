# Summary of 39_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.5
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

11.6 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.820526 |   0 |    0.792644 |   0.812579 |    0.537723 |       0.782562 |  0.503219 |
| recall    |    0.931153 |   0 |    0.674218 |   0.812579 |    0.535124 |       0.812579 |  0.503219 |
| f1-score  |    0.872346 |   0 |    0.728651 |   0.812579 |    0.533666 |       0.793768 |  0.503219 |
| support   | 3486        | 193 | 1854        |   0.812579 | 5533        |    5533        |  0.503219 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3246 |                0 |              240 |
| Labeled as 1 |              106 |                0 |               87 |
| Labeled as 2 |              604 |                0 |             1250 |

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
