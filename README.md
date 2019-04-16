# Classification performance standard

## Description

001 `Classification-Performance-Standard.ipynb` Classification performance standards such as accuracy, precision, recall, confusion matrix, F1, ROC, AUC. Take MNIST as example.

002 `Classification-Performance-Standard.ipynb` The framework to evaluate multi-classification classifier automatically.

## Standard

<img src="https://latex.codecogs.com/gif.latex?\mathrm{Accuracy=\frac{TP&plus;TN}{P&plus;N}}" title="\mathrm{Accuracy=\frac{TP+TN}{P+N}}" />

<img src="https://latex.codecogs.com/gif.latex?\mathrm{ErrorRate=1-Accuracy}" title="\mathrm{ErrorRate=1-Accuracy}" />

<img src="https://latex.codecogs.com/gif.latex?\mathrm{Precision=\frac{TP}{TP&plus;FP}}" title="\mathrm{Precision=\frac{TP}{TP+FP}}" />

<img src="https://latex.codecogs.com/gif.latex?\mathrm{Recall=\frac{TP}{TP&plus;FN}}" title="\mathrm{Recall=\frac{TP}{TP+FN}}" />

<img src="https://latex.codecogs.com/gif.latex?\mathrm{F1=\frac{2×TP}{n\_samples&plus;TP-TN}}" title="\mathrm{F1=\frac{2×TP}{n\_samples+TP-TN}}" />

Confusion matrix

||Predict Positive | Predict Negative |
|--|--|--|
|Actual Positive | TP(True Positive) | FN(False Negative)|
|Actual Negative|FP(False Positive)|TN(True Negative)|

![Confusion matrix](https://github.com/vba34520/Classification-Performance-Standard/blob/master/picture/Confusion%20matrix.png)

The vertical axis of the ROC(Receiver Operating Characteristic) curve is TPR(True Positive Rate) and the horizontal axis is FPR(False Positive Rate).

<img src="https://latex.codecogs.com/gif.latex?\mathrm{TPR=\frac{TP}{TP&plus;FN}}" title="\mathrm{TPR=\frac{TP}{TP+FN}}" />

<img src="https://latex.codecogs.com/png.latex?\mathrm{FPR=\frac{FP}{TN&plus;FP}}" title="FPR=\frac{FP}{TN+FP}" />

AUC is the area under ROC curve.

<img src="https://latex.codecogs.com/png.latex?\mathrm{AUC}=\frac{1}{2}\sum_{i=1}^{m-1}(x_{i&plus;1}-x_{i})*(y_{i}&plus;y_{i&plus;1})" title="AUC=\frac{1}{2}\sum_{i=1}^{m-1}(x_{i+1}-x_{i})*(y_{i}+y_{i+1})" />

![ROC](https://github.com/vba34520/Classification-Performance-Standard/blob/master/picture/ROC.png)

![ROC(each class)](https://github.com/vba34520/Classification-Performance-Standard/blob/master/picture/ROC(each%20class).png)
