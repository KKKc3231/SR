# 超分辨率重构

## 展开网络用于超分

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221006210253187.png" alt="image-20221006210253187" style="zoom: 67%;" />

- 基于模型的方法可以有效地处理上式，可以处理不同的模糊核k，下采样倍数↓s，以及噪音n;
- 基于学习的模型处理上式有很大的局限性，因为基于学习的模型要训练，所以只能处理一种k，↓s，n;
- USRNet是针对非盲超分的网络，使用半二次分裂算法来迭代的计算，分为数据模块和先验模块

## 深度展开网络的问题分解（Unfolding Network）

- 将深度展开网络分解为两个子问题，分别为数据子问题和先验子问题

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221007171655127.png" alt="image-20221007171655127" style="zoom: 67%;" />

半二次分裂算法

- 固定X，首先求解Zk，Zk逐渐逼近于Xk-1；
- 求解得到Zk，然后根据式6来求解Xk;
- 然后交替的进行迭代;

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221010155247682.png" alt="image-20221010155247682" style="zoom: 50%;" />

## 退化模型

超分中的退化模型是指如何将HR图像变到LR

IR（图像恢复）方法

- 基于模型的IR方法：通过简单的指定来灵活地处理各种IR任务；直接在`退化图像`上进行优化 
- 基于深度学习的IR方法

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221021202551940.png" alt="image-20221021202551940" style="zoom:50%;" />

k：模糊核

sita：噪声水平

idea:

1、图像超分辨率一般不用Dropout，因为对于超分问题来说，有很多的解空间。但是模糊核如果只用一种，使用Dropout性能会下降，如果模糊核有多种，则Dropout这种方法会使效果提升，会提高泛化性能。展开网络中好像没有使用Dropout。

2、展开网络中噪声水平是人为给出的，看论文代码也是需要手动设置，不同的噪声水平会导致不同的超分结果。

- Dropout helps prevent co-adapting

- Dropout helps improve generalization ability



## 损失函数

`Loss Function`为L1损失（均值）+ VGG损失（感知损失）+ 对抗损失\

# 傅里叶变换、

## 傅里叶变化

- 没有信息的损失，只是换了个角度看问题

