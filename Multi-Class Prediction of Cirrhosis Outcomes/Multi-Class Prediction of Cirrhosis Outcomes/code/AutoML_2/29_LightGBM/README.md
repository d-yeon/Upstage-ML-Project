# Summary of 29_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 15
- **learning_rate**: 0.05
- **feature_fraction**: 1.0
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

9.2 seconds

### Metric details
|           |           0 |          1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-----------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.847947 |   0.641026 |    0.789994 |   0.828484 |    0.759656 |       0.82131  |  0.453147 |
| recall    |    0.918244 |   0.129534 |    0.73247  |   0.828484 |    0.593416 |       0.828484 |  0.453147 |
| f1-score  |    0.881697 |   0.215517 |    0.760146 |   0.828484 |    0.61912  |       0.81773  |  0.453147 |
| support   | 3486        | 193        | 1854        |   0.828484 | 5533        |    5533        |  0.453147 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3201 |                5 |              280 |
| Labeled as 1 |               87 |               25 |               81 |
| Labeled as 2 |              487 |                9 |             1358 |

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
