# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 4
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

1.4 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.801333 |   0 |    0.784605 |   0.796855 |    0.528646 |       0.767776 |  0.538758 |
| recall    |    0.93144  |   0 |    0.626753 |   0.796855 |    0.519398 |       0.796855 |  0.538758 |
| f1-score  |    0.861502 |   0 |    0.696852 |   0.796855 |    0.519451 |       0.77628  |  0.538758 |
| support   | 3486        | 193 | 1854        |   0.796855 | 5533        |    5533        |  0.538758 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3247 |                0 |              239 |
| Labeled as 1 |              113 |                0 |               80 |
| Labeled as 2 |              692 |                0 |             1162 |

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
