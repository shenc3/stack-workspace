


> Written with [StackEdit](https://stackedit.io/).

1. 准确率的局限性
	1. 评估指标选择：当数据集不平衡时，准确率无法评估模型效果
	2. 模型欠拟合和过拟合
	3. 数据集划分
	4. 线下评估和线上测试的样本分布存在差异等

2. 精确率和召回率的权衡
	1. 为了综合评估一个排序模型的好坏，不仅要看topN情况下的precision@N和recall@N，还要绘制出模型的P-R曲线。整条P-R曲线是通过将阈值从高到低移动得到的
	2. 多分类情况下可以使用micro average或weighted macro average指标，其实这两个指标是一致的

3. 平方根误差的“意外”
	1. 平方根误差的定义 $RMSE = \sqrt{\large\frac{\sum^n_{i=1}(y_i - \hat{y}_i)^2}{n}}$
	2. 一般情况下，RMSE能够很好地反映回归模型预测值和实际值的偏离程度，但如果存在**离群点**（outlier）的话，RMSE指标会变得很差
	3. 处理方法：
		* 离群点是噪声，考虑将其过滤
		* 离群点不是噪声，那么就需要进一步加强模型的预测能力，将离群点产生的机制建模进去
		* 可以找一个更合适的指标来评估模型。例如平均绝对百分比误差（Mean Absolute Percent Error, MAPE），定义为$MAPE=\sum_{i=1}^n\large|\frac{y_i - \hat{y}_i}{y_i}| \times \frac{100}{n}$

4. 什么是ROC曲线
5. 如何绘制ROC曲线
6. 如何计算AUC
7. ROC曲线相比P-R曲线有什么特点？


9. 为什么要进行在线A/B测试
10. 如何进行线上A/B测试
11. 过拟合和欠拟合具体是指什么现象

12. 为什么在 一些场景中要使用余弦相似度而不是欧氏距离？
13. 如何划分实验组和对照组
14. 模型评估过程中的验证方法及其优缺点
15. 能否说出集中降低过拟合和欠拟合风险的方法？

16. 余弦距离是否是一个严格定义的距离？
17. 自助法采样在极限情况下会有多少数据从未被选择过？
18. 超参数有哪些调优方法？


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcwMjc0ODM5NywtMTI2NTI5MDg3NSwtOD
cyODI5OTc2LDU2MzgxMzY0Myw1NDgxOTcxMzQsNzMwOTk4MTE2
XX0=
-->