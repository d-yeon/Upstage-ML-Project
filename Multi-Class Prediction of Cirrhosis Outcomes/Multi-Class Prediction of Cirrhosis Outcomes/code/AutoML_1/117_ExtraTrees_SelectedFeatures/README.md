# Summary of 117_ExtraTrees_SelectedFeatures

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 40
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

17.4 seconds

### Metric details
|           |           0 |            1 |           2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------------:|-------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |    0.822511 |   1          |    0.789408 |   0.812941 |    0.87064  |       0.81761  |  0.505217 |
| recall    |    0.926563 |   0.00518135 |    0.683387 |   0.812941 |    0.538377 |       0.812941 |  0.505217 |
| f1-score  |    0.871442 |   0.0103093  |    0.732582 |   0.812941 |    0.538111 |       0.794875 |  0.505217 |
| support   | 3486        | 193          | 1854        |   0.812941 | 5533        |    5533        |  0.505217 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |             3230 |                0 |              256 |
| Labeled as 1 |              110 |                1 |               82 |
| Labeled as 2 |              587 |                0 |             1267 |

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
