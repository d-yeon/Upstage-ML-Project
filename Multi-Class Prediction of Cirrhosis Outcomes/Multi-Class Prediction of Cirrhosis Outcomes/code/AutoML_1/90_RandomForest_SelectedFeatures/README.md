# Summary of 90_RandomForest_SelectedFeatures

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.6
- **min_samples_split**: 30
- **max_depth**: 7
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

26.2 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.830971 |   0 |    0.789346 |   0.818543 |    0.540106 |       0.788038 |  0.481742 |
| recall    |    0.925129 |   0 |    0.703344 |   0.818543 |    0.542824 |       0.818543 |  0.481742 |
| f1-score  |    0.875526 |   0 |    0.743868 |   0.818543 |    0.539798 |       0.80087  |  0.481742 |
| support   | 3486        | 193 | 1854        |   0.818543 | 5533        |    5533        |  0.481742 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3225 |                0 |              261 |
| Labeled as 1 |              106 |                0 |               87 |
| Labeled as 2 |              550 |                0 |             1304 |

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
