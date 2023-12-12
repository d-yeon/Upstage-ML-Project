# Summary of 27_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.05
- **feature_fraction**: 0.9
- **bagging_fraction**: 0.8
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

12.4 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.843824 |   0.657143 |    0.794239 |   0.827399 |    0.765069 |       0.820697 |  0.459227 |
| recall    |    0.919105 |   0.119171 |    0.728695 |   0.827399 |    0.58899  |       0.827399 |  0.459227 |
| f1-score  |    0.879857 |   0.201754 |    0.760056 |   0.827399 |    0.613889 |       0.816061 |  0.459227 |
| support   | 3486        | 193        | 1854        |   0.827399 | 5533        |    5533        |  0.459227 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3204 |                7 |              275 |
| Labeled as 1 |               95 |               23 |               75 |
| Labeled as 2 |              498 |                5 |             1351 |

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
