# 机器学习常用评测指标

## TPR、FPR&TNR
-|预测1|预测0
---|---|---
实际1|True Positive(TP)|False Negative(FN)
实际0|False Positive(FP)|True Negative(TN)
### 真正类率(true positive rate ,TPR)

## 精确率Precision、召回率Recall和F1值
### 准确率Precision
- 定义：预测正确的正例数据占预测为正例数据的比例
- 公式：
```math
P = \frac{TP}{(TP+FP)}
```

### 召回率Recall
- 定义：预测为正例的数据占实际为正例数据的比例
- 公式：
```math
R = \frac{TP}{(TP+FN)}
```

### 综合评价指标F-measure
- 定义：Precision和Recall加权调和平均
- 公式：
```math
F = \frac{(a^2+1)*P*R}{a^2*(P+R)}
```
当参数α=1时，就是最常见的F1。因此，F1综合了P和R的结果，当F1较高时则能说明试验方法比较有效

### F1值
- 定义：为了能够评价不同算法的优劣，在Precision和Recall的基础上提出了F1值的概念，来对Precision和Recall进行整体评价
- 公式：
```math
F1 = \frac{2*P*R}{P+R}
```

## References
- [机器学习算法常用指标总结](http://www.cnblogs.com/maybe2030/p/5375175.html#_label1)
- [准确率，召回率，F1 值、ROC，AUC、mse,mape评价指标](https://blog.csdn.net/a819825294/article/details/51699211)
