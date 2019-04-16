# Classification performance standard

## Description

001 `Classification-Performance-Standard.ipynb` Classification performance standards such as accuracy, precision, recall, confusion matrix, F1, ROC, AUC. Take MNIST as example.

002 `Classification-Performance-Standard.ipynb` The framework to evaluate multi-classification classifier automatically.

## Standard

$$Accuracy=\frac{TP+TN}{P+N}$$

$ErrorRate=1-Accuracy$

$Precision=\frac{TP}{TP+FP}$

$Recall=\frac{TP}{TP+FN}$

$F1=\frac{2×TP}{n\_samples+TP-TN}$

Confusion matrix

||Predict Positive | Predict Negative |
|--|--|--|
|Actual Positive | TP(True Positive) | FN(False Negative)|
|Actual Negative|FP(False Positive)|TN(True Negative)|

![Confusion matrix](https://github.com/vba34520/Classification-Performance-Standard/blob/master/picture/Confusion%20matrix.png)

The vertical axis of the ROC(Receiver Operating Characteristic) curve is TPR(True Positive Rate) and the horizontal axis is FPR(False Positive Rate).

$TPR=\frac{TP}{TP+FN}$

$FPR=\frac{FP}{TN+FP}$

AUC is the area under ROC curve.

$AUC=\frac{1}{2}\sum_{i=1}^{m-1}(x_{i+1}-x_{i})*(y_{i}+y_{i+1})$



