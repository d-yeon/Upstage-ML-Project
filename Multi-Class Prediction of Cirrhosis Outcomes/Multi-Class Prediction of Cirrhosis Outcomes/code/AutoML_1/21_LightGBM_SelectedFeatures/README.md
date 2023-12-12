# Summary of 21_LightGBM_SelectedFeatures

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 15
- **learning_rate**: 0.05
- **feature_fraction**: 0.8
- **bagging_fraction**: 0.5
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

10.8 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.848726 |   0.675676 |    0.790509 |   0.829387 |    0.771637 |       0.823183 |  0.451452 |
| recall    |    0.917384 |   0.129534 |    0.736785 |   0.829387 |    0.594568 |       0.829387 |  0.451452 |
| f1-score  |    0.88172  |   0.217391 |    0.762702 |   0.829387 |    0.620605 |       0.818667 |  0.451452 |
| support   | 3486        | 193        | 1854        |   0.829387 | 5533        |    5533        |  0.451452 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3198 |                4 |              284 |
| Labeled as 1 |               90 |               25 |               78 |
| Labeled as 2 |              480 |                8 |             1366 |

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
