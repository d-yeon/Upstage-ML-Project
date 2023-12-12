# Summary of 80_LightGBM_SelectedFeatures_Stacked

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

18.0 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.842838 |   0.659091 |    0.794537 |   0.826676 |    0.765489 |       0.820244 |  0.452185 |
| recall    |    0.919966 |   0.150259 |    0.721683 |   0.826676 |    0.597302 |       0.826676 |  0.452185 |
| f1-score  |    0.879715 |   0.244726 |    0.75636  |   0.826676 |    0.626933 |       0.816231 |  0.452185 |
| support   | 3486        | 193        | 1854        |   0.826676 | 5533        |    5533        |  0.452185 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3207 |                8 |              271 |
| Labeled as 1 |               89 |               29 |               75 |
| Labeled as 2 |              509 |                7 |             1338 |

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
