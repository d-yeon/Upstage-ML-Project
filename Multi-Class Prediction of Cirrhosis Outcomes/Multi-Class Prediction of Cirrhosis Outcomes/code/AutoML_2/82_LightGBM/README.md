# Summary of 82_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.2
- **feature_fraction**: 0.5
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 50
- **metric**: multi_logloss
- **custom_eval_metric_name**: None
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

9.7 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.849037 |   0.642857 |    0.802585 |   0.833183 |    0.764826 |       0.82628  |  0.451828 |
| recall    |    0.922834 |   0.139896 |    0.736785 |   0.833183 |    0.599839 |       0.833183 |  0.451828 |
| f1-score  |    0.884399 |   0.229787 |    0.768279 |   0.833183 |    0.627488 |       0.822655 |  0.451828 |
| support   | 3486        | 193        | 1854        |   0.833183 | 5533        |    5533        |  0.451828 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3217 |                9 |              260 |
| Labeled as 1 |               90 |               27 |               76 |
| Labeled as 2 |              482 |                6 |             1366 |

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
