# Summary of 58_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 16
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

12.6 seconds

### Metric details
|           |           0 |   1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|----:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.837409 |   0 |    0.741027 |   0.805711 |    0.526145 |       0.775903 |  0.528821 |
| recall    |    0.893861 |   0 |    0.72384  |   0.805711 |    0.539234 |       0.805711 |  0.528821 |
| f1-score  |    0.864715 |   0 |    0.732333 |   0.805711 |    0.532349 |       0.790194 |  0.528821 |
| support   | 3486        | 193 | 1854        |   0.805711 | 5533        |    5533        |  0.528821 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3116 |                0 |              370 |
| Labeled as 1 |               94 |                0 |               99 |
| Labeled as 2 |              511 |                1 |             1342 |

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
