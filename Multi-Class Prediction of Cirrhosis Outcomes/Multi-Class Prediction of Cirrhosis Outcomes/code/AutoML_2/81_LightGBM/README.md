# Summary of 81_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.2
- **feature_fraction**: 0.5
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 20
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

9.8 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.847981 |   0.581395 |    0.793651 |   0.829207 |    0.741009 |       0.820477 |  0.457651 |
| recall    |    0.921687 |   0.129534 |    0.728155 |   0.829207 |    0.593125 |       0.829207 |  0.457651 |
| f1-score  |    0.883299 |   0.211864 |    0.759494 |   0.829207 |    0.618219 |       0.818394 |  0.457651 |
| support   | 3486        | 193        | 1854        |   0.829207 | 5533        |    5533        |  0.457651 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3213 |                7 |              266 |
| Labeled as 1 |               83 |               25 |               85 |
| Labeled as 2 |              493 |               11 |             1350 |

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
