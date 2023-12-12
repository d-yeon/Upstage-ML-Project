# Summary of 9_Default_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
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

13.8 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.813843 |   0 |    0.796212 |   0.808964 |    0.536685 |       0.779547 |  0.506294 |
| recall    |    0.934309 |   0 |    0.657497 |   0.808964 |    0.530602 |       0.808964 |  0.506294 |
| f1-score  |    0.869925 |   0 |    0.720236 |   0.808964 |    0.530054 |       0.789423 |  0.506294 |
| support   | 3486        | 193 | 1854        |   0.808964 | 5533        |    5533        |  0.506294 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3257 |                0 |              229 |
| Labeled as 1 |              110 |                0 |               83 |
| Labeled as 2 |              635 |                0 |             1219 |

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
