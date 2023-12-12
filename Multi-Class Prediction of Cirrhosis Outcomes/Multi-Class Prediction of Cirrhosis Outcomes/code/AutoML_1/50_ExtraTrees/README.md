# Summary of 50_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 40
- **max_depth**: 3
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

8.3 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.794541 |   0 |    0.78951  |   0.793241 |    0.528017 |       0.76514  |  0.557181 |
| recall    |    0.935169 |   0 |    0.608954 |   0.793241 |    0.514708 |       0.793241 |  0.557181 |
| f1-score  |    0.859138 |   0 |    0.687576 |   0.793241 |    0.515571 |       0.771683 |  0.557181 |
| support   | 3486        | 193 | 1854        |   0.793241 | 5533        |    5533        |  0.557181 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3260 |                0 |              226 |
| Labeled as 1 |              118 |                0 |               75 |
| Labeled as 2 |              725 |                0 |             1129 |

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
