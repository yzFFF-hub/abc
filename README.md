# KNN算法解决约会问题（导论实验报告）
# 1.问题描述
## 1.1关于这个问题
Helen经常上约会网站寻求一段姻缘，对于每一个她交往过的人，收集他们的数据，Helen根据他们的特征对他们分类，分为3个喜欢程度（即3个类别）。当一个新的交往对象出现时，评估他们的特征，把他分到已有的3个类别。
## 1.2问题的形式化描述
问题的形式化描述将在实验报告中给出。
# 2.系统
## 2.1系统架构
- **读取模块**

- **归一化模块**

- **算法模块**

- **训练与测试**

- **应用模块**
## 2.2各个部分介绍（具体内容在报告中给出）
- **file2matrix**


- **autoNorm**


- **classify0**


- **datingClassTest**


- **classifyPerson**

## 2.3算法的伪代码
```
分类器算法(测试样本，训练样本， 目标变量集，k）：
	用线性运算求出训练样本每个记录与测试样本的距离
	
	对距离进行排序

	for i in range(k):

		算出前k个分类变量中每个分类变量的数目

	返回数目最多的那个变量
```
# 3.实验
## 3.0算法原理及其优缺点
具体内容在报告中给出
## 3.1实验环境
- PyCharm
- Python3
- Numpy
- Matplotlib
## 3.2数据
数据集作为附件存在压缩包中，命名为"datingTestSet2.txt"
## 3.3实验结果展示
具体内容在报告中给出
# 4.总结与展望
具体内容在报告中给出
# 参考文献
[1][【五分钟机器学习】环境会影响你的决策：K近邻算法（KNN)_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV13K411H7Zs?from=search&seid=11304396467388631258&spm_id_from=333.337.0.0)

[2][(34条消息) 机器学习实战——练习（kNN——约会网站）_Dlog的博客-CSDN博客_knn约会](https://blog.csdn.net/m0_37970224/article/details/86133735)

[3][深入浅出KNN算法（一） KNN算法原理 - zzzzMing - 博客园 (cnblogs.com)](https://www.cnblogs.com/listenfwind/p/10311496.html)
