# Summary of 18_Xgboost_KMeansFeatures

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.05
- **max_depth**: 8
- **min_child_weight**: 5
- **subsample**: 0.5
- **colsample_bytree**: 0.8
- **eval_metric**: mlogloss
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

21.7 seconds

### Metric details
|           |           0 |           1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.844122 |   0.818182  |    0.784686 |   0.825411 |    0.815663 |       0.823301 |  0.462368 |
| recall    |    0.916523 |   0.0466321 |    0.735167 |   0.825411 |    0.566108 |       0.825411 |  0.462368 |
| f1-score  |    0.878834 |   0.0882353 |    0.75912  |   0.825411 |    0.575396 |       0.811143 |  0.462368 |
| support   | 3486        | 193         | 1854        |   0.825411 | 5533        |    5533        |  0.462368 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3195 |                1 |              290 |
| Labeled as 1 |              100 |                9 |               84 |
| Labeled as 2 |              490 |                1 |             1363 |

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
