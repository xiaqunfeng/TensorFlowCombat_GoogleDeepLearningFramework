## 《Tensorflow实战Google深度学习框架》学习笔记

![Tensorflow实战Google深度学习框架](images/cover.JPEG)

## note

- 在 [caicloud / tensorflow-tutorial](https://github.com/caicloud/tensorflow-tutorial) 和 [TensorFlow_learning_notes](https://github.com/cookeem/TensorFlow_learning_notes) 的基础上对代码进行了必要的注释；

- 对 tensorflow 老版本中被遗弃的特性代码进行修正和注释说明；
- 在ipynb文件中添加了自己的学习笔记。

## 版本

Tensorflow版本：

```
>>> import tensorflow as tf
>>> tf.__version__
'1.10.0'
```

python版本：

```
▶ python3 --version
Python 3.6.5
```

## 本书目录

###第1章 深度学习简介 

1.1 人工智能、机器学习与深度学习 
1.2 深度学习的发展历程 
1.3 深度学习的应用 

* 1.3.1 计算机视觉 
* 1.3.2 语音识别 
* 1.3.3 自然语言处理 
* 1.3.4 人机博弈 

1.4 深度学习工具介绍和对比 

### 第2章 TensorFlow环境搭建 
2.1 TensorFlow的主要依赖包 

* 2.1.1 Protocol Buffer 
* 2.1.2 Bazel 

2.2 TensorFlow安装 

* 2.2.1 使用Docker安装 
* 2.2.2 使用pip安装 
* 2.2.3 从源代码编译安装 

2.3 TensorFlow测试样例 

### 第3章 TensorFlow入门 
3.1 TensorFlow计算模型——计算图 

- 3.1.1 计算图的概念 
- 3.1.2 计算图的使用 

3.2 TensorFlow数据模型——张量 

- 3.2.1 张量的概念 
- 3.2.2 张量的使用 

3.3 TensorFlow运行模型——会话 
3.4 TensorFlow实现神经网络 

- 3.4.1 TensorFlow游乐场及神经网络简介 
- 3.4.2 前向传播算法简介 
- 3.4.3 神经网络参数与TensorFlow变量 
- 3.4.4 通过TensorFlow训练神经网络模型 
- 3.4.5 完整神经网络样例程序 

### 第4章 深层神经网络 
4.1 深度学习与深层神经网络 

- 4.1.1 线性模型的局限性 
- 4.1.2 激活函数实现去线性化 
- 4.1.3 多层网络解决异或运算 

4.2 损失函数定义 

- 4.2.1 经典损失函数 
- 4.2.2 自定义损失函数 

4.3 神经网络优化算法 
4.4 神经网络进一步优化 

- 4.4.1 学习率的设置 
- 4.4.2 过拟合问题 
- 4.4.3 滑动平均模型 

### 第5章 MNIST数字识别问题 
5.1 MNIST数据处理 
5.2 神经网络模型训练及不同模型结果对比 

- 5.2.1 TensorFlow训练神经网络 
- 5.2.2 使用验证数据集判断模型效果 
- 5.2.3 不同模型效果比较 

5.3 变量管理 
5.4 TensorFlow模型持久化 

- 5.4.1 持久化代码实现 
- 5.4.2 持久化原理及数据格式 

5.5 TensorFlow最佳实践样例程序 

### 第6章 图像识别与卷积神经网络 
6.1 图像识别问题简介及经典数据集 
6.2 卷积神经网络简介 
6.3 卷积神经网络常用结构 

- 6.3.1 卷积层 
- 6.3.2 池化层 

6.4 经典卷积网络模型 

- 6.4.1 LeNet-5模型 
- 6.4.2 Inception-v3模型 

6.5 卷积神经网络迁移学习 

- 6.5.1 迁移学习介绍 
- 6.5.2 TensorFlow实现迁移学习 

### 第7章 图像数据处理 
7.1 TFRecord输入数据格式 

- 7.1.1 TFRecord格式介绍 
- 7.1.2 TFRecord样例程序 

7.2 图像数据处理 

- 7.2.1 TensorFlow图像处理函数 
- 7.2.2 图像预处理完整样例 

7.3 多线程输入数据处理框架 

- 7.3.1 队列与多线程 
- 7.3.2 输入文件队列 
- 7.3.3 组合训练数据（batching） 
- 7.3.4 输入数据处理框架 

### 第8章 循环神经网络 
8.1 循环神经网络简介 
8.2 长短时记忆网络（LTSM）结构 
8.3 循环神经网络的变种 

- 8.3.1 双向循环神经网络和深层循环神经网络 
- 8.3.2 循环神经网络的dropout 

8.4 循环神经网络样例应用 

- 8.4.1 自然语言建模 
- 8.4.2 时间序列预测 

### 第9章 TensorBoard可视化 
9.1 TensorBoard简介 
9.2 TensorFlow计算图可视化 

- 9.2.1 命名空间与TensorBoard图上节点 
- 9.2.2 节点信息 

9.3 监控指标可视化 

### 第10章 TensorFlow计算加速 
10.1 TensorFlow使用GPU 
10.2 深度学习训练并行模式 
10.3 多GPU并行 
10.4 分布式TensorFlow 

- 10.4.1 分布式TensorFlow原理 
- 10.4.2 分布式TensorFlow模型训练 
- 10.4.3 使用Caicloud运行分布式TensorFlow 