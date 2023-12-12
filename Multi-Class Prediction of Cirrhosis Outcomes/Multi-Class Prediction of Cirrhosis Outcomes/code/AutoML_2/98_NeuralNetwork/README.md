# Summary of 98_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 8
- **learning_rate**: 0.01
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

16.8 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.831045 |   0 |    0.754155 |   0.806796 |    0.5284   |       0.776293 |  0.518382 |
| recall    |    0.903041 |   0 |    0.709817 |   0.806796 |    0.537619 |       0.806796 |  0.518382 |
| f1-score  |    0.865549 |   0 |    0.731314 |   0.806796 |    0.532288 |       0.790378 |  0.518382 |
| support   | 3486        | 193 | 1854        |   0.806796 | 5533        |    5533        |  0.518382 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3148 |                0 |              338 |
| Labeled as 1 |              102 |                0 |               91 |
| Labeled as 2 |              538 |                0 |             1316 |

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
