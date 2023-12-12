# Summary of 79_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 15
- **learning_rate**: 0.05
- **feature_fraction**: 0.8
- **bagging_fraction**: 0.5
- **min_data_in_leaf**: 30
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

10.3 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.849628 |   0.605263 |    0.789717 |   0.829207 |    0.748203 |       0.821029 |  0.450876 |
| recall    |    0.917384 |   0.119171 |    0.737325 |   0.829207 |    0.591293 |       0.829207 |  0.450876 |
| f1-score  |    0.882207 |   0.199134 |    0.762622 |   0.829207 |    0.614654 |       0.81831  |  0.450876 |
| support   | 3486        | 193        | 1854        |   0.829207 | 5533        |    5533        |  0.450876 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3198 |                5 |              283 |
| Labeled as 1 |               89 |               23 |               81 |
| Labeled as 2 |              477 |               10 |             1367 |

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
