


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



4. 什么是ROC曲线
5. 为什么要进行在线A/B测试
6. 如何进行线上A/B测试
7. 过拟合和欠拟合具体是指什么现象
8. 如何绘制ROC曲线
9. 如何计算AUC
10. 为什么在 一些场景中要使用余弦相似度而不是欧氏距离？
11. 如何划分实验组和对照组
12. 模型评估过程中的验证方法及其优缺点
13. 能否说出集中降低过拟合和欠拟合风险的方法？
14. ROC曲线相比P-R曲线有什么特点？
15. 余弦距离是否是一个严格定义的距离？
16. 自助法采样在极限情况下会有多少数据从未被选择过？
17. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NjYyMjA1NDAsLTg3MjgyOTk3Niw1Nj
M4MTM2NDMsNTQ4MTk3MTM0LDczMDk5ODExNl19
-->