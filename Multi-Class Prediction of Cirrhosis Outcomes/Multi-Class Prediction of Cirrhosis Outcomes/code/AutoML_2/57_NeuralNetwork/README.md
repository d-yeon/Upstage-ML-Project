# Summary of 57_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 4
- **learning_rate**: 0.05
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

12.3 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.8332   |   0 |    0.743517 |   0.804446 |    0.525573 |       0.774086 |  0.541483 |
| recall    |    0.898451 |   0 |    0.711435 |   0.804446 |    0.536629 |       0.804446 |  0.541483 |
| f1-score  |    0.864596 |   0 |    0.727122 |   0.804446 |    0.530573 |       0.788373 |  0.541483 |
| support   | 3486        | 193 | 1854        |   0.804446 | 5533        |    5533        |  0.541483 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3132 |                0 |              354 |
| Labeled as 1 |               92 |                0 |              101 |
| Labeled as 2 |              535 |                0 |             1319 |

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
