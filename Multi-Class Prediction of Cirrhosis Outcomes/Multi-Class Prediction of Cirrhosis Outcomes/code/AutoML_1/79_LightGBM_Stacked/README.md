# Summary of 79_LightGBM_Stacked

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

21.5 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.843034 |   0.613636 |    0.791371 |   0.825411 |    0.749347 |       0.817721 |  0.453417 |
| recall    |    0.918244 |   0.139896 |    0.722222 |   0.825411 |    0.593454 |       0.825411 |  0.453417 |
| f1-score  |    0.879033 |   0.227848 |    0.755217 |   0.825411 |    0.6207   |       0.814831 |  0.453417 |
| support   | 3486        | 193        | 1854        |   0.825411 | 5533        |    5533        |  0.453417 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3201 |                8 |              277 |
| Labeled as 1 |               90 |               27 |               76 |
| Labeled as 2 |              506 |                9 |             1339 |

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
